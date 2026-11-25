# ARVO 냉각 이어폰 앱 (프로토타입)

- `index.html` 한 파일에 화면·스타일·동작(HTML/CSS/JavaScript)이 모두 들어 있어요.
- `assets/` 폴더에는 Figma 시안에서 가져온 아이콘·이미지가 있어요.
- 실행: `index.html`을 브라우저로 열면 돼요. (또는 이 폴더에서 `npx serve` 후 접속)

## 구성
- 화면: 스플래시 · 홈(오토 모드/볼륨/냉각, 아래로 TODAY·RECENT RIDES·DEVICE) · AI(음성 입력, 채팅) · 지도(경로·안내) · 마이페이지(리포트·기기·공지·고객센터·설정)
- 테마: 흰색 기본, 설정 → 다크 모드
- 음성 입력: Lucian UX/UI Prompt #457 (MIT) 기반 — 실제 음성 인식 대신 예시 문장을 사용
- 데이터: 설정값만 브라우저 localStorage(`arvo-proto-v1`)에 저장, 채팅 기록은 저장하지 않음

## Claude Code에서 이어서 작업하기
이 폴더를 열고 예: "index.html의 AI 화면을 React 컴포넌트로 나눠줘", "실제 Web Speech API로 음성 인식 붙여줘"
