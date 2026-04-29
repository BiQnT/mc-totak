# 🔧 접속이 안 될 때 — 트러블슈팅

증상별로 체크 항목을 정리했습니다. 위에서부터 차례대로 확인하세요.

## ❌ "Not whitelisted on this server"
**의미**: 화이트리스트에 등록 안 된 닉네임으로 접속 시도.
**해결**:
1. 본인 Minecraft 닉네임 정확히 확인 (대소문자 구분)
2. 운영진에게 닉네임 전달 + 화이트리스트 등록 요청
3. 등록 후 다시 접속

## ❌ "Outdated client" / "Outdated server"
**의미**: 클라이언트 Minecraft 버전과 서버(1.21.x) 버전이 다름.
**해결**:
1. Minecraft 런처 → **재생** 옆 ▼ → "최신 출시" 선택해서 1.21.x 자동 사용
2. 다른 버전 프로파일 선택 중이면 1.21.x 프로파일 새로 만들기

## ❌ "Failed to verify username" / "Bad login"
**의미**: 정품 인증 실패.
**해결**:
1. Minecraft 런처에서 다시 로그인
2. Microsoft 계정 비밀번호 변경 직후라면 잠시 후 재시도
3. 정품 라이센스 보유 확인 (https://account.mojang.com)

## ❌ "Connection timed out"
**의미**: 서버에 도달 못함.
**해결**:
1. 서버 주소 오타 확인
2. 본인 인터넷 연결 확인 (다른 사이트 잘 되는지)
3. Discord에서 운영진이 서버 다운 공지했는지 확인
4. 회사·학교·기숙사 방화벽이 차단할 가능성 — 다른 네트워크에서 시도

## ❌ "Connection refused"
**의미**: 서버 자체가 응답 안 함 (다운 가능성).
**해결**:
1. Discord `#서버상태` 또는 `#공지` 채널 확인
2. 운영진에게 신고 (Discord 운영진 멘션)

## ❌ Minecraft가 검은 화면 / 멈춤
**의미**: 클라이언트 문제.
**해결**:
1. Minecraft 종료 후 재시작
2. PC 재부팅
3. 그래픽 드라이버 업데이트 (NVIDIA Geforce Experience / AMD Radeon Software)
4. Java 버전 충돌 — 런처가 자체 Java 사용하니 보통 문제 없음

## ❌ 접속은 되는데 `/n list`가 안 나옴
**의미**: 권한 부족 또는 플러그인 미로드.
**해결**:
1. 잠시 후 다시 시도 (서버 시작 직후 플러그인 로딩 중일 수 있음)
2. 그래도 안 되면 운영진 호출 — 권한 그룹 미할당 가능성

## ❌ Bedrock Edition으로 산 마크
**의미**: 모바일/콘솔용 Minecraft 라이센스로는 본 서버 접속 불가.
**해결**:
1. PC용 Java Edition을 따로 구매해야 함 (~33,000원)
2. 일부 라이센스는 "Minecraft for Windows" 묶음에 Java + Bedrock 같이 있음 — 확인 필요

## ❌ Bedrock Edition + Java Edition 둘 다 산 경우
**해결**: Minecraft 런처에서 **Java Edition** 탭으로 전환하여 실행.

## 🐛 그래도 안 되면

다음 정보를 모아서 [Issue 등록](../../issues/new?template=connection_help.md):
- 본인 OS (Windows / Mac / Linux + 버전)
- Minecraft 런처 버전
- Minecraft 클라 버전
- 정확한 오류 메시지 (스크린샷 권장)
- 시도한 시간 + 네트워크 환경
- 본인 닉네임 (화이트리스트 확인용)

운영진이 24시간 이내 회신 목표.

## 운영진 빠른 연락
- Discord `#운영진호출` (긴급)
- Discord `#질문` (일반)
- GitHub Issue (기록 남김 — 권장)
