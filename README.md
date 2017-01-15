# BOAZ-bigdata-conference-5th

* 행사명 : 제5회 BOAZ 빅데이터 컨퍼런스
* 일시 : 2017년 1월 15일 일요일 오후1시~오후5시
* 장소 : 서울시청 서소문별관 후생동 강당 4층

## link

* onoffmix
    - [http://m.onoffmix.com/event/87603/content](http://m.onoffmix.com/event/87603/content)
* BOAZ
    - link
        + blog
            * [http://m.blog.naver.com/boazbigdata/220901135659](http://m.blog.naver.com/boazbigdata/220901135659)
        + facebook
            * [https://ko-kr.facebook.com/BOAZbigdata/](https://ko-kr.facebook.com/BOAZbigdata/)
        + slideshare
            * [http://www.slideshare.net/BOAZbigdata/presentations](http://www.slideshare.net/BOAZbigdata/presentations)
        + youtube
            * [https://www.youtube.com/channel/UCSniI26A56n2QZ71opJtTUg](https://www.youtube.com/channel/UCSniI26A56n2QZ71opJtTUg)

## index

* 축사 (이원석 교수님)
* 서울특별시 빅데이터 캠퍼스
* 팀발표1 : Webtoonism 팀
* 팀발표2 : 서울홀로서기 팀
* 팀발표3 : 대서울여지도 팀
* 팀발표4 : 스벅옆이디야 팀
* 팀발표5 : IRECIPE BOT 팀
* 강연 (김규호 교수님)

## content

* 축사 (이원석 교수님)
    - trend
        + IBM Watson
            * [https://www.ibm.com/watson/](https://www.ibm.com/watson/)
        + 의료
        + 산업화
        + 4차 혁명
            * 제로섬의 범위는 global
* 서울특별시 빅데이터 캠퍼스
    - 2016.07 ~
    - [https://bigdata.seoul.go.kr](https://bigdata.seoul.go.kr)
    - 폐쇄적
        + 입주/분석/퇴소
            * 데이터 반출 주의
    - 파트너십
        + 민간
        + 공모전
    - 데이터셋
        + 카드 매출
        + 유동인구
        + 민간 구입 데이터
* 팀발표
    - 웹툰의 OSMU 가능성 예측을 위한 통계적 모델링
    - 서울에 거주하는 20~30대 나홀로족을 위한 라이프 가이드
    - 서울시내 간선도로 교통량을 활용한 주요지점 간 이동시간 시각화
    - 폐업률을 기준으로 한 서울시 강남구의 창업입점 생존률 분석
    - 워드임베딩과 인공신경망을 이용한 개인 맞춤형 레시피 추천
* 강연 (김규호 교수님)

---

```
* 팀발표1. Webtoonism 팀  [조규원, 이신원, 이하영, 최기준]
* 주제 : 웹툰의 OSMU 가능성 예측을 위한 통계적 모델링
* 내용 : 웹툰시장에서 활발히 이루어지고 있는 OSMU(One Source Multi Use)에 대해서 다양한 통계적 기법을 통해 모델링해보고, 현재 미완결 웹툰 중 OSMU 가능성이 높은 웹툰 예측
```

* 데이터 수집
    - 웹 크롤링
        + 수집 완료 항목
        + 수집 불가 항목
            * 조회수, 이용자 정보, 연재 요일(완), 크롤링 시점 이후 변화
* 데이터 전처리
    - RGB 값 추출
        + K-means clustering
            * 상위컬러 6색 추출
        + ...
* 모델링
    - 변수 선정
    - 결과 값 비교
    - 최종 모델 선택(BOOSTING)
* QA
    - 데이터수집 기간
        + ? ~ 2016.12.20
    - 감성1, 색상을 변수에 추가한 이유는?

---

```
* 팀발표2. 서울홀로서기 팀  [김승효, 김재은, 박다혜]
* 주제 : 서울에 거주하는 20~30대 나홀로족을 위한 라이프 가이드
* 내용 : 데이터 시각화를 통해 살펴보는 서울의 20-30대 나홀로족의 식(食), 주(住) 라이프 트렌드북. 차트와 시각화를 통한 현황제시를 통해 독자들의 선택의 폭을 넓혀준다. 
```

* 웹 서비스 제공
    - ...
    - [http://singlelife.creatorlink.net/](http://singlelife.creatorlink.net/)
    - web
        + creatorlink
* R
    - _
    - ggplot2
    - illustrator
* ...
* 주
    - 국토교통부 실거래가
        + 데이터 가공
            * 면적
                - to 평수
    - ...
* 식
    - ...
* 데이터 상관 관계
    - 카페 수 & 집값
* 시각화
    - 막대 그래프
    - 파이 차트
    - 라인차트
    - 히트맵
    - 워드 클라우드
    - 트리맵
* QA
    - 데이터 수집
    - 트리맵?
        + like 파이 차트
    - critic
        + raw 데이터 시각화 결과물만 있는 것인가?
    - 흑백 색상 선택 이유

---

```
* 팀발표3. 대서울여지도 팀  [조수민, 박슬기]
* 주제 : 서울시내 간선도로 교통량을 활용한 주요지점 간 이동시간 시각화
* 내용 : 서울시 주요도로의 교통량을 기반으로 지점 간 시간거리를 지도로 시각화한다. 또한, 시점이나 장소별로 상이한 교통상황을 보조자료로 제공하여
서울시 교통흐름을 한 눈에 파악한다.
```

- ...
- cartogram
    + (단점) 수치 미제공
- 서울시 공공데이터 Open API
    + 145개소
    + 도로를 지나가는 이동 차량 수
    + 25만건
    + 데이터 가공
        * 이동 차량 수 / lane
- 측정 되지 않은 지역 추정
    + kriging interpolation(크리깅 보간법)
    + sill
    + 람다 벡터 추정
- ...
- 시각화
    + ....
    + 열지도
- 리플렛
    + M자형
- QA
    + _ 
    + 요일별, 휴일별 교통량에 대한 고려는?
    + 카토그램
        * 도로는 선으로 표현되고 지역은 면적으로 나타나 확인이 어려운데? 다른 방법은 없었는지?
        * line cartogram
    + 방향에 대한 고려는?

---

```
* 팀발표4. 스벅옆이디야 팀  [김상엽, 김동환, 임재성, 전현우]
* 주제 : 폐업률을 기준으로 한 서울시 강남구의 창업입점 생존률 분석
* 내용 : 상권 데이터를 분석해 새로 들어서는 점포에게 장기간 생존가능한 입지를 추천한다. 콕스 비례 위험 모형, R-shiny 등을 활용하여 서울시 강남구를 집중적으로 조명하여, 강남구 내 음식점 종류별 장기간 생존 지역, 혹은 강남구 내 지경별 장기간 생존 음식점 종류를 추천해준다.
```

* 순서
    - 주제선정
    - 데이터 수집
    - 시각화
    - 분석
    - 결론
* 서울 열린 데이터 광장
    - 상권 프로파일링 정보
* 데이터 정제
    - 카테고리
* 데이터 분석
    - 생존 함수
    - 단점 보완
    - _
* 결론 도출
    - 업종별 전략적 접근
    - 의 외 부분
        + 치킨, 중식...
    - 서울특별시 상권분석 서비스
        + [http://golmok.seoul.go.kr/](http://golmok.seoul.go.kr/)
    - 폐업률 60개월 일 때 증가 이유
        + 임대료 상승으로 인한 폐업 증가로 추정

---

```
* 팀발표5. IRECIPE BOT 팀  [김성동, 김수연, 노우영, 박소영, 박소현, 이지원]
* 주제 : 워드임베딩과 인공신경망을 이용한 개인 맞춤형 레시피 추천
* 내용 : 추천 시스템의 Cold start Problem에 대처하기 위해, 대량의 레시피 텍스트로부터 각 레시피의 특징을 추출하고 를 인공신경망에 매핑하여 복잡미묘한 입맛의 선호를 예측, 봇 인터페이스를 통해 피드백을 받는 Online learning 형태의 추천 시스템 제안
```

* 인공신경망
* 추천시스템
* 유사 서비스
    - CJ The Kitchen
    - 레시피 몬스터
* 추천 알고리즘
    - 협업 필터링
        + 유사도 계산(rating matrix)
        + [https://ko.wikipedia.org/wiki/%ED%98%91%EC%97%85_%ED%95%84%ED%84%B0%EB%A7%81](https://ko.wikipedia.org/wiki/%ED%98%91%EC%97%85_%ED%95%84%ED%84%B0%EB%A7%81)
    - cold start
* 아키텍처
    - ...
    - feature extraction
        + 레시피 특징 추출
        + word2vec
    - scoring
        + neural network
        + 조건부 확률
* 크롤링
    - 파이썬 셀레니옴
    - to 만개의 레시피
    - 20만개
* data
    - 메타 데이터
    - and 데이터 연관 관계가 세부속성으로 들어있음
* _
    - pos tagging
* ...
* recommendation
* ramdomness
    - 유저 취향 탐색
* 추천과 검색 문제 해결 제시
    - wide and deep learning for search engine
        + google play store
    - 추상화와 필터링
* QA
    - word2vec vs doc2vec
    - ...
    - serendipity

---

```
* 연사 초청 강연 : 서강대학교 소프트웨어교육센터 김규호 교수님
* 주제 : 빅데이터? 내 주변의 "생활 데이터" ?
* 내용 : 4차 산업혁명, 인공지능, Intellectual Explosion, Singularity
Point 등 무언가 가만 있으면 뒤쳐지는 것 같아서 무언가 해야할 것 같은 스트레스를 받지만 어떻게 해야할지 막연한 키워드들이 있습니다. 2015년 1월 지역 난방 아파트 거주자로서 겨울에 컴퓨터가 있는 방이 춥다는 문제의 해결을 위해 시작한 작은 "생활IoT" 프로젝트를 계기로 메이커 커뮤니티, 스타트업 커뮤니티에 참여하면서 겪은 것들을 바탕으로 위의 키워드들을 해석해보고 이 와중에 나는 무엇을 하면 좋을까에 대해 생각의 거리를 제공해보고자 합니다.
```

* 난방 코딩
    - [http://www.bloter.net/archives/220360](http://www.bloter.net/archives/220360)
    - [http://www.slideshare.net/KyuhoKim/20150122-valve-god](http://www.slideshare.net/KyuhoKim/20150122-valve-god)
    - [http://www.slideshare.net/KyuhoKim/presentations](http://www.slideshare.net/KyuhoKim/presentations)
* 데이터 수집 중요성

