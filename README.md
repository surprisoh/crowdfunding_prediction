# Crowdfunding_prediction

## 1. Problem
** A.  User들이 시각적으로 볼 수 있는 Crowd Funding 웹사이트의 공간은 한정적이다.**

** B.  Crowd Funding Company ** 
- 개설되는 프로젝트의 절대적인 개수도 중요하지만 각 프로젝트의 성공율도 중요하다.
- 각 프로젝트의 성공율은 결국 수익을 극대화하는 요소이다.
- 런칭할 프로젝트를 심사하는 과정을 조금 더 자동화할 수는 없을까?

** C.  Project Creator ** 
- Creator의 최대 목표는 펀딩 성공
- 펀딩이 성공하기 위한 가장 중요한 요소는 무엇일까?
- 프로젝트 설명에 영상을 첨부해야하는가? 펀딩 금액으로 얼마가 가장 적정한가? 

## 2. Solution

** A. 프로젝트의 펀딩이 시작되기 전 얻을 수 있는 정보로 성공 예측** 
- Features : 목표펀딩금액, 영상첨부 유/무, 설명글 문법오류 정도, 카테고리

** B.  펀딩 시작 후 얻을 수 있는 정보로 성공 예측 **
- Features : 목표펀딩금액, 문법오류정도, 카테고리, 각 날짜별 누적 펀딩율

## 3. Insight
- 설명글의 문법 오류정도는 성공 예측 정확도를 높여줍니다.
- 각 날짜별 누적 펀딩율은 많은 정보(프로젝트의 참신성, 마케팅효과 등)을 포함하고 있어 예측의 정확도를 급격히 높여줍니다.
