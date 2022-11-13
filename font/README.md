## windows terminalの外観を変更する
windowsに以下２つのフォントをインストール
- Meslo LG S Bold Nerd Font Complete.ttf
- Meslo LG S Regular Nerd Font Complete.ttf
  
windows terminal → 設定 → JSONファイルを開く  
以下の項目を追加  

```
"profiles": 
    {
        "defaults": 
        {
          "font": {
            "face": "Cascadia Mono"
          }
        },
        "list": 
        [
          {
            "colorScheme": "Brogrammer",
            "guid": "{59b72ad2-09f7-55ec-af87-65d062af8472}",
            "hidden": false,
            "name": "Ubuntu 20.04.5 LTS",
            "opacity": 90,
            "source": "CanonicalGroupLimited.Ubuntu20.04LTS_79rhkp1fndgsc",
            "font": {
              "face": "MesloLGS Nerd Font"
          }
        ]
    },
  "schemes": 
    [
        {
            "background": "#131313",
            "black": "#1F1F1F",
            "blue": "#2A84D2",
            "brightBlack": "#D6DBE5",
            "brightBlue": "#1081D6",
            "brightCyan": "#0F7DDB",
            "brightGreen": "#1DD361",
            "brightPurple": "#5350B9",
            "brightRed": "#DE352E",
            "brightWhite": "#FFFFFF",
            "brightYellow": "#F3BD09",
            "cursorColor": "#B9B9B9",
            "cyan": "#1081D6",
            "foreground": "#D6DBE5",
            "green": "#2DC55E",
            "name": "Brogrammer",
            "purple": "#4E5AB7",
            "red": "#F81118",
            "selectionBackground": "#1F1F1F",
            "white": "#D6DBE5",
            "yellow": "#ECBA0F"
        },
    ]
```