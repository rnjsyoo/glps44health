
# 보건실 재실 현황 (독립 사이트) · Sick Bay Status

메인 인트라넷과 **같은 구글폼/시트**를 읽는 큰 화면 전용 페이지입니다.
모니터·태블릿에 띄워두면 지금 보건실에 누가 있는지 한눈에 보입니다.

- 데이터: 보건실 재실 구글폼 응답 시트 (자동 새로고침 1분)
- 영문명·반: 학생 DB 시트에서 자동
- 재실 시간이 끝나면 자동으로 사라짐 / 퇴실 버튼(그 기기 로컬)
- 한 블록 = 1줄 한국어 + 2줄 영어 (외국인 선생님용)

## 배포 방법 (둘 중 하나)

### A. 기존 저장소에 폴더로 추가 — 가장 간단
1. 기존 GLPS44 저장소(예: rnjsyoo.github.io/GLPS44)에 `health` 폴더를 만들고
   이 폴더의 `index.html`을 넣습니다.
2. 커밋/푸시하면 끝: **https://rnjsyoo.github.io/GLPS44/health/**

### B. 새 저장소로 (완전 별도 주소)
1. GitHub에서 새 저장소 생성 (예: `glps44-health`).
2. 이 `index.html`을 업로드 → Settings → Pages → Branch: main / root 저장.
3. 몇 분 뒤: **https://<아이디>.github.io/glps44-health/**

## 설정 변경
`index.html` 상단 `CONFIG`에서 시트/폼 주소를 바꿀 수 있습니다.
(현재 값은 메인 인트라넷과 동일하게 맞춰져 있습니다.)
