# html
## html 기초
* `title`  제목태그
* `meta` 문서정보태그
* `Markup` html 을 의미적으로 작성한다 == 마크업
* `Debugging` Html 포함 프로그래밍 언어들의 오류를 검사하여 정상코드로 만든다.
## Vs code 주요 단축키
* `ctrl+/` 한줄 주석
*`shift + alt + a` 블록 주석
* `shift+ alt+ 방향키` 해당 방향으로 복제
## Html 기본작성법
* `<시작태그></닫기태그>
* `<시작태그 속성= "값" 속성="값"></닫기태그>`
* `<빈태그>`
* `alt +z` 자동줄바꿈
* `ctrl+|` 화면 분할
## 타이틀 작성법
* 웹페이지 특성에 따라 타이틀을 작성해야한다.
* 메인페이지일 경우 -> 사이트명
* 서브페이지일 경우 -> 페이지명 | 사이트명
## 특수 문자 태그
* 시작 &   끝 ;
  <code>&lt;body&gt;</code>
* &copy;
* 그룹 div  -2개 이사의 인라인or 블복 요소를 묶어주는 그룹태그  - 블록임..
* 인라인 그룹 - span
## 태그 + 이름 속성 class, id
* .Class: 반복 유형 분류시 사용, 반복지정가능
* #id : 전체 페이지 중 단 하나의 요소에만 지정시 사용
* Class, id는 태그 관계없이 모든 태그에 적용할 수 있습니다. 
## 하이퍼링크태그
* `<a href="#" target="_blank"></a>`
* `target="_blank"` 속성은 링크를 새창으로 띄울때무나 작성한다.
* 새창의 기준은 외부 사이트로 이동 시 결정된다.
## a태그 작성 순서
1. `<a href=""></a>`
2. `<a href="">클릭대상</a>`
3. `<a href="연결경로">클릭대상</a>
### 특정 위치로 바로가기 링크
* 다른 웹페이지가 아닌 같은 페이지 내에 다른 위치로 스크롤되는 바로가기 기능
### 바로가기링크 제작 순서
1. 클릭대상, 이동대상 먼저 제작하기
2. 각 이동 대상의 첫번째 요소에 id 설정하기
3. 위 2번으로 이동시 클릭해야 하는 대상에 href 속성으로 #아이디명 입력하기
## 파비콘 복붙용
* `<link rel="shortcut icon" href="" type="image/x-icon"> <link rel="icon" href="" type="image/x-icon">`
## 비디오 영상
*  autoplay muted loop
* autoplay muted loop controls
* ?autoplay=1&mute=1