# React JS로 영화 웹 서비스 만들기

## ※ 시작 전
    Node.js & npm 설치
    vscode 설치
    git 설치

    npm install npx -g 실행

1. react 프로젝트 생성
    npx create-react-app react-movie
    cd react-movie
    npm start

2. git 초기화
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/rebornist/react-movie.git
    git push -u origin main

3. react 에 전달된 props 타입의 오류 체크 패키지 설치
    npm i prop-types
    import PropTypes from "prop-types";

4. fetch를 대체한 axios 설치
    npm i axios
    import axios from "axios";