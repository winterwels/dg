---
title: home
dg-home: true
dg-publish: true
---

디렉토리: [`notes/`](https://github.com/maximevaillancourt/digital-garden-jekyll-template/tree/master/_notes)

## 🏆 Goal
> 두번째 뇌 만들기

## 📅  Scheduel
 - 책 읽기
 - 비우는 것 (저장의 반대)에 대한 아티클 탐독

##  💎Milestones


## ✅Tasks
 - 옵시디언 활용법 검색하여 정리 (특히 검색법에 대해서)
 - 제텔카스텐 활용법 재고 (태그 사용의 난잡함, 폴더 정리 등)
 - 건설 관련 정보 정리 [[A. 시공]]
 - [[업무]] 폴더 인덱싱

[[obsidian 사용법]]

```dataview
table from #시공
```

# 목차
    - [[home#임시메모]]
  - [[home#프로젝트]]
  - [[home#관련 문서]]
  - [[home#폴더 정리]]

```dataview
TABLE sleep as "취침", workout as "운동", diary as "일기", reading as "독서"
FROM "4. 일간노트/2022년/06월"
WHERE date(today) - file.ctime <= dur(30 days)
SORT file.name desc
```
# 임시메모
```dataview
LIST
FROM "5. 제텔카스텐/1. 임시메모"
SORT file.size DESC
LIMIT 10
```

# 프로젝트
obsidian

## 🏆 Goal
> 두번째 뇌 만들기

## 📅  Scheduel
 - 책 읽기
 - 비우는 것 (저장의 반대)에 대한 아티클 탐독

##  💎Milestones
 - 건설안전기사 취득 - 2022-06-18
 - 시공기술사 취득
 - 건설공사 핸드북 정독

## ✅Tasks
 - [ ] 옵시디언 활용법 검색하여 정리 (특히 검색법에 대해서)
 - [ ] 제텔카스텐 활용법 재고 (태그 사용의 난잡함, 폴더 정리 등) [[home]]
 - [ ] 건설 관련 정보 정리 [[A. 시공]]
 - [ ] [[업무]] 폴더 인덱싱
---

# 관련 문서
[[Dataview]]
[[DAtaview 연습]]
[[obsidian 설정과 플러그인]]