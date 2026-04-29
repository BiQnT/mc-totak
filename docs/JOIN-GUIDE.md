# 🎮 총학생회 포켓몬 도장깨기 서버 — 클라이언트 설치 가이드

vanilla 마크와 다르게 **NeoForge + Pixelmon mod 설치**가 필요합니다. 한 번만 설치하면 끝. 약 15분 소요.

## 0단계 — 준비물 체크리스트
- [ ] PC (Windows / macOS / Linux)
- [ ] **Minecraft Java Edition 라이센스** + Microsoft 계정
- [ ] Java 21 설치된 환경 (Minecraft Launcher가 자동 설치, 직접 설치 시 https://adoptium.net/)
- [ ] 인터넷 연결 (모드 ~150MB 다운)
- [ ] 운영진에게 본인 Minecraft 닉네임 전달 → 화이트리스트 등록 받기

> ⚠️ Bedrock Edition (모바일·콘솔)은 **불가** — Pixelmon은 Java Edition 전용.

## 1단계 — Minecraft Java Edition 1.21.1 설치

1. https://www.minecraft.net/download → Launcher 다운
2. Microsoft 계정 로그인 → Java Edition 탭
3. 좌측 **"설치"** → "새로 설치" → 버전 선택: **release 1.21.1** → 새 프로파일 만들기
4. 한 번 실행해서 1.21.1 다운로드 완료 확인 → 메인 메뉴에서 종료

## 2단계 — NeoForge 1.21.1 설치

1. https://neoforged.net/ 접속
2. **Downloads** → MC 1.21.1 → `21.1.228` 또는 latest 21.1.x
3. **Installer (Recommended)** 클릭 → `neoforge-21.1.228-installer.jar` 다운
4. 다운된 jar 더블클릭 (또는 우클릭 "Open With Java")
5. 설치 창에서 **"Install client"** 선택 → OK
6. 성공 메시지 → 닫기

설치 직후 Minecraft Launcher의 프로파일 목록에 **"NeoForge 1.21.1-21.1.228"** 자동 추가됨.

## 3단계 — Pixelmon mod 다운로드

1. https://www.curseforge.com/minecraft/mc-mods/pixelmon 접속
2. **"Files"** 탭 → 좌측 필터: **Game Version → 1.21.1** 선택 → Mod Loader → **NeoForge**
3. 최신 파일 (예: `Pixelmon-1.21.1-9.3.14-universal.jar`) 클릭
4. 우측 **"Download File"** → 다운로드

## 4단계 — mods 폴더에 jar 복사

각 OS별 mods 폴더 위치:

=== "Windows"
    1. `Win + R` → `%appdata%\.minecraft\mods\` 입력 → Enter (폴더 없으면 만들기)
    2. 다운받은 `Pixelmon-1.21.1-9.3.14-universal.jar`을 이 폴더에 그대로 복사

=== "Mac"
    1. Finder → `Cmd + Shift + G` → `~/Library/Application Support/minecraft/mods/` 입력 → Enter (폴더 없으면 만들기)
    2. jar을 폴더에 복사

=== "Linux"
    1. `~/.minecraft/mods/` 열기 (없으면 만들기)
    2. jar 복사

## 5단계 — NeoForge 프로파일로 실행

1. Minecraft Launcher 실행
2. 좌측 **"설치"** → **"NeoForge 1.21.1-21.1.228"** 프로파일 찾기
3. 우측 **▶ 재생** 클릭 → 첫 실행 시 모드 로딩 (1~2분)
4. 메인 메뉴에 **"Mods"** 버튼 + **Pixelmon 9.3.14** 아이콘 보이면 정상

## 6단계 — 서버 접속

1. **멀티플레이** 클릭
2. **서버 추가** → 서버 이름: `포켓몬 서버`, 서버 주소: `policies-untagged.gl.joinmc.link`
3. **완료** → 서버 박스 더블클릭 → 입장
4. 첫 접속 시: 시작 마을 spawn에 도착. 채팅창(`T`)에서 다음 명령 시도:
   ```
   /pokegive <포켓몬명>     ← 운영진이 첫 포켓몬 1마리 부여
   /pokebattle <상대>       ← 다른 학생과 배틀
   ```

## 7단계 — 화이트리스트 등록 확인

서버 측에서 운영진이 본인 닉네임을 사전 등록해야 입장 가능. 등록 안 됐을 때:
```
You are not white-listed on this server!
```
→ Discord에서 운영진에게 닉네임 전달 → 등록 후 재시도.

---

## 🎮 자주 쓰는 명령어 (서버 인게임)

| 명령어 | 설명 |
|--------|------|
| `/party` | 본인 포켓몬 파티 보기 |
| `/pc` | PC 박스 (보관함) |
| `/pokebattle <상대>` | 상대와 포켓몬 배틀 신청 |
| `/dexcheck` | 본인 포켓몬 도감 진행률 |
| `/spawning` | 현재 위치 spawn 가능한 포켓몬 종류 |
| `/struc list` | 가까운 구조물 (gym, 마을 등) |

---

## 🏆 도장 도전 흐름

1. 시작 마을에서 **첫 포켓몬 선택** (운영진/NPC)
2. 야생 포켓몬 잡으며 레벨업
3. 첫 번째 도장 (1번) 도착 → 도장관과 배틀 → 승리 시 **배지 1개**
4. 다음 도장 도전 가능 → 11 배지 모두 모으면 챔피언 도전권
5. 챔피언 = 회장단 (운영진 NPC) → 우승 시 **마스터볼** 획득

자세한 룰: [RULEBOOK.md](RULEBOOK.md)

---

## 🐛 막혔다면

- 모드 설치 단계: [troubleshooting.md](troubleshooting.md)
- 그래도 안 되면: [GitHub Issue 등록](https://github.com/BiQnT/mc-totak/issues/new/choose)

24시간 이내 운영진 회신 목표.
