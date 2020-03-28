# 퀀트, 금융분석, 주가예측

## 목표: 주식자동매매, 웹서비스 구현을 위한 기반 알고리즘 공부

웹서비스 아이디어 정리
- 위험신호표시, 리스크 회피
    - 신용오실레이터, 어느정도 검증됨.
    - 딥러닝, 급락에 대해서만 학습
    - VIX지수, 선물, 미국채권, 금 활용방안?
- 주식종목 매매일지
    - 기존 증권사 hts의 매매일지와 다른점
        - 매수/매도사유 기입
        - 이미 매도한 종목에 대한 복기 -> 오답노트
        - (매수했거나 매도한)관심종목의 실적, 가치에 대한 확인이 쉽도록
        - 미래 예상실적, 정량적 가치평가가 있어야
   
울산투자스터디 발표자료 정리<br>
```관련주소: https://```

- [time_series_analysis (시계열분석)](time_series_analysis/)
    - 시계열분석 실습      
        - 시계열데이터 pandas스킬, ARIMA, prophet
    - LSTM모델 실습
      - LSTM모델 간단실습, 케라스창시자에게 배우는 딥러닝 6장
      - RNN, LSTM모델 설명, pdf정리

- [quant (종목분석/알고리즘/백테스팅)](quant/)
    - 경제지표확인
    - 관심종목실적정리
    - 관심종목주가가공
    - 재무데이터크롤링
    - 원자재 주가상관관계
    - 매매전략구현, 백테스팅
        - ref: 생활속 문제를 통해 배워보는 머신 러닝 7장
            - 종가매수시가매도 전략
            - 머신러닝(SVR)모델 전략
            - 동적시간워핑모델 전략
        - 변동성돌파전략
        - 평균회귀전략
    
- [paper_review (관련논문 리뷰)](paper_review/)
    - A hybrid stock trading framework integrating technical analysis with machine learning techniques
    , RajashreeDash, 2016
    - 거래량 급감 패턴의 감독 학습에 기반한 단기 주가 예측, 이재원, 2018
    

- [stock_data_with_api (증권사API사용 데이터수집)](stock_data_with_api/)
    - 대신증권API사용하기
    - 이베스트API사용하기
