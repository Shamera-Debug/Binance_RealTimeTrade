# RealTimeTrade_Project
딥러닝 + 자동 매매

## 🖥️ 프로젝트 소개
암호화폐 주가 데이터를 활용하여 비트코인, 이더리움, 리플의 주가를 예측하여 자동 매매 시스템 개발
<br>

## 🕰️ 개발 기간
* 23.12. - 24.03.

### 🧑‍🤝‍🧑 맴버구성
- 김현준(팀장) : 데이터 수집 및 모델링, 실시간 매매 구현
- 백승호 : 데이터 분석 및 모델링
- 최지현 : 웹 구현
- 황진영 : 데이터 수집

### ⚙️ 개발 환경
언어   : Python   PHP   MySQL
DB     : MariaDB
IDE    : VSCode   DBeaver   MobaXterm
Server : GoogleCloud   Apache2
Data   : Binance   Investing.com   U.Today

### 개발 일정
![image](https://github.com/Shamera-Debug/Binance_RealTimeTrade/assets/68696549/44c5f7a1-4a53-4310-8b29-a894c47c6aa5)


## 📌 주요 기능
#### 회귀 모델 + 분류 모델 동시 사용
분류 모델을 사용하여 주가가 상승할지 하락할지에 대한 확실성을 높이고
회귀 모델을 통해 실제로 예상되는 수익률을 계산함으로써
수수료가 발생하더라도 이익을 볼 수 있는 거래 지점을 예측

#### 1분단위 주가 예측
주기적으로 Binance 서버 타임을 가져와 정확히 매분 00초에 예측 수행 -> 매매 방식으로 진행

#### Binance 지갑 정보
api_key와 api_secret 정보를 입력한 후 코드 이용가능
아래와 같은 정보 확인
![image](https://github.com/Shamera-Debug/Binance_RealTimeTrade/assets/68696549/4af9be2d-8ff2-451b-9f4d-1086f74cbdfb)

#### WEB 화면에서 현재 자산 정보 확인 가능(GCP 사용 현재 상태 : OFF)
사이트 주소 : http://35.216.66.247/wordpress/
![image](https://github.com/Shamera-Debug/Binance_RealTimeTrade/assets/68696549/c1a1aea1-6a0b-4129-83df-b87e1f2534e6)

