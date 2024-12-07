# 🖥 COMSULTANT

<div align="center">
    <img src="https://user-images.githubusercontent.com/63358647/204694792-5b7cd21f-7130-4a60-89e2-297facd9869c.JPG" width="30%"/>
</div>
<div align="center">
    <img src="https://user-images.githubusercontent.com/63358647/204694514-858aaa96-b9a4-4071-bd7b-306b73fc4815.JPG" width="60%"/>
</div>

## 0. 서비스 소개
- 소개 : 약 300만 건의 빅데이터 기반 조립 컴퓨터 견적 추천 플랫폼
- 의미 : 컴퓨터를 컨설턴트해주는 컴설턴트
- 타겟층
  1. 실제로 많은 사람들이 사용하는 컴퓨터를 사고 싶으신 분  
  2. 광고 제품을 피하고 싶으신 분  
  3. 시간이 없어 지금 바로 견적 추천을 받고 싶은신 분  
  4. 컴퓨터에 대한 지식이 부족하여 제품간 호환성을 확인할 수 없는 사람
- 차별점
  - 기존 타사이트
    - 운영자 혹은 판매자가 판매하는 조립 컴퓨터를 게시하거나 광고 제품을 올린다.  
    - 사용자는 자신의 조건에 맞춰 견적을 추천받기위해 견적 문의를 통해 답변을 기다려야 한다.  
  - COMSULTANT
    - `빅데이터 기반의 추천 서비스`로 실제 사용자들이 많이 이용하는 견적 스펙을 추천한다.
    - 버튼 클릭 하나만으로 대기시간없이 바로 추천을 받을 수 있다.
    - 제품간의 소켓 규격 등 `호환성 검사`를 자동화하여 실제로 사용할 수 있는 제품을 추천한다.

## 1. 개요
- 기간 : 2022.08 ~ 2022.10
- 소개 :
    - 로그인 및 회원 기능
    - 인기상품 및 견적 소개
    - 제품 조건별 검색
    - 제품 정보 상세보기 및 시세 그래프 확인
    - 나의 견적 생성 및 확인
    - 부품 호환성 검사
    - 견적 추천 받기 및 저장. 추천 결과 일부 수정 및 재추전
    - 나의 견적 불러오기 후, 나의 견적 기반 조건 추천 받기
    - 찜하기 및 댓글 기능
    - 나의 견적, 찜, 댓글 목록 확인
    - 견적 자료 이미지 저장

## 2. 팀 소개
### 역할 분담
| 팀원 | 고나령 | 김진회 | 신성은 | 유지태 | 윤주경 | 이예찬 |
| --- | --- | --- | --- | --- | --- | --- |
| 역할 | 팀장 / Back-end | Back-end / Front-end | Hadoop | Kafka / Back-end | Back-end / Front-end | Front-end |

### 담당파트
백엔드(JPA) [30%], 프론트(React) [10%], 데이터 수집 및 가공 [50%]
  - 백엔드
    - 제품 관련 API
    - 시세 관련 API
    - 찜 관련 API
  - 프론트
    - 마이페이지 회원정보 확인 및 수정
    - 나의 찜 목록 확인
    - 나의 댓글 목록 확인
    - 나의 견적 목록 확인
    - 상단 Nav바 애니메이션 
  - 데이터
    - 데이터 수집
    - 견적, 부품, 시세 데이터 RDBMS, NoSQL에 맞춰 데이터 가공 및 적재
