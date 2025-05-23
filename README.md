# React Twitter

* React와 Firebase를 활용한 **실시간 트위터 프로젝트**입니다.
* URL: [https://twitter-app-kappa.vercel.app/](https://twitter-app-kappa.vercel.app/)
* [Pull Request](https://github.com/gbs7536/twitter-app/pulls?q=is%3Apr+is%3Aclosed) 탭에서 기능별 코드 변경 내역을 확인할 수 있습니다.

<br />

# 프로젝트 개요

## 🎯 주요 기능

* 실시간 트윗 스트림 및 타임라인
* 트윗 작성, 편집, 삭제
* 이미지 업로드 기능 (Firebase Storage)
* 로그인/회원가입 및 OAuth 소셜 로그인 (Google, Github)
* 사용자 프로필 및 좋아요/작성한 글 모아보기
* 해시태그 생성 및 검색 기능
* 팔로우/언팔로우 기능
* 댓글 및 좋아요 기능
* 다국어 처리 (영어/한국어)

---

## ⚙️ 기술 스택

* **Frontend**: React, React Router, SCSS
* **상태관리**: Recoil, React Context API
* **Backend**: Firebase Auth, Firestore, Firebase Storage
* **배포**: Vercel (수동 배포)

---

## 🧱 앱 구조

* Create React App 기반의 SPA
* 반응형 웹 구현 (미디어 쿼리 적용)
* 컴포넌트 기반 구조: 레이아웃, 폼, 게시글 박스, 탭, 프로필 등

---

## 🛠 기타 구현/학습 내용

* 전역 상태관리 (Recoil) 및 다국어 처리
* 폴더 구조 설계 및 프로젝트 초기 세팅
* React Hooks 활용: `useEffect`, `useState`, `useContext`, `useCallback`
* 실시간 동기화(`onSnapshot`)를 이용한 Firestore 연동
* SCSS를 활용한 스타일링 및 모바일 대응

---

## 📌 구현 기능 상세

1. **홈 타임라인**

   * Firestore를 통한 실시간 트윗 표시
   * React 컴포넌트를 이용한 리스트 구성

2. **트윗 작성/편집 페이지**

   * 이미지 업로드 및 글 작성/수정/삭제
   * Firebase Storage와 연동

3. **회원가입 및 SNS 로그인**

   * 이메일/비밀번호 회원가입
   * Google, Github 로그인 (OAuth)

4. **프로필 페이지**

   * 유저 정보 및 작성 글, 좋아요 글 모아보기
   * 프로필 이미지 수정 기능 포함

5. **해시태그 기능**

   * 글 작성 시 해시태그 자동 생성
   * 해시태그 기반 필터링 및 검색 탭 제공

6. **기타 기능**

   * 댓글 작성/삭제
   * 좋아요 추가/제거
   * 팔로우/언팔로우 기능
   * 다국어 처리 (EN/KO)
   * 반응형 웹

---
