# screening-clinic-covid19 (21/02/15 ~ 21/02/18)

Front-end : 코로나19 선별진료소 홈페이지 제작
 - (21-02-15) -> 선별진료소 메인페이지 중 nav, content, side 구현(부트스트랩 사용, 반응형 웹으로 제작)
 - (21-02-16) -> 사이트 파비콘 적용, 하이퍼링크 수정, footer 구현
 
Back-end : 심평원에서 제공하는 선별진료소, 국민안심병원 openAPI 웹 데이터를 수집해 클라이언트에 제공
 - (21-02-16) -> express 서버 구축 및 데이터베이스, 라우터 모듈화
 - (21-02-17) -> openAPI 웹 데이터 수집 및 DB에 저장(객체 형태로)
 - (21-02-18 오전) -> 검색에 따른 데이터 DB에서 조회 후 뷰 템플릿 엔진(ejs)을 이용해 화면에 표시하는 기능 추가
 - (21-02-18 오후) -> 검색항목을 선별진료소, 국민안심병원, 코로나 검사 실시기관 총 3가지로 분류 및 조회 추가


+ 추후 시간이 되면 위치기반 서비스 기능도 추가할 예정입니다.
