# scrollSection
스크롤영역 감지 


# 사용법
new sectionScroll('감지될영역', 시작점보정(숫자), 영역 진입시 실행될함수);

ex) 
new sectionScroll('.section_product', 2, function(){
    console.log('start2');
});

- 시작점은 윈도우 innerHeight / 2 가 기본값임
- 시작점보정값이 작아질수록 빠르게 클수록 늦게 정의된 함수가 실행됨
