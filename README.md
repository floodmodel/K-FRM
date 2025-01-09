# K-FRM (Korean-Flood Risk assessment Model)
* K-FRM은 정량적 홍수 위험도 평가(Quantitative Flood Risk Assessment)를 구현하기 위한 프로그램입니다.
* K-FRM에 대한 자세한 내용은 위 [**Wiki 메뉴**](https://github.com/floodmodel/K-FRM/wiki) 및 [**동영상**](https://www.youtube.com/watch?v=PzIEDj--56g)에 설명되어 있습니다.
* [**build_inventory 폴더**](https://github.com/floodmodel/K-FRM/tree/main/build_inventory)에는 K-FRM에서 사용되는 [**Inventory DB 구축용 프로그램**](https://github.com/floodmodel/K-CDMS/wiki/Inventory-Builder)이 있습니다.
* K-FRM에서 사용되는 Inventory Data는 [**K-CDMS**](https://github.com/floodmodel/K-CDMS)에서 download 받을 수 있습니다.
* [**k-frm 폴더**](https://github.com/floodmodel/K-FRM/tree/main/k-frm)는 K-FRM에 대한 QGIS plug-in을 download 받을 수 있습니다.(최신날짜의 zip을 사용하세요) 
* QGIS3.10에서 운영되도록 개발되었습니다.
* [**2022년 KDI 예비타당성조사 수행을 위한 세부지침 수자원부분**](https://github.com/floodmodel/K-FRM/blob/main/Reference/%5B%EB%B3%B4%EA%B3%A0%EC%84%9C%5D%20%EC%98%88%EB%B9%84%ED%83%80%EB%8B%B9%EC%84%B1%EC%A1%B0%EC%82%AC%20%EC%88%98%ED%96%89%EC%9D%84%20%EC%9C%84%ED%95%9C%20%EC%84%B8%EB%B6%80%EC%A7%80%EC%B9%A8%20%EC%88%98%EC%9E%90%EC%9B%90%EB%B6%80%EB%AC%B8%20%EA%B0%9C%EC%A0%95%20%EC%97%B0%EA%B5%AC_%EC%B5%9C%EC%A2%85%EB%B3%B8.pdf) : KDI 지침에 K-FRM 반영 완료


<br/><br/>

# Update history
2021.10.07. (General, Professional version) Inventory-Building 메뉴의 UI 개선 <br/>
2021.10.18. (Professional version) 차량 인벤토리 업데이트 및 차량 가치 계산 기능 추가 <br/>
2021.11.24. (General, Professional version) 버전 통합 -->  k-frm 폴더에서 관리 <br/>
2022.02.09. 차량 인벤토리 피해액 결과 단위 수정 <br/>
2022.04.18. 격자 형태 피해액 산출 기능 추가 <br/>
2022.06.17. 2019년도 인벤토리 및 2019, 2020 원단위 Parameter 데이터 추가 <br/>
2022.06.20. 일부 오류 수정 <br/>
2022.07.27. UI 변경 <br/>
2022.08.19. 건물 인벤토리 개별 피해액 부분에 Bdtyp 추가  <br/>
2022.08.26. UI 개선 <br/>
2022.09.07. UI 개선, summary result 오류 수정 및 building 주거/비주거 구분 <br/>
2022.11.09. Metadata에 표시되는 ICON 크기 조정 <br/>
2022.12.22. Public sector loss UI 및 기능 변경, Annualized loss 기능 추가 <br/>
2023.02.24. Code Style 변경 <br/>
2023.10.20. PolygonZ 유형 Hazard Data가 입력으로 주어진 경우 사용자에게 정보 제공. Database 관련 처리 코드의 효율성 개선. 잠재적 오류 발생 구간의 회피 및 유지보수성 개선을 위한 Logging 기능 보완  <br/>
2024.04.30. Result Table Download 기능 추가 <br/>
2024.08.16. 사용자별로 Result Table 기본 저장 경로 설정 <br/>
