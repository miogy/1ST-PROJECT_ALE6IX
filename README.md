# < ALE6IX PROJECT >

## 1. 시연영상 전체보기

[![home](https://velog.velcdn.com/images/ch00ng10000/post/3ff906f7-d6ea-43a6-92f1-fc37b06e3eae/image.png)](https://youtu.be/X2f3YSx6h0Q)


## 2. 프로젝트 소개

- 해외 유명 디자이너 브랜드 ALESSI (http://alessi.co.kr) 를 클론 코딩 하였습니다.
- 프로젝트 내의 짧은 기간동안 세션 복습과 새로운 기능을 도전해 보고자 디자인은 클론코딩 하였고 기능을 구현하는 데에 중점을 두었습니다.
- 최대한 라이브러리를 지양하고 모든 기능을 스스로 학습하여 구현하는 것을 지향합니다. 
- 영상에서 보여지는 부분 모두 Fetch함수로 api를 이용하여 백엔드와 통신하여 작업하였습니다.

### 1) 프로젝트 선정이유

- E-commerce는 필요한 부분을 컴포넌트화하여 섹션을 나누거나 fetch를 이용하여 api통신으로 데이터를 주고 받는등
  지금까지 학습한 부분을 각자 맡은 페이지내에서 복습할 수 있고 새로운 기능을 추가로 학습할 수 있기에 선정하게 되었습니다.

### 2) 개발 인원 및 기간

- 개발기간 : 2022/8/29 ~ 2022/9/8
- 개발 인원 : 프론트엔드 4명, 백엔드 2명
- [Front-end-repo](https://github.com/wecode-bootcamp-korea/justcode-6-1st-ale6ix-front)
- [Back-end-repo](https://github.com/wecode-bootcamp-korea/justcode-6-1st-ale6ix-back)

### 3) 적용 기술

> - FE : React.js, sass, react-modal, react-dom, react-icons, react-paginate, react-router-dom

## 3. 담당기능

### 1) 전체 프로젝트 구현 기능

- 메인페이지 
- 제품 페이지 , 상세페이지 
- 로그인, 회원가입, 장바구니, 검색 페이지

### 2) 팀원과의 공동 작업

- [Main] : 메인 페이지 내에 섹션별 컴포넌트화 작업
- [상세 페이지] : 상세 페이지 내에 구매부분과 상품문의/후기 컴포넌트화 작업
- [Nav bar] : 레이아웃, 스타일링, mock-up데이터 카테고리 연결

### 3) 담당 기능

- [Main] 이미지 슬라이드 : next & prev버튼, Dot, 무한 슬라이드
- [Nav bar] : mock-up데이터를 이용하여 hover시 서브메뉴 UI구현
- [Main] Section : 신제품 및 추천 제품 섹션 별 제품 card 구현,
- [상세페이지] 상세페이지 내 상품 후기 : token을 이용하여 제품 구매 user일 경우 리뷰작성 또는 해당 user의 글을 삭제 (fetch함수와 POST & DELETE & GET메서드 이용),
- [상세페이지] 상세페이지 내 상품 문의 : fetch함수를 이용하여 POST메서드로 문의글 등록 및 DELETE메서드로 user의 token을 이용한 게시글 삭제, GET메서드를 이용하여 리스트구현

<br>
<hr>
<br>

## 3. 담당기능

### Main 

https://user-images.githubusercontent.com/99234582/190320114-96894487-8c1e-407b-8428-4b321ea5b69b.mp4

- Image Slider : mock-up이미지를 데이터형으로 작업하고 메인 슬라이드 내에 Next & Pre 버튼구현,
 <br> 해당 이미지경로 Dot생성 및 이동구현, setInterval을 사용한 무한 슬라이드

<br>


https://user-images.githubusercontent.com/99234582/190320314-a0c6337d-0434-4a65-b3d5-93e79ff98679.mp4

- 섹션 컴포넌트 : 신 제품, 추천 제품 fetch를 이용한 데이터 연결, React-router-dom을 사용하여 Link 이동

<br>
<hr>
<br>


#### 제품페이지


https://user-images.githubusercontent.com/99234582/190320736-bcacd1ed-c186-420d-9866-437b45f0df15.mp4

- 상품 문의 : api 호출하여 POST, GET, DELETE 구현. 

<br>


https://user-images.githubusercontent.com/99234582/190320711-3e057832-9f6e-4790-95fd-7efdeb908999.mp4

- 상품 후기 : api 호출하여 해당 제품을 구매한 유저의 토큰으로 POST, DELETE하고 재렌더링 GET 구현.

<br>
<hr>
<br>


### Nav bar


https://user-images.githubusercontent.com/99234582/190320661-f85c43c0-52d5-49db-b9bb-4cb38d528318.mp4

- mock-up데이터를 이용한 Nav menu구현

#### 그외

- Footer레이아웃 스타일링

<br>

## Reference

- 이 프로젝트는 [알레시](http://alessi.co.kr) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 모두 알레시 코리아의 동의하에 작업되었습니다.

# < ALE6IX PROJECT >
