# Unity Game Portfolio

Unity와 C#으로 만든 2D 게임 결과물을 Windows Release 빌드와 구현 문서로 정리한 포트폴리오입니다.

![VamGame cover](docs/assets/vamgame-cover.png)

## Problem / 문제

- Unity 프로젝트는 시간이 지나면 빌드 파일, Unity package, 에셋, 문서가 섞이기 쉽습니다.
- GitHub 언어 통계에는 Unity가 아니라 C# 중심으로 표시되기 때문에 게임 개발 경험을 README에서 명확히 설명해야 합니다.
- 실행 가능한 결과물과 구현 포인트를 분리해 보여줄 필요가 있습니다.

## Solution / 해결 방법

- 게임별 폴더를 분리했습니다.
- Windows 실행 빌드와 상세 문서를 함께 제공합니다.
- `VamGame`은 Unity package와 구현 포인트를 문서화했습니다.
- `subakgame`은 보관된 Windows 실행 빌드 중심으로 정리했습니다.

## Tech Stack / 기술 스택

| Area | Stack |
| --- | --- |
| Engine | Unity |
| Language | C# |
| Build target | Windows |
| Game type | 2D action, survival, casual game |
| Documentation | Markdown |

## Skills / 구현 역량

- Unity C# 2D 게임 개발
- 플레이어 이동과 생존 처리
- 적 스폰과 추적
- 무기와 총알 처리
- 아이템 및 장비 시스템
- 레벨업과 HUD 구성
- 오브젝트 풀링 기반 생성 관리
- Windows 실행 빌드 정리
- 게임별 README와 문서 작성

## Project Gallery / 프로젝트 갤러리

| VamGame | subakgame |
| --- | --- |
| ![VamGame cover](docs/assets/vamgame-cover.png) | ![subakgame cover](docs/assets/subakgame-cover.png) |
| 2D 생존 액션 게임 | Windows 실행 빌드 |
| [상세 문서](docs/vamgame.md) | [상세 문서](docs/subakgame.md) |

## Included Projects / 포함 프로젝트

| Project | Genre | Build | Detail | Main Points |
| --- | --- | --- | --- | --- |
| VamGame | 2D action survival | [Windows ZIP](https://github.com/jiyoon99/unity-game-portfolio/releases/download/builds-2026.06/vamgame-windows.zip) | [docs/vamgame.md](docs/vamgame.md) | 플레이어 성장, 적 스폰, 무기/아이템, 오브젝트 풀링 |
| subakgame | Casual game build | [Windows ZIP](https://github.com/jiyoon99/unity-game-portfolio/releases/download/builds-2026.06/subakgame-windows.zip) | [docs/subakgame.md](docs/subakgame.md) | Unity Windows 실행 빌드 |

## Run / 실행

GitHub Release에서 ZIP을 내려받아 압축을 푼 뒤 Windows 실행 파일을 실행합니다.

```text
VamGame/vam.exe
subakgame/subakgame.exe
```

- [Windows Game Builds 2026.06](https://github.com/jiyoon99/unity-game-portfolio/releases/tag/builds-2026.06)
- [Third-party notices](THIRD_PARTY_NOTICES.md)

## Project Structure / 프로젝트 구조

```text
unity-game-portfolio/
├── games/
│   ├── vamgame/
│   │   ├── README.md
│   │   └── VamGame.unitypackage
│   └── subakgame/
│       └── README.md
├── docs/
│   ├── assets/
│   ├── vamgame.md
│   └── subakgame.md
├── .gitignore
└── README.md
```

## VamGame Implementation Points / VamGame 구현 포인트

- 플레이어 이동과 생존 처리
- 적 생성과 추적
- 무기와 총알 처리
- 아이템 및 장비 시스템
- 레벨업과 HUD
- 오브젝트 풀링 기반 생성 관리

## Assets Preview / 에셋 미리보기

| Enemy | Bullet | Tile Palette |
| --- | --- | --- |
| ![Enemy prefab](docs/assets/vamgame/Assets-Prefabs-Enemy.prefab.png) | ![Bullet prefab](docs/assets/vamgame/Assets-Prefabs-Bullet-0.prefab.png) | ![Tile palette](docs/assets/vamgame/Assets-Tile-New-Palette.prefab.png) |
