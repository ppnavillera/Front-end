헤더에 있는 로고 눌렀을 때 홈 화면으로 리다이렉팅하면서 기존에 검색하던 정보 초기화되면 좋을거 같음.

헤더 창의 경우에만 absoulte로 해서 올리고, 나머지는 네이버지도의 overlay를 이용해서 지도에 올려야 할듯?
https://d2.naver.com/helloworld/3380225

해야할 것.
1. 지도 줌 컨트롤 네이버 지도 내장된 것 쓸지 아니면 따로 구성할지. 
    - 만약 쓴다면 css 및 상태 업데이트 등 수정해야함.
2. 지도에 비건 식당 표시해주는거는 마커 수정해서 쓰면 될듯? 인터넷에 예제 있음
3. 검색해서 나타내는 것 구현 필요

마커 = 화면에 송송 표시되는 것들
정보창 - 간단한 정보 패널

만약에 식당 유형이 명시적으로 표시되는게 아니라 카테고리로 분류되서 데이터가 넘겨진다면 탐색해서 해당하는 카테고리를 반환한다.