## 3. 기술 스택🛠
| **Front-end** | **Back-end** | **Database** | **Distributed System** | **Infra** | **Crawling** |
| --- | --- | --- | --- | --- | --- |
| React 18.2.0 <br> JavaScript ES6+ <br> SCSS / HTML5 <br> Chrome/ Edge <br> Axios 0.27.2 <br> Node.js 16.16.0 <br> Npm 8.11.0 <br> Redux 4.2.0 <br> React Router Dom 6.3.0 <br> ESLint 8.20.0 <br> Webpack 5.74.0 <br> Ant Design 4.23.1 | JAVA 11 <br> Spring Boot 2.7.3 <br> Spring Security <br> Hibernate <br> JPA <br> Gradle 7.5 <br> JWT 0.9.1 <br> MapStruct 1.5.2 | Redis 7.0.4 <br> MongoDB 5.0.12 <br> MySQL | Hadoop 3.2.2 <br> HDFS <br> MapReduce <br> Zookeeper 3.6.3 <br> Kafka 3.2.0 | NginX <br> AWS EC2 Ubuntu 20.04 LTS <br> Docker 20.10.18 <br> Docker Compose 1.29.2 <br> Jenkins | Selenium <br> Scrapy |

## 4. 데이터 흐름

<img src="https://user-images.githubusercontent.com/63358647/204694519-542a9ef1-3b89-47a3-a771-1269b4d008e6.JPG" width="60%"/>


## 5. 서비스 아키텍처

<img src="https://user-images.githubusercontent.com/63358647/204694522-87bba3e0-ba11-4412-a443-a2c419065bec.png" width="70%"/>


## 6. 그 외 산출물
### 1) API 명세서
<img src="https://user-images.githubusercontent.com/63358647/204729050-33d5d6a1-cb10-4684-a44d-f15f22373c4a.JPG" width="60%"/>
<img src="https://user-images.githubusercontent.com/63358647/204729056-674b44f3-61ae-43f5-83af-309e7debedb6.JPG" width="60%"/>

### 2) Postman docs
<img src="https://user-images.githubusercontent.com/63358647/204729057-223f168d-8833-4523-a2c0-a4841593300c.JPG" width="60%"/>

### 3) ERD
<img src="https://user-images.githubusercontent.com/63358647/204729061-4cd5f267-7d21-41fb-ae3b-bab22db93e0b.png" width="60%"/>

### 4) WireFrame (Figma)
<img src="https://user-images.githubusercontent.com/63358647/204744653-d9fd086b-3dd2-4664-8758-7d30fe3e41b2.png" width="60%"/>

