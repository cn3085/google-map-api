## Google Map API 가이드

 * API Key 발급 절차
      - Google Map Platform 접속 : https://cloud.google.com/maps-platform/
      - 새 프로젝트 만들기
      - 메뉴 > API 및 서비스 > 라이브러리 > Maps JavaScript API 추가, Places API 추가
      - 메뉴 > API 및 서비스 > 사용자 인증 정보 > 사용자 인증 정보 만들기 > 키 제한 > API 제한사항 > 제한사항 추가 > 저장

 * 기능 별 예제 코드
   - map.html : 맵 생성, 마커 생성, 설명창 생성
   - clear-marker.html : 마커 감추기, 보이기, 지우기
   - searching.html :  장소 검색
   - searching-with-paing.html : 주변 검색, 장소의 type, name 검색, 검색 결과 List 표시, 추가 검색(more)
   - index.html : type, name 검색, 지도 중앙 기준 검색 반경(Circle) 표시, 마커 클릭시 중앙 위치 변경, 모바일 환경 UI 변경
   - naver-map.html : Naver Map API 맵 생성, 마커 생성, 설명창 생성

* 참고
   - place Type : https://developers.google.com/places/web-service/supported_types?hl=ko
   - place Data Fields : https://developers.google.com/places/web-service/place-data-fields?hl=ko
