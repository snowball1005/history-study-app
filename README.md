# 중2 역사 탐험 연구소

동아출판 역사② 1~4단원 흐름과 4단원 8일 기말 대비 학습 앱. 정적 웹사이트라 별도 서버나 로그인 없이 동작합니다.

## 실행
`index.html`을 열면 됩니다. 웹 배포 시 `index.html`과 `content.js`를 같은 디렉터리에 올리세요.

## 기능
- 시대별 연표와 인과관계 흐름도
- 8개 소단원별 상세 개념, 암기 카드, 객관식, 서술형과 모범 답안
- 시험 범위 조정, 오답 복습, 학습 기록 저장, 기록 백업

## GitHub → Render 배포
1. 새 **공개 GitHub 저장소**를 만들고 이 디렉터리의 파일을 저장소 루트에 업로드합니다.
2. Render → New → Static Site → GitHub 저장소 연결.
3. Build Command: `echo ready` / Publish Directory: `.` 설정.
4. Auto-Deploy: `On Commit` 설정. 정적 사이트 URL을 공유하면 로그인 없이 접속 가능합니다.
5. 수정 사항은 GitHub에 커밋하면 Render가 자동으로 다시 배포합니다.

## 학습 내용 수정
- `content.js`: `data`(객관식·용어·간단한 흐름), `supplement`(설명·서술형), `periods`(연표), `causes`(마인드맵).
- 새로운 시험 범위는 앱 안의 `시험 범위`에서 선택합니다.

주의: `localStorage` 학습 진도는 각 브라우저 기기별로 별도 보관되며 자동 동기화되지 않습니다. 서버 저장·공유 학습 기록 기능은 포함하지 않습니다.
