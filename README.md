# Yony | Yang Younghee

기획자입니다. 

---

저는 업무 자동화와 지식 관리를 위해 코드를 공부합니다. 
"필요한 것을 만들기 위해" 라는 동기가 먼저였고, 언어는 나중에 따라왔습니다.

10년간 현업에서 대리점 관리와 구매, 발주, 재고, 실적을 관리했고,  
지금은 사내 DX·AX 로드맵을 설계하면서 RPA 자동화를 직접 개발·운영합니다.  
퇴근 후에는 개인 생산성 시스템을 고쳐 씁니다.

---

## Why GitHub

버전 관리가 필요해서입니다.

아이디어를 메모하던 방식으로 코드를 다룰 수는 없었습니다.  
어제의 스크립트가 오늘의 시스템을 망가뜨리는 경험을 몇 번 한 뒤,  
Git을 쓰는 것이 선택이 아니라 위생의 문제라는 걸 이해했습니다.

이 계정에는 두 종류의 코드가 있습니다.  
하나는 사내 자동화(Brity RPA, ERP 연동)이고,  
다른 하나는 개인 생산성 시스템(PKM 동기화, 소비 분석, 루틴 추적)입니다.  
둘 다 "내가 쓰기 위해" 만든 것들입니다.

---

## What I Build

**PKM & 지식 관리**  
UpNote에서 Obsidian으로의 단방향 동기화 엔진(`sync_engine.py`)을 직접 구현해 운영합니다.  
UUID 기반 파일 매핑, mtime 변경 감지, Windows Task Scheduler 연동.  
2,700개 이상의 노트가 이 파이프라인 위에서 움직입니다.

**업무 자동화**  
Brity RPA로 사내 ERP 데이터 업데이트, 회계·영업 팀 반복 업무를 자동화합니다.  
실행 환경은 Rhino/ES5이며, .NET 클래스를 직접 호출하는 방식으로 파일 처리를 우회합니다.

**데스크탑 대시보드**  
Electron 기반의 플로팅 대시보드 DX-board를 개발 중입니다.  
URL, 로컬 앱, Python 스크립트를 더블클릭 하나로 실행하는 빠른 실행 도구입니다.

**개인 데이터 파이프라인**  
Google Sheets 적재 → Appsheet에서 기록 → Telegram 알림까지,  
GAS환경에서 재무·소비·루틴·환율 데이터를 하나의 생태계 안에서 관리합니다.

---

## Tech Stack

| 영역 | 도구 |
|---|---|
| **자동화** | Google Apps Script, Python, Brity RPA |
| **데스크탑** | Electron |
| **데이터·BI** | Google Sheets, Power BI |
| **PKM** | UpNote, Obsidian |
| **환경** | Windows, VSCode, Git |

---

## Writing

코드보다 글을 먼저 씁니다.

[Naver Blog](https://blog.naver.com/yana_stella) · [Brunch](https://brunch.co.kr/@yonycompany)  
저서: 《일상채우기기술》 《미라클리딩》

---

## Note for Developers

저는 전문 개발자가 아닙니다.  
시스템을 설계하는 기획자이고, 그 시스템을 직접 구현하기 위해 코드를 씁니다.

코드가 다소 투박할 수 있습니다.  
더 나은 로직에 대한 조언은 언제나 환영합니다.
