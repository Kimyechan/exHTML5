# Front-End

## HTML

- DOM TREE

    html

    head                      body

    meta title link       div.wrapper

              text              header

- 중요 사항

    논리적인 순서

    시맨틱 마크업

    네이밍

    구조 설계

- 3단 구조 - 헤더(내비게이션 포함) 컨텐츠 푸터
- 4단 구조 - 헤더 내비게이션 컨텐츠 푸터

- div 사용 시기 : 서로 다른 content를 묶어 줄 때
- html naming
    - class
    - id - 고유 식별

## CSS

ref : [https://css-tricks.com/](https://css-tricks.com/)

- BOX MODEL

    content

    padding

    border

    margin

- layout
    - float : parent의 위에 떠있는 구조 → 자식들을 건드린다
    - display
        - flex → 부모를 건드린다 (container(부모), items(자식))
            - direction : column, row, column reverse, row reverse
            - 정렬 속성 : justify-content, align-items
            - ref : [https://css-tricks.com/snippets/css/a-guide-to-flexbox/](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
    - Box Model
    - 배치 변경 : position : absolute → static 배치가 아닌 곳까지 올라가서 배치
- form
    - ref :
        - [https://www.miketaylr.com/pres/html5/forms2.html](https://www.miketaylr.com/pres/html5/forms2.html)
        - [https://developer.mozilla.org/ko/docs/Web/HTML/Element/Input](https://developer.mozilla.org/ko/docs/Web/HTML/Element/Input)