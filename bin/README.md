
# LeagueOfLegend 전적 검색 서비스

## 개발 기간
* 2018.01 ~ 2018.04

## 개발 동기
* 자주 사용하는 서비스를 직접 구현하고 싶었음.

## 개발 목적
* 게임이 업데이트 될 떄마다 직접 공식 홈페이지에 접속해야 하는 불편함이 존재. 
* 분리되어 있는 커뮤니티와 서비스를 통합하기 위함.
## 개발 환경
* 언어 : Java
* Front : HTML, CSS, Bootstrap
* Back : Spring Boot, JavaScript & JQuery, myBatis
* DB : MySQL, MongoDB
* Server : Tomcat
* Build : Maven
## 기능
* 소환사 검색 ( 기본적인 소환사 정보 표기, 참여한 게임 정보, 선택한 챔피언 별 통계 )
* 전체 챔피언 별 통계 ( 승률 ) 
## DB Collection
* Champion : 게임 캐릭터 (업데이트 시 자동 갱신)
* Item : 게임 아이템 (업데이트 시 자동 갱신)
* Match : 단일 게임에 대한 모든 데이터
* Summoner : 등록된 게임 사용자 정보
* SummonerSpell : 게임 스킬(업데이트 시 자동 갱신)