## 7. 시연 영상
[바로가기](https://www.youtube.com/watch?v=UzseH60O1V8)

## 8. 회고
### 기획: 주변 사용자에게 필요한 서비스
```
주변 사람들에게 필요한 서비스가 무엇인지를 고민하고 주제를 컴퓨터 견적 추천 플랫폼으로 정했다.
주변에 전공이 프로그래밍이지만 조립 컴퓨터에 대한 지식이 없는 사람들이 많았고, 이분들도 쉽게 컴퓨터 견적을 맞출 수 있다면 좋겠다는 생각에서 시작한 프로젝트였다.
실제로 주제를 발표했을 때, 많은 사람들에게 긍정적인 반응을 받았다. 또한, 실제 서비스를 시연했을 때 역시 긍정적인 피드백을 받을 수 있었다. 
```

### 데이터 수집 중 겪은 문제점: 일정 문제
```
다른 분산팀 중에서는 공개된 대량의 데이터를 먼저 확보하고 데이터에 맞춰서 주제를 정하는 팀들이 많았다.
아무래도 짧은 프로젝트 기간(6주)안에 데이터를 직접 확보하고 개발까지 끝내는 작업은 일정에 무리가 가기 때문이었다.
하지만 컴설턴트 팀은 주제를 먼저 정하고 데이터를 직접 확보하기로 했다.
다OO, 컴OO, 해외사이트 등에서 부품&견적&시세 데이터를 크롤링하거나 직접 수집하며 약 300만 건의 데이터를 확보했다.
하지만 여러 사이트에서 모은 자료들이다 보니 형식들이 전부 달랐고, 이를 우리의 DB에 저장하기 위해서는 데이터 가공 작업이 필요했다.
수집과 가공 총 작업은 약 2주~3주의 시간이 소요됐고, 그만큼 실제 개발 시간도 줄어들었고 일정이 촉박해지는 문제가 있었다.
```

### 대용량 데이터 가공 중 어려웠던 점: 다양한 형식의 데이터 예외처리
```
본인은 백엔드, 프론트 개발 외에 약 300만 건의 데이터를 POI 라이브러리와 csv형식을 이용하여 가공하는 작업을 했다.
POI는 엑셀 파일 형식 그대로를 이용하는 라이브러리로 초기에 엑셀 파일 형식이었던 자료를 쉽게 가공할 수 있었다.
데이터의 추출 부분의 특징을 파악하고 해당 특징에 따라 java 문자열 알고리즘으로 원하는 데이터를 뽑아 가공했다.
약 8차례에 거쳐 데이터 가공을 했고, 결국 원하는 형식의 데이터로 만들 수 있었다.
어려웠던 점은 특징을 파악해도 계속해서 발견되는 예외 데이터가 존재했고 그로 인해 다시 알고리즘 수정 과정을 반복해야했다.
ex. 같은 제품이지만 '삼성'&'samsung' 한영표기, 대소문자표기, 띄어쓰기 존재, 형식 순서 다름, 콤마 구분자, 없는 데이터 등
```

### NoSQL의 사용 및 장점
```
이전 프로젝트인 코게더에서는 사용하지 않았던 NoSQL를 사용했다.
빅데이터를 처리해야 하니 데이터 접근에 대한 속도 측면을 무시할 수 없었고, 이를 위해서 NoSQL을 사용했다.
JWT 토큰은 Redis에 담고, 약 270만 건의 시세데이터는 MongoDB에 담았다.
특히 시세데이터를 직접 몽고DB에 담고 관리하는 작업을 맡았는데 이 작업에서 몽고DB의 자유로운 형식 저장에 대한 편의성을 느낄 수 있었다.
저장 형식은 각 부품마다 컬렉션을 생성하고 해당 컬렉션에 부품들을 저장했다.
각 부품들은 부품id, 이름, date배열이 있고, date 배열에는 날짜와 가격이 매핑되어있다. 
{id, name, date[]{date, price}}

RDBMS와 다른 NoSQL의 특징과 장점을 느낄 수 있었던 경험이었다.
```

### React의 찍먹 후기와 느낀 Vue와의 차이점
```
프론트의 인원이 부족하다보니 프론트 경험이 있는 본인은 백엔드 개발이 끝나고 프론트 작업도 맡았다.
하지만 본인이 사용하던 Vue가 아닌 React였기 때문에 많은 부분을 담당하지는 못했고 MyPage만을 담당했다.
담당한 파트는 MyPage와 관련된 서비스를 확인하면 된다.
Comsultant/frontend/src/components/account/mypage,  Comsultant/frontend/src/services/

프론트 팀원의 코드를 참고하고 따로 공부를 하며 페이지를 구현했다.
다행히 전체적인 구성과 틀에 있어서는 Vue와 큰 차이는 없었고, 어렵지 않게 프론트 개발을 할 수 있었다.
개인적으로 코드의 구성이나 컴포넌트 분리, props와 같은 부분에서 React가 간단한 것을 느꼈고 왜 React가 인기가 많은지 이해할 수 있었다.
```

### JPA의 복잡한 쿼리 만들기(필터링): Specification vs QueryDSL
```
부품 조건 필터링에서는 수많은 and와 or이 존재하는 복잡한 필터링을 구현해야했다.
본인은 이 부분에서 Specification을 이용했다. 하지만 이것은 잘못된 선택이었다...
약간 복잡하다고 느끼는 쿼리에 있어서는 쉽게 구현할 수 있었지만 매우 복잡한 쿼리에 있어서는 오히려 작성하기 힘들었고, 유지보수(수정작업)가 매우 힘들었다.
나중에 김영한님의 JPA 강좌를 들으면서 깨달은 점은 Specification을 절대 사용하지말라! 쿼리DSL을 사용하라! 였다.

Specification을 이용해보고 직접 단점을 깨달을 수 있었고, QueryDSL을 학습해서 사용해야겠다고 느꼈다.
```
