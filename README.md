# 🏰 총학생회 봉건제 마인크래프트 서버

> 9개 국서가 황제국과 영주국으로 나뉘어 한 학기 동안 영토·자원·외교를 두고 경쟁하는 봉건 정치 시뮬레이션 마크 서버.

[![Status](https://img.shields.io/badge/status-v1%20%EC%84%A4%EC%B9%98%20%EC%99%84%EB%A3%8C-success)](#)
[![Edition](https://img.shields.io/badge/edition-Java%201.21.x-blue)](https://www.minecraft.net/download)
[![License](https://img.shields.io/badge/docs-CC--BY--SA--4.0-lightgrey)](LICENSE)

## 🚀 빠른 접속 (3분 컷)

| 정보 | 값 |
|------|-----|
| **서버 주소** | **`policies-untagged.gl.joinmc.link`** ← 이 주소를 그대로 붙여넣기 |
| **에디션** | **Minecraft Java Edition 1.21.x만 지원** ⚠️ |
| **포트** | 25565 (기본 — 주소만 입력하면 자동) |
| **모드** | 화이트리스트 ON — 운영진 사전 등록 필요 |

### 1단계 — Minecraft 설치
- **Java Edition** 다운로드: https://www.minecraft.net/download
- ⚠️ **Bedrock Edition (모바일·콘솔판) 절대 X**
- 처음 설치하면 자동으로 최신 버전(1.21.x)으로 설치됨

### 2단계 — Microsoft 계정 로그인
- 정품 라이센스 필요 (학생 라이센스 또는 본인 라이센스)
- 라이센스 없으면 운영진 문의

### 3단계 — 서버 추가
1. Minecraft 실행 → **멀티플레이** 클릭
2. **서버 추가** → 서버 이름: `총학생회 서버` / 서버 주소: 위의 서버 주소 입력
3. **완료** → 서버 목록에서 클릭하면 접속 시도

### 4단계 — 화이트리스트 등록 확인
- 본인 Minecraft 닉네임을 운영진에게 미리 전달해두기
- 운영진이 등록하지 않으면 `Not whitelisted on this server` 오류

⏩ **첫 접속 후**: 자국 leader에게 Discord 또는 채팅으로 초대 요청 → leader가 `/t add <닉네임>` 으로 추가

---

## 📖 자세한 가이드

| 문서 | 내용 |
|------|------|
| [JOIN-GUIDE.md](docs/JOIN-GUIDE.md) | 단계별 접속 가이드 (스크린샷 포함) |
| [RULEBOOK.md](docs/RULEBOOK.md) | 봉건제 룰북 — 위계, 평화기, SiegeWar, 그리핑 |
| [FAQ.md](docs/FAQ.md) | 자주 묻는 질문 |
| [troubleshooting.md](docs/troubleshooting.md) | 안 들어갈 때 체크리스트 |
| [nation-map.md](docs/nation-map.md) | 9 국서 좌표 표 |

---

## 🏛️ 9 국서 (Nations)

| 국서 | 위상 | 영토 방위 |
|------|------|-----------|
| 회장단 | 👑 황제국 | 정북 (월드 spawn에서 가장 가까움) |
| 사무총괄국 | 🛡️ 영주국 | 동 |
| 재정관리국 | 🛡️ 영주국 | 남동 |
| 대외협력국 | 🛡️ 영주국 | 남 |
| 미래전략실 | 🛡️ 영주국 | 남서 |
| 비서실 | 🛡️ 영주국 | 서 |
| 나눔복지국 | 🛡️ 영주국 | 북서 |
| 문화기획국 | 🛡️ 영주국 | 북 (회장단 너머) |
| 소통연결국 | 🛡️ 영주국 | 북동 |

> Towny 시스템상으로는 9개 동등 nation이지만, **봉건 위계는 룰북·Discord 권위로 강제**됩니다. 황제국 함락 시나리오(반란)도 SiegeWar로 가능 — 정치 다이내믹의 핵심 장치.

---

## 🗓️ 학기 일정 (8~10주)

| 주차 | 활동 |
|------|------|
| -2주 | 인프라 구축 (운영진) |
| -1주 | 학생 5명 베타 |
| 1주 | 정식 오픈 — 자국 정착 |
| 2~3주 | 빌드업 — 농사·자원·건설 |
| 4~5주 | 영토 확장 / 외교 |
| 6~7주 | 전쟁 빌드업 — 동맹·자원 비축 |
| 8주 | **선포 윈도우** |
| 9주 | **단 1회 SiegeWar 충돌** |
| 10주 | 결과 정리 + 후일담 |

---

## 🛠️ 도움 요청

- **접속이 안 돼요** → [troubleshooting.md](docs/troubleshooting.md) 먼저 확인 → 안 되면 [Issue 등록](../../issues/new/choose)
- **그리핑 신고** → Discord `#그리핑신고` 채널 (좌표·시간·증거)
- **룰 문의** → Discord `#질문` 채널

---

## 🔧 운영진용

서버 운영자(donghyun)는 별도 운영 가이드를 봅니다 — 이 저장소는 학생용입니다.

기술 스택:
- Paper 1.21.11 + OpenJDK 21 + Ubuntu 22.04
- Towny 0.102 + SiegeWar 3.3 (정치/전쟁)
- WorldGuard 7.0 + LuckPerms 5.5 + CoreProtect 23 (운영)
- EssentialsX 2.21 + PlaceholderAPI 2.12 (편의)
- Playit.gg TCP tunnel (외부 접속, 무료)

---

📅 작성: 2026-04-29 / 🤖 deep-interview → consensus plan → autopilot 파이프라인으로 셋업
