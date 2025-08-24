# 매일국어 웹퍼블리셔 테스트 과제 설명문서

> 선택과제 1번 독도 메인 화면 구현 코드입니다. 완성된 화면은 [링크](https://seraleedev.github.io/maeil-publishing-test/)에서 확인 가능합니다.
> 코드샌드박스 링크 : https://codesandbox.io/p/github/seraleedev/maeil-publishing-test/draft/gallant-albattani
> 사용기술 : HTML, SCSS

## 폴더 구조

```
📜index.html
📦img
📦css
 ┣ 📜style.css
 ┗ 📜style.css.map
📦scss
 ┣ 📂base
 ┃ ┣ 📜_global.scss
 ┃ ┗ 📜_reset.scss
 ┣ 📂components
 ┃ ┣ 📜_article.scss
 ┃ ┣ 📜_aside.scss
 ┃ ┣ 📜_footer.scss
 ┃ ┣ 📜_nav.scss
 ┃ ┗ 📜_section.scss
 ┣ 📂utils
 ┃ ┣ 📜_mixins.scss
 ┃ ┗ 📜_variables.scss
 ┗ 📜style.scss
```

## 폴더별 설명

| 폴더명         | 폴더 설명                              |
| -------------- | -------------------------------------- |
| scss/base      | 스타일 리셋 및 기본 설정이 적용된 파일 |
| src/components | 컴포넌트 별 스타일링 파일              |
| src/utils      | 공통적으로 쓰이는 변수나 믹스인 파일   |


