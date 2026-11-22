# 작은 대장간 웹 시험판

Godot 4.7.2로 만든 개발 중 게임의 웹 빌드입니다 (소스 코드는 포함하지 않음).

- `claude/` — Claude안 웹 빌드
- `codex/` — Codex안 웹 빌드 (생기면)
- 글꼴: 나눔고딕, SIL Open Font License 1.1 (`OFL-NanumGothic.txt`)

## 다시 올리기 (PC)
1. 비교 폴더에서 내보내기: `Godot_v4.7.2-stable_win64_console.exe --headless --path <blacksmith-claude> --export-release "Web" "D:/GameProjects/blacksmith-web/claude/index.html"`
2. 이 폴더에서 `git add -A`, `git commit`, `git push` → 1~2분 뒤 GitHub Pages에 반영.
로컬 미리보기: `node serve.js` → http://localhost:8791/
