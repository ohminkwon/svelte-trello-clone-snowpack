[![Netlify Status](https://api.netlify.com/api/v1/badges/4c8ac2c5-3b3d-47b6-8713-eb98c59d7903/deploy-status)](https://app.netlify.com/sites/cloning-trello-snowpack-ohminkwon/deploys)

# Svelte Trello clone app with Snowpack

[Rollup 기반의 Trello 클론 프로젝트](https://github.com/ohminkwon/svelte-trello-clone-rollup)를 Snowpack으로 리팩토링한 프로젝트입니다.<br>

![demo gif](./src/images/svelte-trello-example.gif)

<u>**[DEMO](https://cloning-trello-snowpack-ohminkwon.netlify.app)**</u>

## 기본 패키지

- svelte: SvelteJS 핵심 패키지입니다.
- snowpack: 프로젝트를 빌드를 위한 핵심 패키지입니다
- @snowpack/plugin-svelte: Svelte 싱글 파일 컴포넌트(SFC)를 컴파일합니다.
- @snowpack/plugin-dotenv: 프로젝트에 사용될 환경 변수를 불러옵니다.
- @snowpack/plugin-optimize: 난독화, 간결화와 빌드 최적화를 위한 패키지입니다.

## 추가 패키지

- @snowpack/plugin-babel: ES6 이전 버전 호환을 위한 패키지입니다.
- babel-plugin-transform-remove-console: 개발모드가 아닐 때, console 명령을 제거하는 패키지 입니다.
- @snowpack/plugin-sass: scss를 적용하기 위한 패키지입니다.
- autoprefixer: CSS에 자동으로 공급 업체 접두사(Vendor prefix)를 적용합니다.(9버전을 사용하면 내부에서 postcss를 설치합니다, 10버전 이상은 postcss를 별도 설치해야 합니다)
- postcss: CSS 전처리기로 CSS작성을 편하게 만들어주는 플러그인 패키지입니다.
- sortablejs: Drag and Drop으로 목록을 쉽게 정렬할 수 있습니다.
- lodash: 다양한 유틸리티 기능을 제공하는 자바스크립트 라이브러리입니다.
- uuid: crypto-random-string 대체로 고유한 랜덤 문자열을 생성합니다.

## Reference
[Svelte.js Core API 완벽 가이드](https://inf.run/bXbH)