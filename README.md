# Spharos-Study
스파로스 아카데미에서 배운것들 기록
2022-7-19 카카오 협업 툴 특강
svn vs git
- local remote 차이

version control
* baseline
-소스파일이 시작되는 시작 지점
* revision
-특정 시점
* branch
-독립적

* commit
-local에만 
* merge
-병합
* conflict
-충돌

GIT FLOW
DEVELOP(baseline)
-Feature(신규, 기능 개발만) > merge > Release
-Release(배포, 개발 완료, only one)
MASTER(baseline)
-Hotfix (error발생시)

GIt/Westagram Guide

Massaging
-slack(공지알림,전파장애)
Whiteboard
-miro(API, 실시간 설계 용이)
Document Sharing
-Jira
Project Manager
-Jira

Event + Brain Storming -> Event Storming
화이트보드에 포스트잇 붙힘( 회의를 통해 반복)
똑같은 프로젝트를 진행해도 서로간의 이해 차이 이슈를 줄여줌
-Domain Event (pp,orange)
-Command (도메인 수행하기 위한 행동,동작,blue)
-Read Model (행위를 위한 데이터,green)
-Policy (정책,조건,pupple)
-Actor (행위자,pink)
-Aggregate (서로 연결된 하나의 집합체,그룹핑,yellow)
-External System (외부시스템,red)

arrow
orange-> blue-> red -> pink -> green -> pupple -> yellow


* 도서 관리 시스템 설계하기 *

