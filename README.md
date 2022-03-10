# html_1
Created with CodeSandbox

![3](https://user-images.githubusercontent.com/37132897/157596347-bc95faf6-45b0-4ecd-b254-9c5db3ddf621.PNG)


공부한 내용들 : 

- h${hello world}*6 적고 탭 누르면, "hello wrold" 의 내용이 h1~h6 까지 생성된다.

(h(헤딩)은 h1에서 h6 까지만 존재한다, 문서 내에는 h1이 하나만 있는것을 추천한다.)

- p 태그는, 문단을 나타낸다. <p></p>
- 5sub2 는, 5<sub>2</sub>
- 2sup4 는, 2<sup>4</sup>
- Lorem : 의미없는 문구
- br 로 줄 이동, 안 닫아도 됨 

- br 로 줄 이동, 안 닫아도 됨
- hr 쓰면, 구분선 하나 그어짐, 안 닫아도 됨
- ctrl + / 하면 여러줄,한줄 주석 설정 및 해제 가능, 빈 줄에 하면 주석을 생성

a (앵커) 태그
- a href="링크~" 여길 누르시면, 홈페이지에 연결됩니다. </a>
- a href="링크~" target = "_blank" : _blank 를 해주면, 새로운 창에서 홈페이지가 열린다.
- a href="./index.html~"> : ./를 해주면, 현재 폴더에 있는 어떤 파일로 이동하게 할 수 있다.
- a href="#move" : #을 해주면, 이 페이지 내에 move 라는, ID를 가진 태그의 내용 부분으로 화면을 이동하게 된다.
- a href=./test.png" download : download 를 이용해서, 이걸 클릭했을때 다운로드 할 수 있게도 할 수 있다. 그 파일이 현재 폴더에 없으면 다운로드 안됨

글자 바꾸기
- strong: 글자 굵게
- b : 글자 굵게
- em : 글자 옆으로 기울어지게
- i : 글자 옆으로 기울어지게
- mark : 형광펜 마냥 칠해짐


기타 잘 쓰이는 태그
- abbr : 약어를 표현할때 사용, 해당 글자 위에 커서 올려두면 abbr title= 에 입력한 내용이 뜬다. 

Ex) <abbr title="HyperText Markup Language">HTML</abbr>
- kbd : 키보드 키를 나타낼때 사용

Ex) <kbd>Ctrl</kbd>

- pre : 있는 그대로 나타낸다
Ex) <pre> 띄어쓰기       와   
줄 바꿈  등이 내가 적은 코딩 그대로 표현된다. </pre>
- code : 코드 블록(컴퓨터 코드 범위를 설정)

Ex) <code> 이 부분이 코드 블록입니다 </code>
- cite : 저작물의 출처를 표기할때 사용(q는 인용구, cite는 인용블록)

