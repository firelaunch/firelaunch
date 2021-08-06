```python
#       __ _          _                        _     
#      / _(_)_ __ ___| | __ _ _   _ _ __   ___| |__  
#     | |_| | '__/ _ \ |/ _` | | | | '_ \ / __| '_ \ 
#     |  _| | | |  __/ | (_| | |_| | | | | (__| | | |
#     |_| |_|_|  \___|_|\__,_|\__,_|_| |_|\___|_| |_|

from firelaunch import LANGUAGES
from firelaunch import FRAMEWORKS
from firelaunch import TOOLS     

def languages():
    language = ["Python", "Arduino", "HTML", "CSS"]  
    if len(language) == 4 :
        print("Language used :",language)
    else :
        print("Error printing Languages..")
languages()

def frameworks():
    framework = ["Flask", "OpenCV", "PyQt5", "Tkinter"]  
    if len(framework) == 4 :
        print("Framework used :",framework)
    else :
        print("Error printing frameworks..")
frameworks()

def tools():
    tool = ["Visual Studio Code", "Arduino IDE"]  
    if len(tool) == 2 :
        print("Tools used :",tool)
    else :
        print("Error printing tools..")
tools()

```
<a href = "https://github.com/firelaunch" targer = "new" rel = "noopener"><img src = "github.png" width = "500"></a><br><br>
<a href = "https://gitlab.com/firelaunch" targer = "new" rel = "noopener"><img src = "gitlab.png" width = "500"></a>
