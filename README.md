# 수돗물 수요예측 AI 알고리즘 개발

## Host
- 주최 : 한국수자원공사(K-water)
- 주관 : AIFactory
- 기간 : 11월 21일 (월) 10:00 ~ 12월 09일 (금) 21: 55
- https://aifactory.space/competition/detail/2143

## About
유량 등의 배수지 운영 자료를 활용하여 수돗물 수요예측을 위한 AI 모델 개발    
대상지 별 각각의 상수원 수요 변화에 따라 달라지는 각 배수지의 유량 적산차(≒시간 단위 공급량)를 예측  
정확한 수요 예측은 수자원 사용 및 수자원 공급에 필요한 에너지 소비를 최적화하는 데에 기여  
본대회는 배수지 급수지역의 행정구역별로 총 3개의 Task로 구성  
[Task 1] 배수지 #1 | 행정 및 주거지역  
[Task 2] 배수지 #2 | 농업지역  
[Task 3] 배수지 #3 | 산업단지  
  
## 참조
Temporal Fusion Transformer를 통한 수요예측  
https://pytorch-forecasting.readthedocs.io/en/stable/tutorials/stallion.html
https://slowsteadystat.tistory.com/24  
model  
[Temporal Fusion Transformer](https://www.google.com/search?q=Temporal+Fusion+Transformer&biw=1920&bih=929&ei=siJ7Y7nkD4up-Qa835SYAg&ved=0ahUKEwi5hbKx2r77AhWLVN4KHbwvBSMQ4dUDCA8&uact=5&oq=Temporal+Fusion+Transformer&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQ6CggAEEcQ1gQQsANKBAhBGABKBAhGGABQywRY0AZgkAloAXABeACAAXqIAcgCkgEDMC4zmAEAoAEByAEKwAEB&sclient=gws-wiz-serp)