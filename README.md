# HueFlix

HueFlix는 Netflix 스타일의 영화 평점 및 추천 서비스를 제공하는 웹 애플리케이션입니다.

## 주요 기능

- 영화 검색 및 상세 정보 조회

- 영화 평가 및 리뷰 작성

- 영화 추천 및 top10

- 반응형으로 구현(태블릿,스마트폰)

- API를 사용한 최신 정보 업데이트

## 페이지 소개
### 반응형 구현(태블릿,스마트폰)
![image](https://github.com/sizy8858/HRproject/assets/148019068/6fb7a377-3679-4889-902f-2c0fd82dc38b)

**태블릿 사이즈**

![image](https://github.com/sizy8858/HRproject/assets/148019068/9d630ab6-99f9-4b26-b2a2-1a72617b141b)

**스마트폰 사이즈**

### 메인 페이지
![image](https://github.com/sizy8858/HueFlix/assets/148019068/8c9ad5fa-3412-4d71-86ec-940546db1cc5)
- 영화가 슬라이드로 배치되어있는 페이지입니다.
- DB는 TMDB 사이트의 API입니다.

JavaScript의 Ajax 함수를 사용하여 TMDB API에 데이터를 요청해서 API에서 반환한 JSON 형식의 데이터를 받아와서 처리합니다.

### 회원가입, 로그인
![image](https://github.com/sizy8858/HRproject/assets/148019068/7f0717ce-3ead-48dd-aefc-d1ebf6cf6490)

**회원가입**

![image](https://github.com/sizy8858/HRproject/assets/148019068/2ca27024-caba-451e-a56b-8f20851c87c9)

**로그인**
- 사이트를 이용하기 위한 회원가입, 로그인 화면입니다.
- 회원가입은 유호성 검사를 거쳐 진행됩니다.
## 기술 스택

- Front-end: HTML, CSS, JavaScript, React
- Back-end: Node.js, Express
- 데이터베이스: MongoDB
- 기타: Axios (HTTP 통신), JWT (인증)
