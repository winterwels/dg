---
title: home
dg-home: true
dg-publish: true
---

๋๋ ํ ๋ฆฌ: [`notes/`](https://github.com/maximevaillancourt/digital-garden-jekyll-template/tree/master/_notes)

## ๐ Goal
> ๋๋ฒ์งธ ๋ ๋ง๋ค๊ธฐ

## ๐  Scheduel
 - ์ฑ ์ฝ๊ธฐ
 - ๋น์ฐ๋ ๊ฒ (์ ์ฅ์ ๋ฐ๋)์ ๋ํ ์ํฐํด ํ๋

##  ๐Milestones


## โTasks
 - ์ต์๋์ธ ํ์ฉ๋ฒ ๊ฒ์ํ์ฌ ์ ๋ฆฌ (ํนํ ๊ฒ์๋ฒ์ ๋ํด์)
 - ์ ํ์นด์คํ ํ์ฉ๋ฒ ์ฌ๊ณ  (ํ๊ทธ ์ฌ์ฉ์ ๋์กํจ, ํด๋ ์ ๋ฆฌ ๋ฑ)
 - ๊ฑด์ค ๊ด๋ จ ์ ๋ณด ์ ๋ฆฌ [[A. ์๊ณต]]
 - [[์๋ฌด]] ํด๋ ์ธ๋ฑ์ฑ

[[obsidian ์ฌ์ฉ๋ฒ]]

```dataview
table from #์๊ณต
```

# ๋ชฉ์ฐจ
    - [[home#์์๋ฉ๋ชจ]]
  - [[home#ํ๋ก์ ํธ]]
  - [[home#๊ด๋ จ ๋ฌธ์]]
  - [[home#ํด๋ ์ ๋ฆฌ]]

```dataview
TABLE sleep as "์ทจ์นจ", workout as "์ด๋", diary as "์ผ๊ธฐ", reading as "๋์"
FROM "4. ์ผ๊ฐ๋ธํธ/2022๋/06์"
WHERE date(today) - file.ctime <= dur(30 days)
SORT file.name desc
```
# ์์๋ฉ๋ชจ
```dataview
LIST
FROM "5. ์ ํ์นด์คํ/1. ์์๋ฉ๋ชจ"
SORT file.size DESC
LIMIT 10
```

# ํ๋ก์ ํธ
obsidian

## ๐ Goal
> ๋๋ฒ์งธ ๋ ๋ง๋ค๊ธฐ

## ๐  Scheduel
 - ์ฑ ์ฝ๊ธฐ
 - ๋น์ฐ๋ ๊ฒ (์ ์ฅ์ ๋ฐ๋)์ ๋ํ ์ํฐํด ํ๋

##  ๐Milestones
 - ๊ฑด์ค์์ ๊ธฐ์ฌ ์ทจ๋ - 2022-06-18
 - ์๊ณต๊ธฐ์ ์ฌ ์ทจ๋
 - ๊ฑด์ค๊ณต์ฌ ํธ๋๋ถ ์ ๋

## โTasks
 - [ ] ์ต์๋์ธ ํ์ฉ๋ฒ ๊ฒ์ํ์ฌ ์ ๋ฆฌ (ํนํ ๊ฒ์๋ฒ์ ๋ํด์)
 - [ ] ์ ํ์นด์คํ ํ์ฉ๋ฒ ์ฌ๊ณ  (ํ๊ทธ ์ฌ์ฉ์ ๋์กํจ, ํด๋ ์ ๋ฆฌ ๋ฑ) [[home]]
 - [ ] ๊ฑด์ค ๊ด๋ จ ์ ๋ณด ์ ๋ฆฌ [[A. ์๊ณต]]
 - [ ] [[์๋ฌด]] ํด๋ ์ธ๋ฑ์ฑ
---

# ๊ด๋ จ ๋ฌธ์
[[Dataview]]
[[DAtaview ์ฐ์ต]]
[[obsidian ์ค์ ๊ณผ ํ๋ฌ๊ทธ์ธ]]