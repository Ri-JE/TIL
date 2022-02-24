# 2일차 정리

## [1일차 복습](https://github.com/Ri-JE/TIL/blob/master/day01.md)

- CLI
- 마크다운
- git 기초
- TIL

---

## github

#### github 시작하기

- github 가입

  ```bash
  # 가입하고 난 이후
  
  # 유저 닉네임 확인
  git config --global --list
  
  # 유저 닉네임/이메일 설정
  git config --global user.name "깃허브 닉네임"
  git config --global user.email "깃허브 이메일"
  
  # 유저 닉네임/이메일 삭제
  git config --global --unset user.name
  git config --global --unset user.email
  ```

- github 설정 변경

  1. 오른쪽 상단 프로필을 클릭
  2. `Settings` 를 클릭
  3. 왼쪽 안내 바에서 `Repositories`를 선택
  4. `Repository default branch`의 입력 창에서  `main`을 지우고 `master`로 작성
  5. `Update`를 클릭

#### 원격 저장소

- github에서 원격 저장소 생성
- 로컬 저장소와 원격 저장소 연결

---

## .gitignore

---

## clone, pull

