# 2023 NH 투자증권 빅데이터 경진대회
NH투자증권 빅데이터 공모전 수상작

## 대회 개요
- 주최: NH투자증권
- 후원: 블룸버그, 나스닥
- 주관: 데이콘
- 기간: 2023.09.04 ~ 2023.10.16
- 주제: 해외 뉴스 데이터를 이용한 투자 정보 분석

## 아이디어
### 소개
최근 뜨는 테마 관련 해외 종목 및 국내 수혜주 수익률 예측

### 배경
국내 개인투자자의 해외 주식 투자가 증가하고 있으며, 그 중 미국 주식에 대한 서비스의 필요성이 대두되고 있음.
2030세대를 중심으로 해외 주식 투자는 늘어나고 있으며, 이들은 스스로 투자 판단을 내리며 뉴스 기사로 투자 정보를 수집함.
투자자들은 종목의 성장성과 시장의 영향력을 기준으로 투자하며, 테마주에 관심이 많으며 그로 인해 테마주의 수혜주의 주가도 상승하고 있음.

### 문제 정의
*해외 주식 투자자의 Pain Point*
1. 시시각각 변하는 경제상황을 해외 뉴스를 통해 빠르게 파악하기 어려움
2. 투자 정보를 찾기 위해서는 많은 기사나 종목에 대한 정보를 접해야 함
3. 투자 초보들은 여러 정보들을 종합적으로 판단해 투자 결정을 내리기 어려움

### 인사이트 도출
테마주와 수혜주를 종목의 성장성과 시장의 영향력을 고려해 종합적으로 알려주는 서비스가 필요함
따라서 최근 뜨는 테마를 분석해 관련 해외 주식의 예상 수익률을 도출하고 이를 기반으로 국내 수혜주 종목을 제공하는 서비스

## 결과
- 예선 2위, 입선상 수상

## 모델링 과정
1. 8개월 간의 CNBC 뉴스 크롤링, yfinance 크롤링
2. BERTopic을 활용한 토픽모델링
3. 최근 성장하는 주식 테마 추출
4. 주식 테마와 관련있는 나스닥 테마주 추출
5. 유망한 테마주와 관련있는 국내 수혜주 추출 및 주가 상승률 예측

### 파생변수




[테마파크_본선_아이디어기획서.pdf](https://github.com/jydoong/NH_BigData_competition/files/14717193/_._.pdf)
