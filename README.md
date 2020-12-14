# CIY_Project_1 #

안녕하세요 모바일프로그래밍 과목 팀 1조 한종수, 이찬서의 프로젝트 리포지토리 입니다.

## 프로젝트 시연영상 유튜브 링크 ##
>## https://youtu.be/syh9ptsTTiw ##
>※ 접속되지 않으실 경우 시크릿 모드로 접속하시면 됩니다. 현재 유튜브 서버에 문제가 있는것 같습니다.
django_project 폴더에는 서버에 대한 핵심적인 파일들이 들어있습니다.

django_project.zip 폴더에는 서버에 대한 전체 파일들(설치된 패키지 파일 포함)이 들어있습니다.

CIY_Project_app 폴더에는 어플리케이션에 대한 전체파일들이 들어있습니다. API 23~29를 목표로 프로그래밍하여 그 외의 안드로이드 버전에서는 구동되지 않을 수 있습니다.

여건 상 서버를 24시간 가동시킬 수 없습니다. 때문에 안드로이드 어플리케이션은 설치는 가능하지만, 어플리케이션 실행 시 서버와 통신이 되지 않아 어플리케이션이 바로 종료될 수 있습니다.

### 파이썬 파일 위치 ###
>-뉴스 기사 크롤링 : /django_project/crawler/crawling/crolling.py
>
>-기사 정보 정형화 : /django_project/crawler/crawling/Make_DB.py
>
>-사용자 정보 업데이트 : /django_project/recommender/py/User_Update.py
>
>-유사도 계산 : /django_project/recommender/py/DB_similarity.py

### 데이터베이스 파일 위치 ###  
>-크롤링데이터 : /django_project/crawler/crawed(업로드 문제로 파일 삭제)
>
>-DB화데이터 : /django_project/recommender/py/articleDB
