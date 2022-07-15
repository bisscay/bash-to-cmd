| BASH$ | CMD> | PowerShell> |
| :--- | :--- | :--- |
| man ls | help dir | |
| | | |
| cat trial.py | type trial.py | |
| | | |
| $JAVA_HOME | echo %JAVA_HOME% | $env:JAVA_HOME | 
| | | |
| touch sample.py | type NUL > trial.py | |
| | | |
| ls -l &#124; grep string | dir &#124; findstr string | |
| | | |
| rm -rf * | del /s /q * |
| | |
| ls -alr | dir /s |
| | |
| echo 'special characters' >> index.html | echo "special characters" >> index.html |
| | |
| export env_var=executable.py | set env_var=executable.py
| | |
| source venv/bin/activate | venv\Scripts\activate |
| | |
| ln file-name.py hard-link.py | mklink /h hard-link.py file-name.py
| | |
| ln -s folder-name soft-link | mklink /d soft-link folder-name
| | |

***TO DO:***
*Link each command to an explanation read-me.*
