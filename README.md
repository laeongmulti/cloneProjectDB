# Project Pages<br>
Front: [cloneProjectFront](https://github.com/laeongmulti/cloneProjectFront)<br>
Back: [cloneProjectBackBoot](https://github.com/laeongmulti/cloneProjectBackBoot)<br>
DB: [cloneProjectDB](https://github.com/laeongmulti/cloneProjectDB)<br>

# DB 설치 방법<br>

**소개**<br>
해당 DB는 Mysql 기반의 DB 생성 및 PhpMyAdmin은 실행.<br>
Mysql Version: 8.0<br>
DB port:3306<br>
PhpMyAdmin port: 8081<br>

**설치방법**<br>
인터넷에서 Docker Desktop 필수 설치<br>

터미널
````bash
docker-compose up -d
````

설치시 localhost:3306 과 localhost:8081 에서 확인 가능<br>

Docker의 좌측 메뉴 Images 에서 껏다켰다 가능<br>

프로젝트의 BackEnd 실행시 DB서버가 없는경우 서버가 죽으니 먼저 실행해두는것을 권장함<br>

**DB툴**<br>
편한거 사용하면 됨<br>
다만 DB가 익숙치 않을경우 PhpMyAdmin 이 초기 UI가 좋아서 이해를 돕는데 도움을 줄 수 있을거라 생각함.<br>
물론 이건 구시대적인 툴이기 때문에 다른 프로젝트에서 사용하는건 비추<br>

**Git 사용 방법**<br>
본인이 db를 수정하면 [내보내기]를 하여 sql 파일 안에 db.sql 형식으로 파일을 만들고 git 에 올리면 됨.<br>
좀 귀찮긴 해서 다른 방법도 물색중<br>