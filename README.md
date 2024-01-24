# memorize_pi
## 원주율 외우기 게임 (Made by Pygame)
    How to execute:
        (Command prompt) "python memorize_pi.py"

    How to make EXE file:
        (Command prompt) "pyinstaller -w -F -i icon.ico memorize_pi.py"
        - pyinstaller download command: "pip install pyinstaller"

    Used Python Packages:
        - pygame (To make main game window)
        - requests (To get response that contains 10000 dights of PI)
        - bs4 (BeautifulSoup4, To parse response)
        - datetime (To memorize your game history)
        - pymsgbox (To know if you want to play more)
        - lxml (html parser engine for bs4)

        - How to install these packages:
            (Command Prompt) "pip install pygame requests bs4 pymsgbox lxml"
            - datetime: default package (Don't install with pip)

    How to clone (with git):
        - url: https://github.com/Math-dna/memorize_pi.git
        ===> command - "git clone https://github.com/Math-dna/memorize_pi.git