# CLI

Command Line Interface (명령어 인터페이스) -> 개발자의 진정한 간지?

## 명령어들

* `ls` : 현재 디렉토리 내부의 파일 & 디렉토리를 보여줌 (**l**i**s**t)

  * `ls -a`:  Show all files even that is hidden모든걸 다 보여줘
  * `ls -al`: list 형태로 이쁘게 보여주는 아이

* `pwd`: 현재 위치를 출력함(**p**rint **w**orking **d**irectory) - 절대(최상단 디렉토리로부터)경로

* `mkdir [directory name]` : 디렉토리(폴더)를 생성(**m**a**k**e **dir**ectory)

* `cd [path]` : 디렉토리를 변경/이동(**c**hange **d**irectory)

* `cd ..`:   상위 디렉토리로 이동(**..**)

* `cd .`: 현재 디렉토리로 이동(**.**)

* ~~`cd /`: 루트(최상단) 디렉토리로 이동(**/**) <-needs to avoid~~

* `cd ~`: home directory로 이동(**~**)

* `rm [파일명]`  : (**r**e**m**ove) 

  * `rm `

    ```java
    // 재귀함수 recursion (스스로에게 돌아오는)
    public static void hello(){
      hello();
    }
    ```