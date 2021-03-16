# Git

**★버전을 통해 코드를 관리하는 도구**



## Git?

**★SCM (Source Code Management) : 코드 관리 도구**

VCS (Version Control Systmem) : 버전 관리 도구 (How manage?)



> 버전?
>
> 1. 언제든지 과거의 특정 시점으로 돌아갈 수 있음
> 2.  매 작업 시점마다 변경 사항을 알 수 있음



### GUI vs. CLI

* GUI (Graphic User Interface) : 그래픽으로 인터렉션 할 수 있음

* CLI (Command Line Interface) : 명령어로 인터렉션 할 수 있음



# CLI

command Line Interface

커맨드(명령어)를 통해 작동하는 인터페이스

<-> GUI(Graphic User Interface, 보통의 프로그램)



## 기초 명령어

### (1) `pwd`

* `pwd` (print working directory) : 현재 폴더의 경로
* `~` (home directory) : 홈 디렉토리(git bash 처음 열면 나오는 기본 폴더)



### (2) `ls`

* `ls` (list): 내용물을 출력(list)



### (3) `cd [폴더명]`

* `cd` (change directory): 폴더를 변경
* `cd ..` : 상위 폴더로 이동
* `cd .` : 현재 폴더로 이동
* `cd /` : 루트 폴더로 이동(`/` 루트 폴더, 최상위 폴더)

* `cd ~` : 홈 폴더로 이동(`~` 홈 폴더)



### (4) `mkdir [폴더명]`

* `mkdir` (make directory): 폴더를 생성



### (5) `rm [파일명]`

* `rm` (remove): 파일을 삭제



### (6) `rm -r [폴더명]`

* `-r` : recursively(재귀적으로) 폴더를 삭제

* `rm -rf /` : 루트로부터 모든 폴더/파일 삭제
* `-r` : 재귀적(recursive)



### (7) `touch [파일명]`

* `touch` : 파일생성



### (8) `cp [파일명] [위치]`

* `cp` (copy): 파일 복사



### (9) `cp -r [폴더명] [위치]`

* 폴더를 복사



### (10) `mv [파일/폴더명] [바꿀파일/폴더명]`

* `mv` (move): 파일/폴더명 변경
* `mv [파일/폴더명] [위치]` : 파일 또는 폴더를 이동