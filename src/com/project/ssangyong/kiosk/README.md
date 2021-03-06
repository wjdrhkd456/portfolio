# 쌍용강북교육센터 두번째 프로젝트

- **프로젝트명** : Java를 기반으로 키오스크 구현하기
- **기술스택**
  - **언어** : Java
  - **IDE** : EditPlus
- **기간** : 2019-09-07 ~ 2019-09-13 
- **직책** : 팀장 
- **프로젝트 설명**
  - 순수 자바기반으로 구현한 키오스크 프로젝트이다. 
  - 주변식당의 현재 잔여 테이블수와 주차장 여유를 확인할 수 있으며, 음식조리시간이 얼마나 걸리는지를 확인할 수 있다. 
  - 모든 정보를 고려하여 선결제 후 식당을 이용하게끔 만든 플랫폼이다. 
- **구현 기능** 
  - 관리자모드(점주가입/탈퇴, 식당등록/삭제, 거래현황, 이벤트관리)
  - 점주모드(식당등록/삭제, 실적관리, 이벤트등록/삭제 , 메뉴등록/삭제/수정)
  - 사용자모드(장바구니기능, 메뉴검색에 따른 식당리스트확인, 식당에 따른 메뉴리스트 확인, 결제) 
- **역할**
  - HashTable 을 이용해 db 를 대체하여 식당에 대한 메뉴정보와 점주가 가지고 있는 식당정보를 저장하는 기능 구축
  - 거래내역을 구현하기 위해 sequence의 역할을 대체할 변수를 지정하여 거래내역을 담당하는 Hashtable에 등록될때마다 변수를 증가하게 하여 장바구니와 실적에 대한 시간적인 컨트롤 기능 구축
  - 프로젝트 총괄
<br/>
<image src='https://github.com/wjdrhkd456/Portfolio/blob/master/src/com/project/ssangyong/kiosk/images/hidden.png' width='400px' height='600px'/> <image src='https://github.com/wjdrhkd456/Portfolio/blob/master/src/com/project/ssangyong/kiosk/images/menu_select.png' width='400px' height='600px'/>
