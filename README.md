# airbnb 메인화면 클론코딩
> HTML, CSS 기초 지식 공부한 것을 기반으로 혼자서 구현해본 airbnb 메인화면 클론코딩 프로젝트 


## 프로젝트 구성
- HTML, CSS

## 사용 예제
### 화면 너비 1760px 이상
![ezgif com-gif-maker](https://user-images.githubusercontent.com/77538818/148766497-0697c703-f2b8-4689-a527-1b144b99fe5b.gif)

### 화면 너비 744px 이상
![airbnb-800px](https://user-images.githubusercontent.com/77538818/148768087-1360bc71-15eb-4f39-a060-44ad3d4cb118.gif)

### 모바일 화면
![airbnb-mobile](https://user-images.githubusercontent.com/77538818/148768148-c505f6a3-8cbd-495f-b676-3bf7ef9de828.gif)

## 배운 점
- [::before, ::after 가상요소 - 메뉴 구분선 활용](https://github.com/raccoon-ccoder/TIL/blob/main/HTML%2C%20CSS/::before%2C%20::after_%EA%B0%80%EC%83%81%EC%9A%94%EC%86%8C_%EB%A9%94%EB%89%B4%20%EA%B5%AC%EB%B6%84%EC%84%A0%20%ED%99%9C%EC%9A%A9.md)
- [font gradient - 텍스트 그라데이션 효과](https://github.com/raccoon-ccoder/TIL/blob/main/HTML%2C%20CSS/font%20gradient_%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EA%B7%B8%EB%9D%BC%EB%8D%B0%EC%9D%B4%EC%85%98%20%ED%9A%A8%EA%B3%BC.md)
- [box-shadow - 그림자 효과](https://github.com/raccoon-ccoder/TIL/blob/main/HTML%2C%20CSS/box-shadow_%EA%B7%B8%EB%A6%BC%EC%9E%90%20%ED%9A%A8%EA%B3%BC.md)
- [box-sizing - padding 설정시 width 변하는 문제](https://github.com/raccoon-ccoder/TIL/blob/main/HTML%2C%20CSS/box-sizing_padding%20%EC%84%A4%EC%A0%95%EC%8B%9C%20width%20%EB%B3%80%ED%95%98%EB%8A%94%20%EB%AC%B8%EC%A0%9C.md)
- [img의 srcset, sizes - 반응형 이미지](https://github.com/raccoon-ccoder/TIL/blob/main/HTML%2C%20CSS/img%EC%9D%98%20srcset%EA%B3%BC%20sizes_%EB%B0%98%EC%9D%91%ED%98%95%20%EC%9D%B4%EB%AF%B8%EC%A7%80.md)
- [justify-content : space-* 차이잠](https://github.com/raccoon-ccoder/TIL/blob/main/HTML%2C%20CSS/justify-content%EC%9D%98%20space-between%2C%20space-around%2C%20space-evenly%20%EC%B0%A8%EC%9D%B4.md)
- [object-fit, object-position - CSS 이미지 조정](https://github.com/raccoon-ccoder/TIL/blob/main/HTML%2C%20CSS/object-fit%2C%20object-position_CSS%20%EC%9D%B4%EB%AF%B8%EC%A7%80%20%EC%82%AC%EC%9D%B4%EC%A6%88%20%EC%A1%B0%EC%A0%95.md)
- [text-align 속성 정렬시 주의점](https://github.com/raccoon-ccoder/TIL/blob/main/HTML%2C%20CSS/text-align%20%EC%86%8D%EC%84%B1%EC%9C%BC%EB%A1%9C%20%EC%A0%95%EB%A0%AC%ED%95%A0%20%EB%95%8C%20%EC%A3%BC%EC%9D%98.md)
- [word-break - 텍스트 줄바꿈 CSS](https://github.com/raccoon-ccoder/TIL/blob/main/HTML%2C%20CSS/word-break_%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EC%A4%84%EB%B0%94%EA%BF%88%20CSS.md)
- [반응형 CSS 단위](https://github.com/raccoon-ccoder/TIL/blob/main/HTML%2C%20CSS/%EB%B0%98%EC%9D%91%ED%98%95%20CSS%20%EB%8B%A8%EC%9C%84%20%EC%A0%95%EB%A6%AC.md)

## 느낀 점
- 공통으로 사용되는 요소들은 컴포넌트 css를 따로 만들어서 사용하는 것이 편리하며 재사용성이 높아져서 좋다.
- 모바일 화면까지 고려해서 레이아웃을 신경써서 짜야 나중에 덜 고생하며 레이아웃 짜는 방법에 대해 더 공부해야겠다.
- 반응형 웹 CSS는 미디어 쿼리로 작성했는데 코드가 더 지저분해지는 느낌이었다. 모바일에 최적화로 CSS를 짰다고 했지만 웹에서 모바일 화면으로 볼 때와 실제 모바일 기기에서 볼 때는 차이가 많았다(특히 글씨체 부분). 모바일 기기도 화면 너비가 다 다르기에 그에 맞게 px가 아닌 em이나 rem을 써야 하는 건지 방법을 잘 몰라서 관련 부분은 따로 공부해야겠다. 아니면 모바일을 위한 CSS 짜는 방법이 있는데 잘 모르는 건지...

### 보완할 점
- js 공부 후 스크롤할 때 header 바뀌는 효과
- 개인정보 보호 확인 버튼 클릭시 jquery 이용해서 fadeIn, fadeOut 효과 추가


