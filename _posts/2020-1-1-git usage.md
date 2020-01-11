---
title: "Git 사용법"
date: 2020-1-1 12:00:00 -0400
categories: git
---

## git 처음 사용하기
 
### 사용자 정보 추가하기
```
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```
 
### 원격저장소 정보
원격저장소 정보 보기
```
git remote -v
```
 
원격저장소 정보 추가
```
git remote add origin https://github.com/username/repositoryName
```
 
---
## git에 일부 내용만 업데이트
 
### 로칼저장소의 인덱스에 추가하기
 
```
git add <file_name>
```
 
### commit
로컬저장소(local repository)에 저장하기
```
git commit -m "new file"
```
 
파일이 저장소에 추가되었는지 확인하기
```
git status
```
### 원격저장소에 반영
로컬저장소의 변경사항을 원격저장소에 반영하기
```
git push origin master
```
Github의 사용자 이름과 암호 입력 후에 Github에 내용이 반영됩니다.
 
## 브랜치 (branch) 사용하기
 
 
[ ^이 글은 **티스토리에 올라온 탁이로그(tagilog.tistory.com) 의 글을 바탕으로, 직접 따라해보면서 정리한 내용** 입니다.]