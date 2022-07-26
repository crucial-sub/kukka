<h1 align="center"> 꾸까 클론 과제 </h1>

<h3 align="center"> 서비스 링크: https://console-lo9-kukka.netlify.app/ </h3>

<p align="center"><img width="500" src="https://bit.ly/3HbbMA8" /></p>

<br/>

## 👏 프로젝트 소개

> 리액트없이 바닐라 자바스크립트로 꾸까(https://kukka.kr/) 웹 페이지를 구현하는 과제로 <br/>
> 크로스 브라우징에 대한 고민을 바탕으로 제작한 프로젝트입니다.

<br/>



## 🚀 스택

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/Jquery-0769AD?style=flat-square&logo=jquery&logoColor=white">
<img src="https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=sass&logoColor=white">

<br/>

## ⚠️ 규칙

- CSS class명은 [BEM 네이밍 규칙](https://padak-padak.tistory.com/entry/CSS-Naming-Conventions-%EB%84%A4%EC%9D%B4%EB%B0%8D-%EA%B7%9C%EC%B9%99)을 준수한다

- Git Team Ground Rule - Git Flow, 모든 팀원이 체크 후 마지막으로 체크한 팀원이 머지한다.

<br/>

## ✨ 구현 사항

> **`맡은 역할`** <br>
> GNB, 플라워클래스 태그 기능 구현

사용 기술

- [x] Vanilla JS 사용
- [x] jQuery 사용 가능
- [x] 반응형

GNB

- [x] 스크롤 이동 시 상단 고정
- [x] 메뉴 hover 시 글자 하단에 밑줄
  - text-decoration 사용 금지
- [x] GNB 하단 영역에 그림자 효과 - (z-index)
- [x] 메뉴 아이템 두 가지: 동영상, 플라워클래스
- [x] 클릭 시 해당 영역으로 스크롤 이동
- [x] 애니메이션 효과 적용
  - scroll-behavior: smooth 사용 금지

동영상

- [x] iFrame 사용하여 Youtube 영역 구현
- [x] 캡션 삽입 & 동영상 제목 클릭 시 링크 이동

플라워클래스

- [x] 이미지 hover 시 줌 효과
- [x] 화살표 버튼 클릭 시 1, 2, 3 이미지 돌아가며 교체

배너 영역

- [x] Bootstrap4 사용해 두 개의 다른 영역 레이아웃 구성
- [x] 이미지 위에 단색 그라데이션
- [x] hover 시 이미지 확대
- [x] 배너 내부 반응형

푸터 영역

- [x] css로 레이아웃 구현 (IE8)
- [x] SNS 아이콘 클릭 시 링크 이동

팝업

- [x] 들어가면 팝업 이미지를 띄움
- [x] 클릭하면 외부 사이트로 이동

## 🗺 구현 Preivew

1. GNB

<img width="400" src="https://user-images.githubusercontent.com/87363422/181026941-ccde1e40-dca5-4d03-b1fd-9b5f62fd26e9.gif" />

2. 플라워클래스 태그 기능 구현

<img width="400" src="https://user-images.githubusercontent.com/87363422/181026983-f1845623-f332-425a-8a05-271f9228eee3.gif" />

## 🗒 프로젝트 진행 과정 및 구현 사항

> [위키 링크](https://github.com/console-lo9/kukka/wiki/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%A7%84%ED%96%89-%EA%B3%BC%EC%A0%95%EA%B3%BC-%EA%B3%A0%EB%AF%BC)

<br/>

## ⚙ 설치

```
# clone the project
$ git clone https://github.com/console-lo9/kukka.git

# install modules
$ cd kukka
$ npm install || yarn

# start with live server

⠀
⠀  You can now view this project in the browser.
⠀  http://localhost:5500/
⠀
```

## 🔗 의존성

```
  "dependencies": {
    "babel-loader": "^8.2.3",
    "node-sass": "^7.0.1",
    "vanilla-framework": "^3.1.0",
    "webpack": "^5.69.1",
    "webpack-cli": "^4.9.2"
  },
```

## 📂 파일 구조

        ├── public
        │   └── scripts
        └── src
            ├── assets
            ├── components
            └── styles
