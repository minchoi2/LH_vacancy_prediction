# LH_vacancy_prediction

충분한 코드 및 데이터가 쌓일시

현재 사용자별 디렉토리 관리
->
Data종류별 코드 디렉토리로 변동예정

Ex)
'ㅁ'를 폴더 이모티콘으로 가정한다.

------------

## 파일 및 폴더 구조 (예시)
+
-ㅁdata <br>
ㄴㅁlabel <br>
   ㄴ~~~ # 주요 핵심 데이터 (지식산업센터 공실률 관련 데이터 등) <br>
ㄴㅁfinance <br>
   ㄴㅁout_effect # 환율 등, 외부 경제지표 <br>
   ㄴㅁin_effect  # 물가상ㅅ으률 등, 내부 경제지표 <br>
   ㄴㅁcard # 카드 매출 데이터 등 <br>
   ㄴㅁpopulation # 인구 및 인구이동 데이터 등 <br>
   ㄴㅁvacancy_rate_of_office # 기타 시설 공실률 데이터 등 <br> 
ㄴㅁinfra <br>
   ㄴㅁhospital # 주변 병원 <br> 
   ㄴㅁsubway # 주변 지하철 <br>
   ㄴㅁbus # 주변 버스 <br>
   ㄴㅁschool # 주변 학교 <br>
ㄴㅁbuilding <br>
   ㄴㅁcenters # 지.산.센 단지 정보 <br>
   ㄴㅁstores # 내부 건물 세부 정보 <br>
ㅁgraph <br>
ㅁmodel <br>
requirements.txt # 필요 파이썬 및 패키지 버전 <br>
config.py # 전역변수 혹은 옵션 등 모음 <br>  
