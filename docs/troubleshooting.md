# 🔧 접속 / 모드 트러블슈팅

## ❌ "Failed to load Pixelmon" / 모드 로딩 실패
- Java 21 사용 중 확인 (Launcher 자동 처리)
- NeoForge 1.21.1-21.1.x 정확한 버전 사용 (1.21.0이나 1.21.4 X)
- Pixelmon jar이 정확히 1.21.1 버전인지 (`Pixelmon-1.21.1-9.x.x-universal.jar`)
- mods 폴더에 다른 모드와 충돌 가능성 — 일단 Pixelmon 외 다른 모드 다 빼고 시도

## ❌ "Outdated client" / "Outdated server"
- 클라이언트 1.21.1 정확히 (1.21.0, 1.21.4 등 X)

## ❌ "You are not white-listed"
- 본인 닉네임 정확히 운영진에 전달 (대소문자 구분)
- 운영진 등록 후 재시도

## ❌ "Connection timed out"
- 서버 주소 오타 확인: `policies-untagged.gl.joinmc.link`
- 본인 인터넷 연결 확인
- Discord에 서버 다운 공지 확인

## ❌ "Internal server error" 또는 즉시 끊김
- Pixelmon 버전 mismatch 가능성 (서버 9.3.x ≠ 클라 9.3.x)
- 서버에 무엇을 사용 중인지: `Pixelmon 9.3.14`
- 클라이언트도 동일 버전 9.3.14 또는 9.3.x로 맞추기

## ❌ NeoForge installer 실행 안 됨
- 다운된 jar이 실제 jar인지 확인 (브라우저가 zip으로 변경 안 했나)
- 우클릭 "Open With" → Java 21 선택
- 또는 명령줄: `java -jar neoforge-21.1.228-installer.jar`

## ❌ Mac에서 모드 잘 안 됨
- ~/Library/Application Support/minecraft/mods/ 정확한 경로
- Finder → Cmd+Shift+G → 경로 입력
- 폴더 없으면 새로 만들기

## ❌ Pixelmon 메뉴/UI 안 보임
- F3 디버그 화면에서 "FML" 표시 확인 (NeoForge가 로드되었는지)
- Mods 메뉴에서 Pixelmon 활성 상태 확인

## ❌ 그래도 안 되면
- 본인 OS, MC 버전, NeoForge 버전, Pixelmon jar 파일명 + 정확한 오류 메시지를
- [GitHub Issue 등록](https://github.com/BiQnT/mc-totak/issues/new?template=connection_help.md)

24h 이내 회신 목표.
