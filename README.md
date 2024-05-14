# fastAPI-realtime-project
FastAPI와 requests 라이브러리를 통해 외부 JSON 서버로부터 실시간 데이터 조회 및 분석, 시각화하는 웹 서비스

## 미세먼지 데이터 시각화 및 분석 웹 서비스
```
개발 기간 : 2023.05. ~ 2023. 06. (2개월)
개발 인원 : 2명 
프로젝트 내 역할 : 실시간 데이터 전처리 및 가공, 데이터 시각화, 검색어 예외처리
```

<개발 환경>

언어 : Python 3.10.12, HTML5/CSS3
서버 : Linux Ubuntu 22.04
프레임워크 : FastAPI
DB : MongoDB 4.4.24
IDE : Pycharm, Visual Studio Code
라이브러리 : pydantic, pandas, matplotlib, requests


<프로젝트 요약>

Notion : https://www.notion.so/54659c405cc847deaa2947dd554ce101
GitHub : https://github.com/SeguirLuna0114/fastAPI-realtime-project
https://github.com/SeguirLuna0114/23SW-Edu/tree/86a6b5b8b9479a1a13405c84331c71f0d21b9ae0/python/forproject

- FastAPI를 통해 외부 JSON서버로부터 데이터 가져오는 기능을 담당하는 API 엔드포인트 정의하여 MongoDB에 저장된 데이터 조회
- pymongo 라이브러리를 사용하여 MongoDB와 연결 설정 -> 데이터 저장 및 검색 작업 수행
- requests 라이브러리를 사용해 외부 JSON 서버에서 실시간 미세먼지 데이터를 가져옴
- JSON 서버에서 가져온 실시간 미세먼지 농도 데이터를 가공(pandas라이브러리)한 후, MongoDB에 저장
- matplotlib을 사용해 크롤링한 미세먼지 데이터의 '특정 연도 및 분기 데이터' 그래프 생성

