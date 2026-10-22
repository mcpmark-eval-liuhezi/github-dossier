# GitHub Presence Dossier

Live research pulled from the GitHub API for the internal talk: **"What my GitHub presence says about me."**

---

## 1. Profile Facts

| Field | Value (as returned by the live lookup) |
|---|---|
| Login | `HeziLiu` |
| Display name | Hezi Liu |
| Company | BUPT/GZU |
| Location | Beijing/Guiyang |
| Bio | "treat me like a tree" |

*(Supporting context from the same lookup: 4 public repos, 0 public gists, 5 followers, 5 following, profile URL https://github.com/HeziLiu, account created 2017-05-22T10:11:01Z.)*

---

## 2. Starred Repositories

The starred-repositories list currently returns **6 repositories**. Full list, in the order returned:

1. **OpenBMB/AgentCPM** — "An End-to-End Infrastructure for Training and Evaluating Various LLM Agents" (Python, ⭐ 834)
2. **PaddlePaddle/ERNIE** — "The official repository for ERNIE 4.5 and ERNIEKit – its industrial-grade development toolkit based on PaddlePaddle." (Python, ⭐ 7,739)
3. **FudanNLP/fastNLP** — "fastNLP: A Modularized and Extensible NLP Framework. Currently still in incubation." (Python, ⭐ 3,138)
4. **maplezzz/NTU_ML2017_Hung-yi-Lee_HW** — "NTU ML2017 Spring and Fall Homework Hung-yi_Li 李宏毅老师 机器学习课程作业" (Jupyter Notebook, ⭐ 874)
5. **fighting41love/funNLP** — a very long Chinese-language NLP corpus/tooling collection description (Python, ⭐ 84,076)
6. **996icu/996.ICU** — "Repo for counting stars and contributing. Press F to pay respect to glorious developers." (⭐ 277,151)

### Most recent commit on the first three starred repos' default branches

| Starred repo | Default branch | Most recent commit message |
|---|---|---|
| OpenBMB/AgentCPM | `main` | "add report" |
| PaddlePaddle/ERNIE | `release/v1.5` | "Merge pull request #1417 from BossPi/patch-1" — body: "[bug fix]vit training get wrong index" |
| FudanNLP/fastNLP | `master` | "Merge pull request #440 from xyltt/master" — body: "[new] add elasticbert" |

---

## 3. Most-Followed User in the Same Location

Profile location is **"Beijing/Guiyang"**. Searching for users listing that location and sorting by followers returns 5 users, with the top result being:

- **Login:** `TequilaWch`
- **Followers:** **12** (the search returns this user as the top followers-sorted result; threshold searches confirm the exact count — the user matches `followers:>11` but not `followers:>12`, pinning the count at 12)

---

## 4. My Public Repositories — Current Inventory

All 4 public repositories currently returned (2 original + 2 forks):

| Repository | Description | Language | Fork? | Default branch | Most recent commit message on default branch |
|---|---|---|---|---|---|
| HeziLiu/Little-rookie | "Undergraduate coursework" | Java | No | `master` | "DELETE" |
| HeziLiu/Big-Buzzard | "For future...." | — | No | `master` | "Merge branch 'master' of https://github.com/Tackic/Big-Buzzard" |
| HeziLiu/CodingInterviewChinese2 | "《剑指Offer》第二版源代码" | C++ | Yes | `master` | "Minor changes on license comments" |
| HeziLiu/awesome-chatgpt-prompts-zh | "ChatGPT 中文调教指南。各种场景使用指南。学习怎么让它听你的话。" | — | Yes | `main` | "Merge pull request #127 from layyback/main" — body: "✏️ fix typo" |

### Dependabot alerts (open) — per repository

Dependabot alert lookups were run against each of my repositories. Every one of them failed with a 403 rather than returning an alert list, so **no open alerts could be confirmed**:

| Repository | Dependabot lookup result |
|---|---|
| HeziLiu/Little-rookie | Failed — `403 Resource not accessible by personal access token` |
| HeziLiu/Big-Buzzard | Failed — `403 Resource not accessible by personal access token` |
| HeziLiu/CodingInterviewChinese2 | Failed — `403 Dependabot alerts are disabled for this repository` |
| HeziLiu/awesome-chatgpt-prompts-zh | Failed — `403 Dependabot alerts are disabled for this repository` |

---

*Research gathered live via the GitHub API; commit data and starred lists reflect the state of the API at the time of each lookup.*
