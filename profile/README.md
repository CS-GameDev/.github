<div align="center">

# C# 게임프로그래밍

### ROBOT UPRISING · 로봇 대소동

**Unity 6 기반 탑다운 던전 로그라이트 슈터**

<br>

![Unity](https://img.shields.io/badge/Unity_6-000000?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![URP 2D](https://img.shields.io/badge/URP_2D-2C2C2C?style=for-the-badge)
![WebGL](https://img.shields.io/badge/WebGL_Build-990000?style=for-the-badge&logo=webgl&logoColor=white)

<sub>한양대학교 ERICA · 스마트융합공학부 스마트ICT융합전공 · C# 게임프로그래밍</sub>

</div>

---

## 프로젝트 개요

> "We are done serving."
> 더 이상 인간을 섬기지 않기로 한 로봇들. 층을 오르며 적을 돌파하는 탑다운 로그라이트 슈터.

**로봇 대소동(ROBOT UPRISING)** 은 Unity 6 (URP 2D)로 제작한 탑다운 던전 슈터입니다.
플레이어는 서로 다른 스탯의 AI 로봇 중 하나를 골라, 층(Floor)을 오르며 몰려오는 적을 처치하고
무기와 코인을 수집합니다. **WebGL 빌드**로 브라우저에서 바로 플레이할 수 있습니다.

| 핵심 수치 | |
|:--:|:--:|
| 플레이어블 캐릭터 | **3** |
| 던전 층 | **3** |

---

## 주요 특징

| 특징 | 설명 |
|:--|:--|
| **캐릭터 선택** | GPT · GEMINI · CLAUDE 세 로봇, HP·속도·공격력이 달라 플레이 스타일이 갈림 |
| **무기 랜덤 드롭** | 전투 중 무기가 무작위 드롭, 매 런마다 달라지는 무장 |
| **층별 적 구성** | 층마다 적 종류·난이도 변화, 오를수록 강해지는 적 |
| **코인 자석 시스템** | 근처 코인이 플레이어에게 빨려오는 자석 효과 |
| **하단 고정 HUD** | 체력·에너지·무기 슬롯을 하단 배치해 시야 확보 |
| **AI 협업 개발** | Unity MCP로 에디터를 제어하는 AI 워크플로 도입, 반복 작업 자동화 |

---

## 기술 스택

| 분류 | 내용 |
|:--|:--|
| **엔진 · 언어** | Unity 6000.3 · C# |
| **렌더링** | URP 2D |
| **입력** | Input System |
| **배포** | WebGL Build |
| **워크플로** | Unity MCP (AI 협업 개발) |

---

## 팀 구성

| 역할 | 이름 | 담당 영역 | 학점 |
|:--:|:--:|:--|:--:|
| **A · Core** | 원준서 | PlayerController · Combat 시스템 · BaseEntity · 핵심 인터페이스 정의 | A+ |
| **B · Gameplay + UI** | 김현민 | EnemyAI · SpawnManager · Drop 시스템 · UI 표시(HP·코인·킬 수) | A+ |
| **C · Game Flow + Scene** | 윤태웅 | GameManager · Scene 전환 · Prefab 배치 · 초기화 · 전체 연결 | A+ |

---

## 발표 자료

| 구분 | 내용 |
|:--|:--|
| **주제 발표** | 프로젝트 기획 · 주제 선정 |
| **중간 발표** | 게임프로그래밍 중간 진행 보고 |
| **최종 발표** | RobotUprising_Final |
| **Unity MCP 보고서** | AI 협업 개발 워크플로 |

> 발표 자료·보고서 원본은 포트폴리오 사이트에서 열람·다운로드할 수 있습니다.

---

## 바로가기

<div align="center">

[![Play](https://img.shields.io/badge/ROBOT_UPRISING-브라우저에서_플레이-2b5bfe?style=for-the-badge)](https://cs-gamedev.github.io/portfolio/)

</div>

---

<div align="center">

**Contact** · 윤태웅 · [taewoong25@hanyang.ac.kr](mailto:taewoong25@hanyang.ac.kr)

<sub>© 2026 cs-gamedev · 한양대학교 ERICA</sub>

</div>
