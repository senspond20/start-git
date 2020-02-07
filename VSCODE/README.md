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

