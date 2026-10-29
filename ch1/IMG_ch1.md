# 챕터 1 「변동성 이론」 이미지 제작 명세서

- 캐릭터 그림 출처: 공식 저장소 `adminmrobo/fruitfly-lab-expressions` @ `ea5da3f` (캐릭터 팩)
- 현재 상태: **모든 쪽이 별도 그림 파일 없이 완성.** 표정은 팩에서 골라 페이지 안에 넣었고(96px, 대결 머리 192px), 히어로·아웃트로 장면과 모든 실험 그림은 페이지 안 캔버스로 직접 그린다.
- 고정 외형: 박사 청록 사각 안경, 조수 이름표 "하루", 초파리 빨간 겹눈 + 남색 헬멧, Money-Robo 흰 머리 + 금빛 픽셀 눈. Money-Robo E19·E21("B" 금화)은 쓰지 않았다.

| 쪽 | 파일 | 주 앵커 | 들어간 표정 키 | 대결 결과 | 크기 |
|---|---|---|---|---|---|
| 1-1 | `1-1_time-series.html` | C | `asst_e01` `asst_e07` `asst_e10` `asst_e12` `asst_e13` `asst_e16` `doc_e07` `doc_e08` `doc_e09` `doc_e10` `doc_e13` `doc_e16` `fly_e07` `fly_e08` `fly_e13` `fly_e16` `fly_e21` `robo_e04` `robo_e07` `robo_e12` `robo_e13` `robo_e14` `robo_e16` `robo_e18` `robo_e20` | F (군집 끄면 D) | 406 KB |
| 1-2 | `1-2_efficient-market.html` | C | `asst_e01` `asst_e10` `asst_e12` `asst_e13` `asst_e16` `doc_e08` `doc_e09` `doc_e10` `doc_e13` `doc_e16` `fly_e07` `fly_e08` `fly_e09` `fly_e13` `fly_e16` `fly_e21` `robo_e07` `robo_e12` `robo_e13` `robo_e14` `robo_e16` `robo_e18` `robo_e20` | F (과잉반응 끄면 D) | 397 KB |
| 1-3 | `1-3_risk-measures.html` | C | `asst_e01` `asst_e07` `asst_e10` `asst_e12` `asst_e13` `asst_e16` `doc_e07` `doc_e08` `doc_e09` `doc_e10` `doc_e13` `doc_e16` `fly_e07` `fly_e08` `fly_e09` `fly_e13` `fly_e16` `fly_e21` `robo_e07` `robo_e12` `robo_e13` `robo_e14` `robo_e16` `robo_e18` `robo_e20` | F (군집 끄면 R) | 409 KB |
| 1-4 | `1-4_clustering-tests.html` | B | `asst_e01` `asst_e07` `asst_e10` `asst_e12` `asst_e13` `asst_e16` `doc_e08` `doc_e09` `doc_e10` `doc_e13` `doc_e16` `fly_e07` `fly_e08` `fly_e10` `fly_e13` `fly_e16` `fly_e21` `robo_e07` `robo_e09` `robo_e12` `robo_e13` `robo_e14` `robo_e16` `robo_e18` `robo_e20` | F (ML vs 적률) | 407 KB |
| 1-5 | `1-5_arch-garch.html` | C | `asst_e01` `asst_e10` `asst_e12` `asst_e13` `asst_e16` `doc_e07` `doc_e08` `doc_e09` `doc_e10` `doc_e13` `doc_e16` `fly_e07` `fly_e08` `fly_e09` `fly_e13` `fly_e16` `fly_e21` `robo_e07` `robo_e12` `robo_e13` `robo_e14` `robo_e16` `robo_e18` `robo_e20` | R (1,000일 R · 150일 F) | 401 KB |
| 1-6 | `1-6_asymmetry-decomposition.html` | C | `asst_e01` `asst_e07` `asst_e10` `asst_e12` `asst_e13` `asst_e16` `doc_e07` `doc_e08` `doc_e09` `doc_e10` `doc_e13` `doc_e16` `fly_e07` `fly_e08` `fly_e09` `fly_e13` `fly_e16` `fly_e21` `robo_e07` `robo_e12` `robo_e13` `robo_e14` `robo_e16` `robo_e18` `robo_e20` | R (레버리지 없는 시장 F) | 415 KB |
| 1-7 | `1-7_volatility-index.html` | C | `asst_e01` `asst_e07` `asst_e10` `asst_e12` `asst_e13` `asst_e16` `doc_e08` `doc_e09` `doc_e10` `doc_e13` `doc_e16` `fly_e07` `fly_e08` `fly_e09` `fly_e13` `fly_e16` `fly_e21` `robo_e07` `robo_e09` `robo_e12` `robo_e13` `robo_e14` `robo_e16` `robo_e18` `robo_e20` | F (스마일 없으면 D) | 408 KB |

## 나중에 바꾸면 좋은 것

- 히어로 장면을 손그림 일러스트로 바꾸려면: 쪽마다 1600×900 한 장(장부 앵커는 금화 탑 옆 Money-Robo, 연구실 앵커는 실험대 옆 박사·하루). 지금은 캔버스 장면이라 없어도 완성 상태다.
- 원자료(KRX 일별 섹터지수·KOSPI·VKOSPI)를 받으면 1-1·1-3·1-4·1-5·1-6의 모의 시장을 실제 자료로 바꾼다. 그림 모양은 그대로 쓸 수 있다.
