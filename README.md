# 알고리즘 스터디

3명이서 4개월간 매주 목요일 저녁 8~10시에 모여 진행하는 알고리즘 스터디입니다.
[LeetCode Top Interview 150](https://leetcode.com/studyplan/top-interview-150/) 기준으로 커리큘럼을 짰고, 자세한 주차별 계획은 노션 페이지를 참고하세요.

- 커리큘럼(노션): [노션 페이지 바로가기](https://app.notion.com/p/3ae3d9b37e1c80728268d77072b7152b?source=copy_link)
- 목표: 개념 완전 정복 + 어려운 문제도 도전할 수 있는 코딩테스트 실전 감각 확보
- 사용 언어: Python(기본), 필요하면 Java

---

## 스터디 취지

혼자 풀 때는 제출 횟수 제한이 없고 시간 제약도 없어서 실제 코딩테스트 환경과 다릅니다.
그래서 **모이는 날에는 실전처럼 시간을 정해놓고 문제를 같이 풉니다.**
LeetCode는 예제 외 테스트케이스가 안 보이고 Submit 결과만 확인할 수 있어서 실전 타임어택 방식에 잘 맞습니다.

---

## 폴더 구조

```
algorithm-study/
├── member1/
│   ├── week01/
│   │   ├── jump_game.py
│   │   └── rotate_array.java
│   ├── week02/
│   └── ...
├── member2/
│   └── ...
├── member3/
│   └── ...
└── .github/
    └── PULL_REQUEST_TEMPLATE.md
```

- 각자 자기 이름 폴더 안에서만 작업합니다.
- 주차별 하위 폴더(`week01`, `week02`, ...)에 그 주 푼 문제를 저장합니다.

---

## 파일 & 커밋 규칙

### 파일명

- Python: 영문 소문자 + 언더스코어. 예) `jump_game.py`, `product_of_array_except_self.py`
- Java: 파스칼케이스(클래스명과 동일해야 함). 예) `JumpGame.java`, `MinStack.java`
- 파일명은 LeetCode 문제명을 영문으로 그대로 사용 (검색/비교하기 쉽게 통일)

### 커밋 메시지

```
[Week01] Jump Game 풀이
[Week03] 3Sum 풀이 (재도전)
```

### 브랜치 & PR (스터디 당일 타임어택 문제만 해당)

- 사전 학습(Easy) 문제는 브랜치 없이 자기 폴더에 바로 push
- 스터디 당일 타임어택 문제는 브랜치 파서 PR로 올리고, 스터디 시간에 리뷰 후 merge
  - 브랜치명: `week01/이름/jump-game`
  - PR 제목: `[Week01] Jump Game - 이름`
  - PR 본문은 `.github/PULL_REQUEST_TEMPLATE.md` 양식 사용

---

## 스터디 당일 진행 순서 (2시간)

1. 위클리 스탠드업 (10~15분): 로테이션으로 그 주 개념 요약 + 진행현황 점검
2. 타임어택 문제풀이 (90분): Medium~Hard 2~3문제, 문제당 25~35분
3. 풀이 공유 & 코드 리뷰 (30~40분): PR 기반으로 서로 리뷰 후 merge

## 오답 관리

- 시간 안에 못 푼 문제는 다음 주 시작 전까지 마무리해서 각자 폴더에 정리
- 매주 시작 5분은 지난주 오답 복습


