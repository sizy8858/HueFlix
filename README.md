# HueFlix

HueFlix는 Netflix 스타일의 영화 평점 및 추천 서비스를 제공하는 웹 애플리케이션입니다.

## 주요 기능

- 영화 검색 및 상세 정보 조회

- 영화 평가 및 리뷰 작성

- 영화 추천 및 top10

- 반응형으로 구현(태블릿,스마트폰)

- API를 사용한 최신 정보 업데이트


## 페이지 소개

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

### 회원 정보 수정
#### 정보 수정
![image](https://github.com/sizy8858/HueFlix/assets/148019068/1a270e92-84a9-44d3-b1b0-84f9cc9af546)

**마이페이지**

![image](https://github.com/sizy8858/HueFlix/assets/148019068/a899d65b-6766-45c7-a9e9-5aa382240b1c)

**비밀버호 입력**

![image](https://github.com/sizy8858/HueFlix/assets/148019068/6dce99be-522f-489e-862c-9a43c885d6d9)

**비밀번호 검사**

- 사용자의 정보를 수정 하기 전 비밀번호를 입력하는 페이지입니다.

- 잘못된 비밀번호를 입력하면 올바르지 않는다는 메시지를 띄웁니다.
#### 정보 수정

![image](https://github.com/sizy8858/HueFlix/assets/148019068/240063b0-cc3a-4ed7-ab50-fe0fb3e48e60)

**비밀번호 입력**

![image](https://github.com/sizy8858/HueFlix/assets/148019068/5873112a-9b5e-4824-9484-0465f01c08a6)

**비밀번호 유호성 검사**

- 닉네임,비밀번호를 변경 할 수 있는 페이지입니다.

- 유효하지 않은 비밀번호를 입력했을 경우 수정할 수 없도록 구현하였습니다.
## 메뉴
### 현재 상영작

![image](https://github.com/sizy8858/HueFlix/assets/148019068/25c39562-f5b0-47e5-90ed-5baad1f71dca)

- 출력되고 있는 영화는 TMDB의 API KEY를 통해 현재 상영 중인 영화 정보를 받아와서 표시합니다.

- 영화 포스터를 클릭하게 되면 영화 상세정보 페이지로 이동하게 됩니다. 
### 개봉 예정작

![image](https://github.com/sizy8858/HueFlix/assets/148019068/5784e329-54fd-4bfb-a58a-71c42b3db1ff)

- 출력되고 있는 영화는 TMDB의 API KEY를 통해 개봉 예정인 영화 정보를 받아와서 표시합니다.

- 영화 포스터를 클릭하게 되면 영화 상세정보 페이지로 이동하게 됩니다.

#### 게시판(일반 로그인 상태)

![image](https://github.com/sizy8858/HueFlix/assets/148019068/13dedc9c-f810-4f46-bf32-d6c72f0e5c30)

- 게시글 읽기와 키워드검색이 가능한 게시판입니다.

- 1페이지에 게시글이 10개가 출력되도록 구현했습니다. (페이지네이션)

#### 게시판(일반 사용자 읽기)

![image](https://github.com/sizy8858/HueFlix/assets/148019068/3af50332-d0b8-4144-a313-ded8978decb8)

- 게시판 일반 사용자는 게시판의 내용을 수정, 삭제 할 수 없도록 하였습니다.

- 목록보기 버튼을 누르면 게시판으로 이동하도록 하였습니다.  

#### 게시판(관리자 로그인 상태)

![image](https://github.com/sizy8858/HueFlix/assets/148019068/d13bbdd9-d4d6-4413-b2f9-2f9562b07070)

- 게시글 작성, 키워드검색이 가능한 게시판입니다.

- 제목을 누르면 해당 읽기페이지로 이동하게 하였습니다. 

#### 게시판(관리자 읽기)

![image](https://github.com/sizy8858/HueFlix/assets/148019068/d7de06b7-d779-4fdf-88b1-4289b5b49aea)

- 게시판 관리자는 수정, 삭제 권한을 부여하여 CRUD가 가능한 게시판입니다. 

- 목록보기 버튼을 누르면 게시판으로 이동하도록 하였습니다.  

### 주요 화면 기능
#### 영화 상세정보(줄거리)

![image](https://github.com/sizy8858/HueFlix/assets/148019068/fdc65b54-52c6-4140-bde1-82ba658101b1)

- 특정 영화의 아이디 값을 활용하여 API를 호출하며,이를 
     통해 해당 영화의 줄거리를 표시하는 페이지입니다.

#### 영화 상세정보(출연)

![image](https://github.com/sizy8858/HueFlix/assets/148019068/fff3e8b1-258d-4292-a917-761c9a7f58b8)

- 특정 영화의 아이디 값을 활용하여 API를 호출하며,이를 통해 해당 영화의 출연을 표시하는 페이지입니다.

#### 영화 상세정보(영상/포토)

![image](https://github.com/sizy8858/HueFlix/assets/148019068/99839ddc-efc7-451b-bfe7-3accd9bd0783)

- 특정 영화의 아이디 값을 활용하여 API를 호출하며, 이를 통해 해당 영화의 영상/포토를 표시하는 페이지입니다.

- 영화 포토/영상을 클릭하면 확대하여 볼 수 있도록 하였습니다.
 
#### 영화 상세정보(사용자 평점/댓글)

![image](https://github.com/sizy8858/HueFlix/assets/148019068/384a386b-00bd-4cb5-b1fa-fde241d0ff7c)

- 특정 영화의 아이디 값을 활용하여 API를 호출하며, 이를 통해 해당 영화의 사용자 평점/댓글을 표시하는 페이지입니다.

- 사용자가 댓글 작성시 별 모양 버튼을 클릭하여 평점을 추가하고 영화 관련된 내용을 평가할 수 있습니다.

#### 영화 상세정보(관리자 평점/댓글)

![image](https://github.com/sizy8858/HueFlix/assets/148019068/4a7df5a3-69eb-4ac6-83fc-42e371f4822a)

- 관리자 권한으로 일반 사용자의 댓글을 삭제 할 수 있습니다. 

#### 영화, 영화인 검색

![image](https://github.com/sizy8858/HueFlix/assets/148019068/a17a6be4-96a0-46f6-a0f8-7e6b3cc2962f)

- 검색창의 입력문자열을 검색 API를 통해 각 탭(전체, 영화, 영화인)에 출력하는 페이지입니다. 

- 검색 결과에 출력되는 영화 포스터를 클릭하게 되면 영화 상세정보 페이지로 이동하게 됩니다. 

## 개발 환경

    - Server : Apache-tomcat-9.0.0

    - Java EE : Eclipse (version 2023-06)

    - Database : Oracle SQL developer

    - Language : Java, Jsp, HTML, CSS, JavaScript, SQL, Spring Legacy, mybatis

    - Framework : Spring Tool suite 3.9.1
## 느낀점

## 느낀점

프로젝트를 통해 많은 것을 배우고 성장할 수 있는 기회를 얻었습니다. 주로 웹 개발과 관련된 기술들을 활용하면서 실무에서의 경험을 쌓을 수 있었습니다. 사용자 친화적인 UI/UX 설계와 구현, 백엔드에서의 데이터 관리, 그리고 협업에 대한 중요성을 몸소 느낄 수 있었습니다.

특히, 영화평점 사이트 프로젝트를 통해 팀원들과의 원활한 협업과 소통 능력을 향상시킬 수 있었습니다. 각자의 역할을 분명하게 정의하고 업무를 조율하는 과정에서 효과적인 팀워크가 이뤄지면서 프로젝트를 성공적으로 완료할 수 있었습니다.

어려움과 도전 속에서 문제에 대한 해결 능력을 키우고, 새로운 기술에 대한 지속적인 학습과 개선 노력을 통해 전반적인 역량을 향상시킬 수 있는 계기였습니다. 앞으로도 이러한 경험을 쌓아나가며 더 나은 웹 개발자로 성장해 나가겠습니다.


