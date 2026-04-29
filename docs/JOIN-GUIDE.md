# 🎮 총학생회 포켓몬 도장깨기 서버 — 클라이언트 설치 가이드

vanilla 마크와 다르게 **Forge 1.16.5 + Pixelmon Reforged 9.1.13 mod 설치**가 필요합니다. 한 번만 설치하면 끝. 약 15분 소요.

## 0단계 — 준비물 체크리스트
- [ ] PC (Windows / macOS / Linux)
- [ ] **Minecraft Java Edition 라이센스** + Microsoft 계정
- [ ] Java 8 환경 (Minecraft Launcher가 자동 처리, 직접 설치 시 https://adoptium.net/)
- [ ] 인터넷 연결 (모드 ~430MB 다운)
- [ ] 운영진에게 본인 Minecraft 닉네임 전달 → 화이트리스트 등록 받기

> ⚠️ Bedrock Edition (모바일·콘솔)은 **불가** — Pixelmon은 Java Edition 전용.

## 1단계 — Minecraft Java Edition 1.16.5 설치

1. https://www.minecraft.net/download → Launcher 다운
2. Microsoft 계정 로그인 → Java Edition 탭
3. 좌측 **"설치"** → "새로 설치" → 버전: **release 1.16.5** → 새 프로파일 만들기
4. 한 번 실행해서 1.16.5 다운로드 확인 → 메인 메뉴에서 종료

## 2단계 — Forge 1.16.5 설치

1. https://files.minecraftforge.net/net/minecraftforge/forge/index_1.16.5.html 접속
2. 페이지 위쪽 **"Download Recommended"** → `Installer` 클릭 (광고 1번 거치고 SKIP 후 다운)
3. 받은 `forge-1.16.5-36.2.39-installer.jar` 더블클릭
4. 설치 창 → **"Install client"** 선택 → OK
5. 성공 메시지 → 닫기

설치 후 Minecraft Launcher 재실행 시 프로파일에 **"forge 1.16.5"** 또는 **"forge-1.16.5-36.2.39"** 자동 추가됨.

## 3단계 — Pixelmon Reforged 9.1.13 다운로드

1. https://www.curseforge.com/minecraft/mc-mods/pixelmon/files/all?filter-game-version=2474
   (위 URL 그대로 들어가면 1.16.5 호환 파일만 표시됨)
2. 목록에서 최신 9.1.x 파일 (예: `Pixelmon-1.16.5-9.1.13-universal.jar`) 클릭
3. 우측 **"Download File"** → 다운로드 (~430MB)

또는 https://reforged.gg → Files → 1.16.5 필터.

## 4단계 — mods 폴더에 jar 복사

=== "Windows"
    1. `Win + R` → `%appdata%\.minecraft\mods\` (없으면 새 폴더)
    2. 다운받은 `Pixelmon-1.16.5-9.1.13-universal.jar` 복사

=== "Mac"
    1. Finder → `Cmd + Shift + G` → `~/Library/Application Support/minecraft/mods/`
    2. jar 복사

=== "Linux"
    1. `~/.minecraft/mods/` 열기
    2. jar 복사

## 5단계 — Forge 프로파일로 실행

1. Minecraft Launcher 실행
2. 좌측 **"Play"** 또는 **"재생"** → 하단 드롭다운 ▼ 클릭
3. **"forge 1.16.5"** 또는 **"release 1.16.5-forge..."** 선택
4. **PLAY** 클릭 → 첫 실행 시 모드 로딩 (1~2분)
5. 메인 메뉴 좌하단에 **"Pixelmon"** 아이콘 / "Mods" 버튼 → Pixelmon Reforged 9.1.13 활성 확인

## 6단계 — 서버 접속

1. **멀티플레이** → **서버 추가**
2. 서버 이름: `포켓몬 서버`, 서버 주소: `policies-untagged.gl.joinmc.link`
3. **완료** → 서버 박스 더블클릭 → 입장
4. 첫 접속 시 시작 마을 spawn에 도착. 채팅창 `T` 키:
   ```
   /pokegive <포켓몬명>     ← 운영진이 첫 포켓몬 부여
   /pokebattle <상대>       ← 다른 학생과 배틀
   ```

## 7단계 — 화이트리스트 등록 확인

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
| `/spawning` | 현재 위치 spawn 가능한 포켓몬 |
| `/struc list` | 가까운 구조물 (gym, 마을 등) |

---

## 🏆 도장 도전 흐름

1. 시작 마을에서 첫 포켓몬 선택
2. 야생 포켓몬 잡고 레벨업
3. 1번 도장 → 도장관 배틀 → 승리 시 배지 1개
4. 11 배지 모이면 챔피언 도전권
5. 챔피언 = 회장단 → 우승 시 **마스터볼**

---

## 🐛 안 되면

- 모드 설치 단계: [troubleshooting.md](troubleshooting.md)
- [GitHub Issue 등록](https://github.com/BiQnT/mc-totak/issues/new/choose)

24시간 이내 회신 목표.
