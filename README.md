# Blog

링크 : [https://blog-b74e6.web.app](https://blog-b74e6.web.app)

## 기술 스택
1. React-router-dom : 라우팅
2. Firebase auth : 사용자 인증
3. Firebase Firestore : CRUD
4. BEM 구조 : css 스타일링
5. Firebase CLI : 배포

## 프로젝트 구조
```
src
├─ components : 공통 컴포넌트
│  ├─ Carousel.tsx : 이미지 슬라이드 관리
│  ├─ Comments.tsx : 댓글 관리
│  ├─ Footer.tsx : Footer 관리
│  ├─ Header.tsx : Header 관리
│  ├─ Loader.tsx : 로딩 화면 관리
│  ├─ LoginForm.tsx : 로그인 관리
│  ├─ PostDetail.tsx : 상세 계시글 관리
│  ├─ PostForm.tsx : 게시글 작성 관리
│  ├─ PostList.tsx : 게시글 리스트 관리
│  ├─ profile.tsx : 사용자 프로필 관리
│  ├─ Router.tsx : 라우팅 관리
│  └─ SignupForm.tsx : 회원가입 관리
├─ context : 사용자 인증, 다크모드 상태 관리
│  ├─ AuthContext.tsx : 사용자 인증 상태 관리
│  └─ ThemeContext.tsx : 다크모드 상태 관리
├─ pages
│  ├─ home.tsx : 메인 페이지
│  ├─ login.tsx : 로그인 페이지
│  ├─ posts
│  │  ├─ detail.tsx : 상세 계시글 페이지
│  │  ├─ edit.tsx : 게시글 수정 페이지
│  │  ├─ new.tsx : 개사글 작성 페이지
│  │  └─ posts.tsx : 게시글 리스트 페이
│  ├─ profile.tsx : 사용자 프로필 페이지
│  └─ signup.tsx : 회원가입 페이지
├─ App.tsx : Contexts 설정
├─ index.tsx : 메인 페이지
├─ index.css : BEM 구조의 디자인
└─ firebaseApp.tsx : Firebase 설정
```
