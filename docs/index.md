# 🎮 총학생회 포켓몬 도장깨기 서버

> 11개 도장(gym)을 도전하며 포켓몬을 잡고 챔피언에 도전하는 학생회 멀티플레이 서버.

## 🚀 빠른 접속

!!! tip "서버 주소"
    **`policies-untagged.gl.joinmc.link`** ← 마크 클라에서 이 한 줄을 그대로 붙여넣기

!!! warning "버전 / 모드 필수"
    **Java Edition 1.16.5 + Forge 1.16.5-36.2.39 + Pixelmon Reforged 9.1.13** 클라이언트 설치 필요. vanilla로는 접속 불가.

[자세한 설치 가이드 →](JOIN-GUIDE.md){ .md-button .md-button--primary }
[안 들어갈 때 →](troubleshooting.md){ .md-button }

## 📋 클라이언트 설치 6단계 요약

=== "1️⃣ MC 1.16.5 설치"
    Minecraft Launcher → 새 프로파일 → `release 1.16.5` 선택 → 한 번 실행해서 다운로드

=== "2️⃣ Forge 설치"
    https://files.minecraftforge.net/net/minecraftforge/forge/index_1.16.5.html → Installer 다운 → 더블클릭 → "Install client"

=== "3️⃣ Pixelmon mod"
    https://www.curseforge.com/minecraft/mc-mods/pixelmon (1.16.5 필터) → `Pixelmon-1.16.5-9.1.13-universal.jar` 다운

=== "4️⃣ mods/ 폴더"
    Mac: `~/Library/Application Support/minecraft/mods/` <br>
    Windows: `%appdata%\.minecraft\mods\` <br>
    여기에 jar 복사

=== "5️⃣ Forge 프로파일 실행"
    Launcher → "Forge 1.16.5" 프로파일 선택 → PLAY

=== "6️⃣ 서버 접속"
    멀티플레이 → 서버 추가 → `policies-untagged.gl.joinmc.link`

## 🏛️ 게임 컨셉

| 요소 | 설명 |
|------|------|
| **Region** | 맵에 분산된 여러 region — 각자 특정 포켓몬 spawn |
| **11 도장** | 운영진/학생 도장관 보유 — 배틀 승리 시 배지 |
| **챔피언** | 11 배지 모두 모으면 회장단(챔피언) 도전권 |
| **트레이너** | 맵 NPC들과 배틀해서 EXP/돈 |

!!! note "도장 깨기 룰"
    상세 룰은 [RULEBOOK.md](RULEBOOK.md) 참조. 친선·정식 배틀 구분, 그리핑 처벌, 챔피언 토너먼트 등.

## 🗓️ 학기 일정

| 주차 | 활동 |
|------|------|
| 1주 | 정식 오픈 — 시작 마을 + 첫 포켓몬 1마리 |
| 2~3주 | 1~3번 도장 도전 |
| 4~5주 | 중급 도장 + 트레이너 배틀 |
| 6~7주 | 상급 도장 + 전설 포켓몬 |
| 8~9주 | 11 배지 → 챔피언 도전권 |
| 10주 | **챔피언 토너먼트** |

## 🛠️ 도움 요청

- 모드 설치 / 접속 문제 → [troubleshooting.md](troubleshooting.md) → [Issue 등록](https://github.com/BiQnT/mc-totak/issues/new/choose)
- Discord `#질문` / `#그리핑신고`

## 🔧 기술 스택 (운영진용)

- 서버: Minecraft Forge 36.2.39 (MC 1.16.5)
- 모드: Pixelmon Reforged 9.1.13
- 호스트: i7-8700 / 16GB RAM / Ubuntu 22.04
- Java 8
- 외부 접속: Playit.gg TCP tunnel (무료)

---

📅 첫 오픈: 2026-04-30
