# 데이터 엔지니어링 초급 3일차 - 데이터 변환 도구 스파크
> 아파치 스파크의 기본 명령어 및 API 를 주피터 노트북을 통해 실습하고 이해합니다

## 스파크 실습을 위해 도커 컨테이너를 기동하고, 노트북 페이지에 접속합니다
* logs 출력에 localhost:8888 페이지를 크롬 브라우저에서 오픈합니다
  - ***반드시 git pull 명령을 통해서 최신 데이터를 가져와야 합니다***
```bash
bash> cd ~/workspace/data-engineer-basic-training/day3
bash> git pull
bash> docker-compose up -d
bash> docker-compose ps
bash> docker-compose logs notebook
```

* 목차
  * 아래와 같이 한 장에 하나의 노트북을 생성합니다
    * 노트북을 열고 work 디렉토리로 이동합니다
    * "lgde-pyspark-tutorial-#.ipynb" 파일명으로 빈 노트북을 하나씩 생성합니다
  * 스파크 기본 명령어 이해
    * [1. 스파크 기본 명령어 이해](http://htmlpreview.github.io/?https://github.com/psyoblade/data-engineer-basic-training/blob/master/day3/notebooks/html/lgde-pyspark-tutorial-1.html)
    * [2. 기본 연산 다루기](http://htmlpreview.github.io/?https://github.com/psyoblade/data-engineer-basic-training/blob/master/day3/notebooks/html/lgde-pyspark-tutorial-2.html)
    * [3. 데이터 타입 다루기](http://htmlpreview.github.io/?https://github.com/psyoblade/data-engineer-basic-training/blob/master/day3/notebooks/html/lgde-pyspark-tutorial-3.html)
    * [4. 조인 연산 다루기](http://htmlpreview.github.io/?https://github.com/psyoblade/data-engineer-basic-training/blob/master/day3/notebooks/html/lgde-pyspark-tutorial-4.html)
    * [5. 집계 연산 다루기](http://htmlpreview.github.io/?https://github.com/psyoblade/data-engineer-basic-training/blob/master/day3/notebooks/html/lgde-pyspark-tutorial-5.html)
    * [6. 스파크 JDBC to MySQL](http://htmlpreview.github.io/?https://github.com/psyoblade/data-engineer-basic-training/blob/master/day3/notebooks/html/lgde-pyspark-tutorial-6.html)

### 모든 실습이 완료되었다면 컨테이너를 모두 종료합니다
```bash
bash> cd ~/workspace/data-engineer-basic-training/day3
bash> docker-compose down
```
