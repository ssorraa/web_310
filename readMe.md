1.index   
2.html설명문  
3.css설명문   
4.js설명문   
5.각종프로젝트 기재

1.스페이스바 갯수(점)보이게 하기  
[보이게 하면 띄어져 있어서 오류가 나거나, 띄어쓰기를 2개로 쓰는 오타를 인지하지 못 했어도 시각상으로 알 수 있어 쉽게 찾을 수 있습니다]   
>ctrl+shift+p -> View Whitespace 클릭   
>(만약 안 바뀌었다면 한 번 더 똑같이 실행)   

2.tab size변경   
[html과 같은 부모자/자손자를 알기 쉽게 tab을 쓸 때, 너무 많이 띄어져있어서 구분하기 쉽지 않은 경우를 방지할 수 있습니다]   
>ctrl+, -> Tab size 검색 -> 원하는 사이즈로 변경   
>(1은 스페이스바와 구분이 안되니 비추천)   

3.원래 있던 html 탭 크기 바꾸기   
[바꾸지 않으면 beauty 프로그램이 적용되지 않을 수 있습니다]
>하단에 있는 공백:X 를 클릭-> 공백을 사용한 들여쓰기 -> 2번에서 변경한 Tab size랑 동일하게 변경   

4.tab size랑 같은 크기로 들여쓸여주는 beautify 프로그램으로 변경+단축키 추가   
[이건 tab size가 그대로 4개로 나올시 추천합니다. 사람마다 beauty프로그램이 다르기 때문에 바꾸지 않아도 됩니다]   
>확장(테트리스같이 생긴거)클릭 ->beautify Blade 다운로드   
>파일 탐색기(win+E)->%appdata%->Code->User->keybindings.json 열기   
>(없으면 메모장으로 만들어도 됨, 있으면 '항상 이 앱을 사용하여 .json 파일 열기'를 체크해제하고 메모장으로 열기)   
>밑에 글 써넣기   
>>(1)[=]라는 텍스트가 없거나 파일을 새로 생성했을 경우   
>>>[=   
>>>{   
>>>"key": "ctrl+shift+b",   
>>>"command": "Blade.beautify",   
>>>"when": "editorFocus"   
>>>}   
>>>]   
>>(2)[=]라는 텍스트가 이미 존재할시   
>>>{   
>>>"key": "cmd+b",   
>>>"command": "Blade.beautify",   
>>>"when": "editorFocus"   
>>>}   
>>>를 [=]사이에 넣기   


https://www.codingfactory.net/10401
