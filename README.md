# worktime2HIM

주간 근무시간 계산기 (iPhone 15 Pro Max · iPad Pro 12.9 5세대용 홈 화면 웹앱)

- 앱 주소: https://zkcmsp.github.io/worktime2HIM/
- 설치: Safari로 위 주소 열기 → 공유(□↑) → **홈 화면에 추가**

## 기능
- 이번 주 월~금 출근·퇴근 시간 선택, 연차(8시간) 처리
- 출근 12시 이전·퇴근 13시 이후면 점심 1시간 자동 공제
- 주 40시간 기준 달성률·초과 시간 표시
- 기록은 각 기기에만 저장 (기기끼리 공유되지 않음, 홈 화면 아이콘을 지우면 기록도 지워짐)
- 한 번 열면 인터넷 없이도 실행

## 파일
| 파일 | 내용 |
|---|---|
| `index.html` | 앱 본체 |
| `manifest.webmanifest`, `icon-*.png` | 홈 화면 앱 이름·아이콘 |
| `sw.js` | 오프라인 실행용 캐시 |
| `original/시간계산기.html` | 처음 만든 PC용 원본 |
| `screenshots/` | 화면 변경 전/후 비교 이미지 |
| `CLAUDE.md` | Claude Code 작업 안내 (대상 기기, 계산 규칙, 작업 방식) |
