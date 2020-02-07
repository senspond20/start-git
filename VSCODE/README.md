# VSCODE 에서 git 과 연동하기
---------------------------------------
+ ## VSCODE 소스제어

![step01](https://github.com/senspond20/image/blob/master/VSCODE/step01.png)

+ ## github 저장소에서 url을 복사
-------------------------------------------
![step02](https://github.com/senspond20/image/blob/master/VSCODE/step02.png)

+ ## VSCODE 에서 Ctrl + ` 터미널 창을 열고 다음과 같이 입력

![step03](https://github.com/senspond20/image/blob/master/VSCODE/step03.png)

< 소스제어에서 >

+ ## 스테이징

![step04](https://github.com/senspond20/image/blob/master/VSCODE/step04.png)

+ ## 커밋

![step05](https://github.com/senspond20/image/blob/master/VSCODE/step05.png)

  ++ 커밋 이름 지정합니다.

![step06](https://github.com/senspond20/image/blob/master/VSCODE/step06.png)


+ ## 분기/푸싱
![step07](https://github.com/senspond20/image/blob/master/VSCODE/step07.png)

![step07](https://github.com/senspond20/image/blob/master/VSCODE/step08.png)


+ ## Tip

+ 그냥 Ctrl + ` 터미널 창을 열고 git command 입력해도 된다.

+ VSCODE나 CMD창에서 푸싱을 한 이후에... 
 
 깃허브에서 수정하게 되서 자료가 변경되면  반드시 풀을 해서 로컬저장소로 가져와야한다. 
 
 (그렇지 않고 푸쉬를 해버리면 깃허브에서 수정한것들이 날라감)





# <font color ="#1fds"> VSCODE 개인설정 </font>

## + 테마 설정

+ ## Ctrl + , workbench 입력
    +  Color Thema : 테마 변경
    +  Color Customizations : setting.json 클릭

![VSCODE](https://user-images.githubusercontent.com/60596128/73672608-8e32a300-46f0-11ea-9a6e-b40b6a434f53.png)

위 테마 코드는 아래와 같습니다.
```c
// setting.json
{
    "editor.fontSize": 20,
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "files.exclude": {
        "**/.classpath": true,
        "**/.project": true,
        "**/.settings": true,
        "**/.factorypath": true
    },
    "window.zoomLevel": 0,
    "workbench.colorTheme": "Visual Studio Light",
    "workbench.colorCustomizations": {

        // 타이틀 바
        "titleBar.activeBackground": "#01194eea",
        "titleBar.activeForeground": "#e0f3e0c0",

        "activityBar.activeBackground": "#e0f3e0c0",
        "activityBar.activeFocusBorder": "#ff0000",
        "activityBar.activeBorder": "#ff0000",
        "activityBar.background": "#01194eea",

        "tab.activeBorderTop": "#23a6c76c",
        "tab.activeBackground": "#23a6c76c",
    //  "tab.activeBorderTop": "#f0c7c7",
    //  "tab.activeBackground": "#f0b2b2",

        //"terminal.foreground": "#ff0000",
        //"terminal.background": "#ff0000"
    }
}

```

