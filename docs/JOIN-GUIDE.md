# 📥 서버 접속 가이드 (학생용)

처음 마인크래프트 서버에 접속하시는 분도 따라할 수 있도록 단계별로 안내합니다. 약 5분 소요.

## 0단계 — 준비물 체크리스트
- [ ] PC (Windows / macOS / Linux 모두 OK)
- [ ] **Minecraft Java Edition 라이센스** (학생 라이센스 또는 본인 라이센스)
- [ ] Microsoft 계정 (게임 로그인용)
- [ ] 운영진에게 본인 Minecraft 닉네임 전달 → 화이트리스트 등록 받기

> ⚠️ **Bedrock Edition (모바일·콘솔용)은 접속 불가**합니다. PC용 Java Edition만 가능합니다. iPad·스마트폰·Xbox·PS로 산 마크는 사용 못 함을 다시 확인.

## 1단계 — Minecraft Java Edition 설치

1. https://www.minecraft.net/download 접속
2. 본인 OS 선택 (Windows/Mac/Linux)
3. **Minecraft Launcher** 다운로드 후 실행
4. Microsoft 계정으로 로그인
5. 런처가 **Java Edition** 탭에서 자동으로 1.21.x 설치 시작

> 처음 한번만 설치하면 됩니다. 이후 게임 업데이트도 런처가 자동 처리.

## 2단계 — 서버 추가

1. Minecraft 실행 (런처에서 **재생** 클릭)
2. 메인 화면 → **멀티플레이** 클릭
3. **서버 추가** 버튼 클릭
4. 정보 입력:
   - **서버 이름**: `총학생회 서버` (자유롭게)
   - **서버 주소**: `policies-untagged.gl.joinmc.link` (이 한 줄을 그대로 붙여넣기)
5. **완료** 클릭

서버 목록에 추가되면 회색 박스로 보이며 핑이 표시됩니다.

## 3단계 — 접속

서버 박스를 더블클릭 또는 선택 후 **서버 입장** 클릭.

성공 시: 게임 안으로 들어가서 spawn 좌표(0, 64, 0) 근처에 떨어집니다.

## 4단계 — 첫 명령어로 확인

게임 안에서 채팅창(`T` 키)을 열고 다음 명령어 입력:

```
/n list
```

9개 국서 목록이 나오면 **정상 접속 + 화이트리스트 OK**.

## 5단계 — 자국 가입 / 자국 생성

### 일반 학생 (자국에 가입)
본인이 속한 국서를 확인하세요. 다음 중 하나입니다:
- 사무총괄국 / 재정관리국 / 대외협력국 / 미래전략실 / 비서실 / 나눔복지국 / 문화기획국 / 소통연결국 / 회장단

해당 국서의 **leader**에게 가입 요청:
1. Discord `#가입요청` 채널 또는 게임 내 `/msg <leader닉네임> 가입 요청합니다`
2. leader가 `/t add <본인닉네임>` 으로 추가 후 안내
3. `/t spawn <자국이름>` 으로 자국 거점 텔레포트 가능

### 국서별 첫 leader (자국 생성)
8 영주국의 leader는 본인이 직접 town/nation을 만듭니다 (Towny 룰: 1 player = 1 town mayor).

```
/mvtp world           ← 메인 월드 이동 (kingdom = 마켓, 영토는 main world)
/tp <x> 100 <z>       ← 본인 국서 좌표 (위 nation-map 표 참조)
/town new <국서이름>   ← town 생성, 본인이 mayor
/nation new <국서약자> <국서이름>  ← (예: /nation new 사무총괄 사무총괄국)
/town claim           ← 청크 점유 (반복으로 영토 확장)
/town set spawn       ← 거점 spawn 위치 설정
```

회장단(황제국)은 운영진이 이미 사전 생성됨 (BLOODAYS = mayor, 좌표 정북).

## 자주 쓰는 명령어

| 명령어 | 설명 |
|--------|------|
| `/home set <이름>` | 거점 위치 저장 (최대 3개) |
| `/home <이름>` | 저장된 거점으로 텔레포트 |
| `/tpa <상대>` | 상대에게 텔레포트 요청 |
| `/msg <상대> <내용>` | 1:1 귓속말 |
| `/n online` | 자국 접속자 보기 |
| `/n list` | 9개 국서 목록 |
| `/t spawn <town>` | 특정 국서 거점 이동 |
| `/co i` | 그리핑 신고용 조사 모드 (자국에서) |

## 안 들어갈 때
[troubleshooting.md](troubleshooting.md) 참조.

## 룰북 필독
첫 접속 후 [RULEBOOK.md](RULEBOOK.md) 한 번 읽으세요. 그리핑·전쟁·황제권한 등 룰을 모르면 페널티 가능.

## 6단계 — (선택) Conquest 리소스팩 — 수동 설치

중세 사실적 비주얼을 원하면 Conquest 리소스팩을 본인 PC에 직접 설치하세요. 서버는 강제 안 함 — 깔고 싶은 사람만.

### Conquest 다운로드
🔗 https://modrinth.com/resourcepack/conquest_/version/1.21.11

위 페이지에서 `Conquest_1.21.11.zip` (266MB) 다운.

### 설치

=== "Windows"
    1. `Win + R` → `%appdata%\.minecraft\resourcepacks\` 입력 → 폴더 열기
    2. 다운로드한 zip 파일을 그대로 폴더에 복사 (압축 풀지 X)
    3. 마인크래프트 실행 → 옵션 → 리소스팩 → "Conquest" 활성화 → 완료

=== "Mac"
    1. Finder → `Cmd + Shift + G` → `~/Library/Application Support/minecraft/resourcepacks/` 입력
    2. 다운로드한 zip 파일을 그대로 폴더에 복사 (압축 풀지 X)
    3. 마인크래프트 실행 → 옵션 → 리소스팩 → "Conquest" 활성화 → 완료

=== "Linux"
    1. `~/.minecraft/resourcepacks/` 열기
    2. 다운로드한 zip 그대로 복사
    3. 마인크래프트 옵션 → 리소스팩 → 활성화

### Conquest 사용 권장 사항
- **Optifine** 또는 **Iris** 모드 함께 사용 시 비주얼 더 풍부
- 다운 안 해도 게임 플레이 동일 (vanilla 비주얼)

## 7단계 — (선택) OptiFine + 셰이더

더 화려한 비주얼을 원한다면 **OptiFine** + **Iris** 모드 + 셰이더 팩(Complementary, BSL, Sildur's 등) 설치. 모두 클라이언트 측이라 서버에 영향 없음.

OptiFine 다운: https://optifine.net/downloads (마크 1.21.x용)
셰이더팩 다운: https://www.curseforge.com/minecraft/shaders

## 💰 경제 시스템 (NEW)

서버에 12개 직업이 있어 광산질·농사·낚시·사냥 등으로 **에메랄드** 화폐를 적립할 수 있습니다.

```
/jobs browse       → 직업 12개 목록 (광부, 농부, 사냥꾼, 어부, 건축가, 나무꾼, ...)
/jobs join 광부     → 광부 직업 가입 (한 명이 여러 직업 가입 가능)
/jobs info 광부     → 광부가 어떤 활동에서 얼마 버는지 확인
/balance           → 본인 잔고
/pay <상대> <금액>   → 송금
/qs help           → 상점(QuickShop) 만들기 가이드
```

**Slimefun**: `/sf guide` 로 가이드북 받으면 다이아 너머의 자원·아이템 (다마스쿠스 강철, 카보나도, 제트팩 등) 제작 가능.
