1.index
2.html설명문
3.css설명문
4.js설명문
5.각종프로젝트 기재

1.스페이스바 갯수(점)보이게 하기
ctrl+shift+p -> View Whitespace 클릭
(만약 안 바뀌었다면 한 번 더 똑같이 실행)

2.tab size변경
ctrl+, -> Tab size 검색 -> 원하는 사이즈로 변경(1은 스페이스바와 구분이 안되니 비추천)

3.tab size랑 같은 크기로 들여쓸여주는 beautify 프로그램으로 변경+단축키 추가
확장(테트리스같이 생긴거)클릭 ->beautify Blade 다운로드
파일 탐색기(win+E)->%appdata%->Code->User->keybindings.json 열기
(없으면 메모장으로 만들어도 됨, 있으면 '항상 이 앱을 사용하여 .json 파일 열기'를 체크해제하고 메모장으로 열기)
밑에 글 써넣기
(1)[=]라는 텍스트가 없을시
[=
{
"key": "ctrl+shift+b",
"command": "Blade.beautify",
"when": "editorFocus"
}
]
(2)[=]라는 텍스트가 이미 존재할시
{
"key": "cmd+b",
"command": "Blade.beautify",
"when": "editorFocus"
}
를 [=]사이에 넣기

4.원래 있던 html 탭 크기 바꾸기
하단에 있는 공백:X 를 클릭-> 공백을 사용한 들여쓰기 -> 2번에서 변경한 Tab size랑 동일하게 변경
