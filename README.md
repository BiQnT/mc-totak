# 🎮 총학생회 포켓몬 도장깨기 서버

> 11개 도장(gym)을 도전하며 포켓몬을 잡고 챔피언에 도전하는 학생회 멀티플레이 서버.

[![Status](https://img.shields.io/badge/status-v1%20%EC%9A%B4%EC%98%81%EC%A4%91-success)](#)
[![Edition](https://img.shields.io/badge/edition-Java%201.16.5-blue)](https://www.minecraft.net/download)
[![Mod](https://img.shields.io/badge/mod-Pixelmon%20Reforged%209.1.13-yellow)](https://www.curseforge.com/minecraft/mc-mods/pixelmon)
[![Loader](https://img.shields.io/badge/loader-Forge%2036.2.39-orange)](https://files.minecraftforge.net)
[![License](https://img.shields.io/badge/docs-CC--BY--SA--4.0-lightgrey)](LICENSE)

## 🚀 빠른 접속 정보

| 정보 | 값 |
|------|-----|
| **서버 주소** | **`policies-untagged.gl.joinmc.link`** |
| **마크 버전** | **Java Edition 1.16.5** ⚠️ (모드 호환을 위해 정확한 버전 필요) |
| **모드 로더** | **Minecraft Forge 36.2.39** (1.16.5용) |
| **모드** | **Pixelmon Reforged 9.1.13** (1.16.5 클래식 버전, 11 gym 맵 호환) |
| **모드** | 화이트리스트 ON — 운영진 사전 등록 필요 |

⚠️ **vanilla로는 접속 불가** — Forge 1.16.5 + Pixelmon Reforged jar을 클라이언트에 설치해야 입장 가능.

[자세한 클라 설치 가이드 →](docs/JOIN-GUIDE.md)

---

## 📖 자세한 가이드

| 문서 | 내용 |
|------|------|
| [JOIN-GUIDE.md](docs/JOIN-GUIDE.md) | Forge + Pixelmon Reforged 클라 설치 + 서버 접속 (15분 1회) |
| [RULEBOOK.md](docs/RULEBOOK.md) | 도장깨기 룰 — 11 gym, 챔피언 도전, 그리핑 처벌 |
| [FAQ.md](docs/FAQ.md) | 자주 묻는 질문 |
| [troubleshooting.md](docs/troubleshooting.md) | 모드 안 깔릴 때 / 접속 안 될 때 |

---

## 🎯 게임 컨셉

| 요소 | 설명 |
|------|------|
| **Region** | 맵 안 여러 region — 각 region마다 특정 포켓몬 spawn |
| **11 도장** | 운영진 또는 학생 도장관이 관리. 도전자 → 도장관 배틀 → 승리 시 배지 |
| **챔피언 (회장단)** | 11 배지 모두 모은 도전자만 챔피언 도전 가능 |
| **트레이너 NPC** | 맵 곳곳에 NPC 트레이너. 배틀 → 경험치/돈 |
| **포켓볼·아이템** | 자연 spawn + 상점 구매. 마스터볼은 챔피언 보상 |

---

## 🗓️ 운영 일정

| 주차 | 활동 |
|------|------|
| 1주 | 정식 오픈 — 시작 마을 + 자기 포켓몬 1마리 선택 |
| 2~3주 | 첫 번째~세 번째 도장 도전 |
| 4~5주 | 중급 도장 + 트레이너 배틀 |
| 6~7주 | 상급 도장 + 전설 포켓몬 도전 |
| 8~9주 | 11 배지 수집 → 챔피언 도전권 |
| 10주 | **챔피언 토너먼트** — 우승자 발표 |

---

## 🛠️ 도움 요청

- **모드 설치 막힘** → [JOIN-GUIDE](docs/JOIN-GUIDE.md) + [troubleshooting](docs/troubleshooting.md) → 안 풀리면 [Issue 등록](../../issues/new/choose)
- **포켓몬 룰 문의** → Discord `#질문` 채널
- **그리핑 신고** → Discord `#그리핑신고` 채널 (좌표·시간·증거)

---

## 🎨 비주얼 (선택)

- **OptiFine 1.16.5**: Forge와 호환되는 셰이더 모드. https://optifine.net/downloads 에서 1.16.5 H7 (또는 latest) 다운 → mods/ 에 추가
- **셰이더팩**: BSL, Complementary, Sildur's 등 — OptiFine과 함께 사용

---

## 🔧 기술 스택 (운영진용)

- 호스트: i7-8700 + 16GB RAM + Ubuntu 22.04
- 서버 소프트웨어: Minecraft Forge 36.2.39 (MC 1.16.5)
- 모드: Pixelmon Reforged 9.1.13
- Java 8 (Forge 1.16.5 표준)
- 외부 접속: Playit.gg TCP tunnel (무료)
- systemd unit: `mc-pokemon.service`
- 자동 백업: 04:00 KST 일일

---

📅 첫 오픈: 2026-04-30 / 🤖 deep-interview → consensus plan → autopilot → Pokemon pivot
