# 배포 링크
 https://thdtmdrud.github.io/portfolio.github.io/index.html

# 2주차 학습 

## font-weight more than 900
> color: black;    
  text-shadow: 2px 0 black;
  letter-spacing: 2px;
  font-weight: bold;

## sr-only
- sr-only 클래스를 활용하여 screen에는 보이지 않지만 screen readers는 볼 수 있도록 할 수 있다.
> .sr-only {
    clip: rect(1px, 1px, 1px, 1px);
    clip-path: inset(50%);
    height: 1px;
    width: 1px;
    margin: -1px;
    overflow: hidden;
    padding: 0;
    position: absolute;
  }

## BEM 방법론
- BEM 방법론을 활용하여 CSS 코드를 단순하고 이해하기 쉬운 견고한 구조로 작성할 수 있다.
- block--modifier-value구문을 사용한다.

## scroll
- scroll의 기능은 살리고 screen에 보이지 않도록 하는 코드이다.
> body{
    -ms-overflow-style: none;
   }\
  ::-webkit-scrollbar {
     display: none;
   }

## Font 적용 방법
> <link href="https://fonts.google.com/" rel="style.css">\
   style{
    font-family: "Roboto", sans-serif;
   }
