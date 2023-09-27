# today's lecture

## pwd 
pwd: shows the current path in a huerachical directory.  
"pwd"는 "Print Working Directory"의 약자로, 현재 작업 디렉토리를 출력하는 명령어입니다. 이 명령어는 주로 컴퓨터의 터미널 또는 명령 프롬프트에서 사용됩니다. "작업 디렉토리"는 현재 작업 중인 디렉토리나 폴더를 나타냅니다.

## cd
cd:change directory
- "cd" 명령어는 현재 작업 디렉토리를 변경하는데 사용됩니다.
- 사용 방법은 다음과 같습니다: cd [디렉토리 경로]
- 예를 들어, "cd documents"라고 입력하면 현재 디렉토리가 "documents"라는 하위 디렉토리로 변경됩니다. 따라서 이제 파일 작업이 "documents" 디렉토리 내에서 이루어집니다.
- cd .."를 사용하면 현재 디렉토리의 상위 디렉토리로 이동할 수 있습니다.
- "cd" 명령어를 실행할 때 주의할 점은 디렉토리 경로를 올바르게 입력해야 한다는 것입니다.

## ls
ls:list files and directories  
- "ls" 명령어는 현재 디렉토리에 있는 파일과 디렉토리 목록을 표시하는 데 사용됩니다.
- 사용 방법은 다음과 같습니다: ls [옵션] [디렉토리 경로]
- "ls" 명령어를 입력하면 현재 디렉토리의 내용을 나열합니다. 예를 들어, "ls"를 입력하면 현재 디렉토리에 있는 파일과 디렉토리 목록이 표시됩니다.
- "[옵션]" 부분은 다양한 출력 형식과 정렬 순서 등을 지정할 수 있는 선택적 옵션입니다. 예를 들어, "ls -l"은 자세한 정보를 포함한 리스트를 보여줍니다.
- "[디렉토리 경로]"를 지정하면 다른 디렉토리의 내용을 볼 수 있습니다. 예를 들어, "ls /home/user/documents"는 "/home/user/documents" 디렉토리의 내용을 나열합니다.

## shell command:clear
clear 명령어는 터미널 또는 명령 프롬프트 창의 화면을 지워서 이전에 출력된 내용을 모두 지우는 명령어입니다. 이를 통해 작업 공간을 정리하고 화면을 깨끗하게 유지할 수 있습니다.  

## cp
cp: copy files and directories  
"cp" 명령어는 파일이나 디렉토리를 복사하는 명령어입니다. "cp"는 "Copy"의 약자입니다. 이 명령어를 사용하여 파일을 다른 경로로 복사하거나 파일의 사본을 생성할 수 있습니다. 

## mv
mv:move files and directories or rename them  
mv" 명령어는 파일 또는 디렉토리를 이동하거나 이름을 변경하는 데 사용되는 명령어입니다. "mv"는 "Move"의 약자이며, 파일 또는 디렉토리를 현재 디렉토리 내에서 다른 위치로 이동하거나 이름을 변경할 때 사용됩니다.   

## rm
rm: delete files and directories ***permantely and irreversevely!!***
"rm" 명령어는 파일 또는 디렉토리를 삭제하는 데 사용되는 명령어입니다. "rm"은 "Remove"의 약자입니다. 이 명령어를 사용하여 파일이나 디렉토리를 영구적으로 삭제할 수 있습니다.

## mkdir 
mkdir: make a new directory
"mkdir" 명령어는 새로운 디렉토리(폴더)를 생성하는 명령어입니다. "mkdir"은 "Make Directory"의 약자입니다. 이 명령어를 사용하여 컴퓨터 파일 시스템에서 새로운 디렉토리를 만들 수 있습니다.  

## wildcards
Wildcards(와일드카드)는 파일 및 디렉토리 이름을 패턴 매칭하기 위한 특수 문자입니다. 와일드카드를 사용하면 여러 파일 또는 디렉토리를 한 번에 선택하고 조작할 수 있습니다.  
- *: all filenames
- g*: all finemanes that begin with the characters "g"
- b*.txt: all filename that begin with the charactres "b" and end with the characres  ".txt"
- data???: any filename that begins with the characters "data" followed by exactly 3 more characters

## help command
1. help:Windows의 명령 프롬프트 (Command Prompt) 또는 PowerShell에서 "help" 명령어는 사용 가능한 명령어 및 명령어에 대한 도움말을 표시하는 데 사용됩니다.
2. man: "man"은 Unix 및 Unix 계열 운영 체제에서 사용되는 명령어 및 프로그램에 대한 매뉴얼 페이지를 표시하는 명령어입니다. "man"은 "manual"의 약자로, 사용자가 명령어 및 프로그램의 사용법, 옵션, 설명 등을 확인하는 데 사용됩니다.

## exit
exiting terminal: exit  
"exit" 명령어는 명령 프롬프트나 터미널 세션을 종료하는 데 사용됩니다. 이 명령어를 실행하면 현재 터미널 또는 명령 프롬프트 창이 종료되고, 현재 세션은 종료됩니다.  
-$exit
