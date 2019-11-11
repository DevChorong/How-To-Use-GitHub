# 깃허브 사용방법

> 1. GitHub에 로그인한다
> 2. download **"git bash"**
> 3. create a file for my repository // repository를 만든다.
> 4. 내 로컬PC에 폴더를 하나만든다
> 5. 만들어낸 폴더에  "git bash here"
> 6. 뜬 프롬포트 창에다가 < *git init*  > 을입력한다.  (< > 는 빼고! 안에 내용만!)
> 7. < *git remote add origin "my repository address"*  >을입력한다.
> 8. 이때 "my repository address" 부분은 내가 Github에 만든 Repository의 주소를 넣는다.



============[this is a starting Level for basic user]===========

### [ Push ] : 내 로컬파일 -> Github Repository 

#### *when we use it?*

>내 PC에서 작업이 끝난 뒤에 사용한다!

### *how to use?*

**" git bash "**를 켠다.

```Git bash
git status
git add .
git commit -m "something that you want to tell someone who read it"
git push origin +master
```

### [ Pull ]  : Github Repository -> 내 로컬파일

### *when we use it?*

>GIthub에 올라와있는 파일을 내 컴퓨터로 다운 받을때!

### *how to use?*
1. 다운 받기 위한 새로운 파일을 하나 만든다.

**" git bash "**를 켠다.

```Git bash
git init
git remote add origin 이부분에 다운받을 Github 사이트를 적는다.
git pull origin master
```

