# Mini Games Collection

브라우저에서 바로 즐길 수 있는 미니 게임 5종 모음. 별도 빌드·서버 없이 HTML 파일만 열면 동작합니다.

**🎮 라이브 데모:** https://frescabreeze.github.io/mini-games-collection/

## 게임 목록

| 게임 | 장르 | 조작 |
|------|------|------|
| 💣 지뢰찾기 | 논리 | 마우스 (좌클릭: 열기, 우클릭: 깃발) |
| ⭕ 틱택토 | 전략 | 마우스 · 2인 또는 vs 컴퓨터 |
| 🔢 2048 | 퍼즐 | 방향키 |
| 🐍 스네이크 | 아케이드 | 방향키, Space(일시정지) |
| 🧠 메모리 카드 | 기억 | 마우스 |

## 실행

`index.html`을 브라우저로 열면 홈에서 각 게임을 선택할 수 있습니다.

## 구조

```
.
├── index.html         # 홈 (게임 카드 그리드)
├── assets/style.css   # 공통 다크 테마
├── minesweeper.html
├── tictactoe.html
├── 2048.html
├── snake.html
└── memory.html
```

공통 레이아웃·팔레트는 `assets/style.css` 한 곳에서 관리하며, 각 게임은 별도 HTML로 독립 실행됩니다.
