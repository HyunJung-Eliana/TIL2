# 원격 저장소(remote repository) 기초

## 기본 설정

* 로컬에 git 저장소
* Github에 remote repository를 생성

## 명령어

### 원격 저장소 설정

```bash
$ git remote add origin http://github.com/HyunJung-Eliana/practice1.git
```

* 깃, 원격저장소(remote) 추가해줘(add) origin이라는 이름으로 저장소 URL을
  * origin은 원격저장소 이름!

### 원격 저장소 목록 보기

```bash
$ git remote -v
origin  https://github.com/HyunJung-Eliana/practice1.git (fetch)
origin  https://github.com/HyunJung-Eliana/practice1.git (push)
```

### 원격 저장소 설정 삭제하기

```bash
$git remote rm origin
```

* 깃아, 원격저장소(remote) 삭제해줘(rm : remove) origin..을

### push

```bash
$ git push origin master
Logon failed, use ctrl+c to cancel basic credential prompt.
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 220 bytes | 73.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/HyunJung-Eliana/practice1.git
 * [new branch]      master -> master
```

* 깃아, 푸쉬해줘 origin 원격저장소에 master 브랜치!

