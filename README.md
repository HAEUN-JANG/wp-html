# 웹 응용 프로그래밍 실습(2주차)

### 배운 내용 
> 오늘은 html5에서 사용되는 기본적인 태그들을 직접 실습해보는 시간을 가졌습니다. 글자 태그부터 멀티미디어, 입력 양식 등을 만드는 태그까지 다양한 태그들을 배울 수 있었습니다. 태그 뿐만 아니라 속성들도 함께 사용하는 방법을 배우고 실습으로 적용해보며 html의 기본적인 사용법을 익히는 시간이었습니다. 

### 수업 내용 정리
---------------------------------------
#### 기본 태그
1. 글자 관련 태그 (실습-index.html)
  + h1~h6,p,br,hr,b,i,small,sub,sup,ins,a

    **html에서 공백은 아무리 여러번 입력하여도 하나로 적용된다. 또한 줄바꿈을 하더라도 공백은 적용되지 않는다.
    
    **제목 태그 실습,앵커 태그 실습, 본문 관련 태그 실습, 글자 형태 관련 태그 실습을 진행함.

<앵커태그 a 의 사용>
  + 페이지 내에서 이동하기(실습-index.html)

      a 태그의 href속성값으로 이동하고자 하는 요소의 id 값을 작성한다.

  + 다른 페이지로 이동하기(실습-index.html, anchor.html)

    a 태그의 href속성값으로 이동하고자 하는 페이지 경로 또는 주소를 작성한다.

2. 목록 관련 태그(실습-index.html, list.html)
  + ul(순서x), ol(순서o), li

3. 표 관련 태그(실습-index.html, table.html)
  + caption, thead, tbody, tfoot, tr, th, td


        < th, td 태그의 속성 >
          (1)rowspan--> 행 병합
          (2)colspan--> 열 병합


4. 공간 분할 태그(실습-index.html, space.html, semantic.html)
  + div(공간을 나누긴 하지만 의미는 x), span
  + header, nav, aside, section, article, footer--> 시맨틱 구조 태그


        **inline요소--> 양옆으로 나열되는 요소(a, 글자 관련 태그 등)
          block요소--> 쌓이는 형태로 나열되는 요소(제목태그, p태그 등)


#### 멀티미디어 관련 태그
5. 이미지 태그(실습-image.html, index.html)
  + img태그를 사용하며, src/alt/width/height 등의 속성을 줄 수 있다.
  + 컴퓨터 내의 이미지를 불러오는 로컬이미지와 외부 링크에서 이미지를 가져오는 외부 이미지 실습을 통해 이미지 태그를 연습하였다.

6. 오디오 태그(실습-audio.html, index.html)
  + audio태그를 사용하며, src/preload/autoplay/loop/controls 등의 속성을 줄 수 있다.
  + source태그: 브라우저 간의 지원하는 음악파일의 종류가 다를때, 이를 해결하기 위한 코드
7. 비디오 태그(실습-video.html, youtube.html, index.html)
  + video태그를 사용하며, 속성은 audio와 비슷하다.
  + 컴퓨터 내 동영상 파일을 가져오는 방법과 유투브 화면을 가져오는 방법을 배웠다.

#### 입력 양식 태그
8. 입력양식 태그 (form.html, index.html)
  + 정보를 입력하는 입력 양식 태그
  + form, input, textarea, select, label, fieldset, legend 등 여러 종류의 태그가 존재한다.
  + 위의 태그들에 다양한 속성값을 주며 입력 양식을 완성해보는 실습을 진행했다.
  





