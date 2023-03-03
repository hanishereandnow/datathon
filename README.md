
# AIFFEL Datathon PROJECT
* 모두의연구소 산하 인공지능 교육기관 AIFFEL에서 진행된 데이터톤 프로젝트로서, 
  <br> Kaggle Instacart Basket Analysis (2017년 연간 데이터) 데이터를 기반으로 프로젝트를 진행하였습니다.
<br/><br/>

# 프로젝트명: [ Instacart 데이터 분석 기반의 <br/> 마케팅 전략 제안 ]
<br/>

## 문제 인식
* E-commerce 기업 Instacart의 매출 증대를 위한 데이터 분석에 초점
  (온라인 식료품 마켓 Instacart는 세계 최대규모 식료품 배송업체이며, 북미지역 업계 점유율 1위)
* 구매 대행 및 배달 서비스를 제공하고 이에 따른 수수료를 통해 수익을 창출하는 비즈니스 구조
  → 일반 상품 판매 수익 구조와는 매출 증대를 위한 전략이 다를 것으로 예상, 이를 데이터 분석을 통해 제시하고자 함
* 매출의 중요 키가 되는 VIP 고객의 기준을 실 데이터로 확인하고 이에 대한 전략을 제안하고자 함
  
<br/>
  
## 분석 목표
* 매출 증대를 위한 VIP 고객분석 및 제안
<br/>

## 데이터 분석
* ERD를 통한 데이터셋 구조화 및 기본 EDA로 구매 특성 파악
* 수수료를 통해 수익을 창출하므로, 매출과 직접 관련되어 있는 ‘고객 당 주문 횟수’를 통해 VIP 고객 설정
    - 이상치와 RFM 기법 활용하여 VIP 기준 설정
    - 구매율 높은 제품은 재구매율도 높은 특성 확인
* 서비스 이용에 충성도가 있는 VIP 고객 공략 + 구매율 낮은 제품의 구매율 상승이 필요
<br/>

## 솔루션 제시
* 제안사항:
    - 가장 주문량이 많은 월요일 오전 11시에,
    - 재주문량 하위권 대분류 제품군 대상으로,
    - VIP 고객에게 할인 쿠폰 제공

<br/>

## 보완 및 개선 가능성
* 클러스터링 기법을 적용한 모델링을 통해 VIP 분석 시도 가능성
    - VIP 고객과 상품 종류 간의 연관성 찾기
* 대용량(약 3천만 건) 데이터 전처리에 대한 깊이 있는 고민을 해 볼 필요성
    - 대분류, 소분류 별 상품에 대한 분석 시도 필요

<br/>

## 분석을 통해 배운 점
* 데이터 분석이 비즈니스 배경(도메인 지식)과 밀접한 관련이 있다는 점
* 같은 데이터셋이라도 어떤 목표에 초점을 맞추는 지에 따라 분석 방향이 달라질 수 있다는 점

## 요약 슬라이드
![image](https://user-images.githubusercontent.com/106140951/222625412-023adecd-fa09-4f84-a84c-c6ad9a08ff3e.png)
![image](https://user-images.githubusercontent.com/106140951/222625436-f9d3c9aa-9861-4947-b8cf-2230a9b45277.png)
![image](https://user-images.githubusercontent.com/106140951/222625455-2b242b80-9568-46ed-bfd8-f4871450ac92.png)
![image](https://user-images.githubusercontent.com/106140951/222625476-a3c4cbfc-dd30-48fa-a6b7-78be00c6f259.png)
![image](https://user-images.githubusercontent.com/106140951/222625486-559c5fbf-b0ae-430e-9c02-27d3b9ecc489.png)
![image](https://user-images.githubusercontent.com/106140951/222625505-4a51f568-d390-4f97-aef0-7f5f307a7276.png)
![image](https://user-images.githubusercontent.com/106140951/222625517-d718e8ff-e1ca-407b-9f8b-a56ea2aa872a.png)
![image](https://user-images.githubusercontent.com/106140951/222625531-44436195-fb1c-4346-8b20-367be1f3a19b.png)
![image](https://user-images.githubusercontent.com/106140951/222625540-5196de4f-ad5b-448e-a036-c6652bc260b6.png)
![image](https://user-images.githubusercontent.com/106140951/222625563-12ba3d4a-83b6-4f49-88aa-3354c01a4b26.png)



