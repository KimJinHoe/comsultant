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

## 7. 시연 영상
[바로가기](https://www.youtube.com/watch?v=UzseH60O1V8)

## 8. 회고
