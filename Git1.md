# Git

[github특강](https://docs.google.com/spreadsheets/d/1BbQzYJlHWzMjeuUms3-_TuIwbYxpjjD3_JaH0KFtoSI/edit#gid=1894267597)

Source Code Management(SCM) : 코드 관리 도구

Why?? 코드과리가 너무 힘들어서  literally "Document" 

How?? 버전관리를 통해 코드를 관리한다. `Version Control System`



## 협업도구

#### 1. Push & Pull

* 같은 저장소를 공유하고 **(저장소 공유)**
* push, pull 만을 통해서 협업
* **A**synchronous : 한가지 task가 끝나야지 다음 task가 진행될 수 있는
  * 끝말잇기



#### 2. Fork & PR(Pull Request) = merge request

* Open Source 운영 (Contribution)
* N행시 백일장

#### 3. Brnaching with Shared Repository

* 

## Use

* Code Management (코드 관리 도구)
* Cooperation Tool (협업 도구)
* Spreading Tool (배포 도구)



### Code Management

```
ls
pwd (print working directory)
```

1. **`git init`**
   * git 저장조 (repository) 시작
2. **`git status`**
   * git 상태(status) 보기
3. **`git add [file/folder명]`**
   * staging area 에 파일을 추가 (**add**)
4. **`git rm --cached [file/folder명]`**
   * staging area에서 파일을 제거 (**remove**)
5. **`git commit -m "commit message"`**
   * 스냅샷을 찍기 (현재 상태를 저장하기)
6. `git diff`
   * 어떤 코드들이 추가 변경 되었는지 확인할 수 있다.
7. **`git log`**
   * commit의 history (버전들의 내역)
   * `git log --oneline` : 한개만 
   * `git log --oneline -1` : 가장 마지막 커밋은?

8. `git remote add [저장소의 이름] [저장소의 주소]`
   * `git remote add origin [자장소의 주소]`
     * 처음 만드는 것을 origin을 만드는 것이 관례
9. `git push [저장소의 이름] [브랜치의 이름]`
10. `git clone [git repository 이름]`
11. `git remote remove origin`
    * remote 삭제

**`git remote add origin [repository http://주소] `**

~~~
remote 삭제
git remote remove origin

remote dhfflrl
git remote origin

settings -> invite collaborate
~~~



pull 

* fetch
* Merge



### 협업 (Cooperation)

1. push/pull (Async) - 하나의 작업이 끝나야지만 다음 작업이 시작되는
2. shared repository & branch
3. fork & PR (Open Source Contribute)

```git
mkdir wordchain/
code .
```





### Faults

- Git 폴더 안에 하부 디렉토리를 또 다른 .init 폴더를 만들면 안된다.
- 비밀번호를 저장할 때는 암호화