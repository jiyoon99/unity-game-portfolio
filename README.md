# Unity Game Portfolio

Unity를 공부하면서 만든 게임 결과물을 포트폴리오용으로 정리한 저장소입니다.

단순히 빌드 파일을 모아둔 저장소가 아니라, 각 게임을 실행 가능한 결과물과 설명 문서로 분리해 “무엇을 만들었고, 어떤 시스템을 구현했는지”를 확인할 수 있도록 구성했습니다.

![VamGame cover](docs/assets/vamgame-cover.png)

## Project Summary

| Item | Description |
| --- | --- |
| Type | Unity game portfolio |
| Role | 개인 학습 프로젝트 / 구현, 빌드, 문서화 |
| Goal | Unity 학습 과정에서 만든 게임을 실행 가능한 포트폴리오 형태로 정리 |
| Platform | Windows build |
| Engine | Unity |
| Language | C# |

## Project Gallery

| VamGame | subakgame |
| --- | --- |
| ![VamGame cover](docs/assets/vamgame-cover.png) | ![subakgame cover](docs/assets/subakgame-cover.png) |
| 2D 생존 액션 게임. 적 스폰, 무기, 아이템, 레벨업, 오브젝트 풀링 흐름을 설명할 수 있는 프로젝트입니다. | Unity Windows 빌드 결과물. 실행 가능한 완성 빌드를 보존하고 포트폴리오 문서로 정리한 프로젝트입니다. |
| [상세 문서](docs/vamgame.md) | [상세 문서](docs/subakgame.md) |

## Why I Organized This

Unity 학습 프로젝트는 시간이 지나면 빌드 파일, Unity package, 에셋 자료가 섞이기 쉽습니다. 이 저장소는 그 결과물을 포트폴리오에서 바로 확인할 수 있도록 게임별로 분리하고, 실행 방법과 구현 포인트를 문서화하기 위해 만들었습니다.

특히 `VamGame`은 단순 실행 빌드가 아니라 플레이어, 적, 무기, 스폰, 아이템, HUD 같은 게임 루프 구성 요소를 설명할 수 있는 프로젝트라 포트폴리오 중심 항목으로 정리했습니다.

## Key Features

- Windows에서 바로 실행 가능한 Unity 빌드 포함
- 게임별 README 분리
- `VamGame` Unity package 포함
- 포트폴리오 설명용 핵심 구현 포인트 정리
- 학습 프로젝트와 실행 결과물을 구분한 디렉터리 구조

## Included Projects

| Project | Genre | Build | Detail | Portfolio Point |
| --- | --- | --- | --- | --- |
| VamGame | 2D action survival | `games/vamgame/Build/VamGame/vam.exe` | [docs/vamgame.md](docs/vamgame.md) | 플레이어 성장, 적 스폰, 무기/아이템, 오브젝트 풀링 |
| subakgame | Unity Windows build | `games/subakgame/Build/subakgame/subakgame.exe` | [docs/subakgame.md](docs/subakgame.md) | Unity 학습 과정에서 완성 빌드까지 만든 실행 결과물 |

## Tech Stack

| Area | Stack |
| --- | --- |
| Engine | Unity |
| Language | C# |
| Build target | Windows |
| Game type | 2D action, survival, casual game |
| Documentation | Markdown |

## Run

Windows에서 각 게임 폴더의 실행 파일을 실행합니다.

```text
games/vamgame/Build/VamGame/vam.exe
games/subakgame/Build/subakgame/subakgame.exe
```

## Project Structure

```text
unity-game-portfolio/
├── games/
│   ├── vamgame/
│   │   ├── README.md
│   │   ├── VamGame.unitypackage
│   │   └── Build/VamGame/
│   └── subakgame/
│       ├── README.md
│       └── Build/subakgame/
├── docs/
│   ├── assets/
│   ├── vamgame.md
│   └── subakgame.md
├── .gitignore
└── README.md
```

## Portfolio Notes

### VamGame

`VamGame`은 뱀파이어 서바이벌 스타일의 2D 생존 액션 게임입니다. 플레이어가 적을 피하면서 무기와 아이템을 성장시키는 구조로, Unity에서 게임 루프를 구성하는 기본 요소를 학습한 프로젝트입니다.

설명할 수 있는 내용:

- 플레이어 이동과 생존 처리
- 적 생성과 추적
- 무기와 총알 처리
- 아이템 및 장비 시스템
- 레벨업과 HUD
- 오브젝트 풀링 기반 생성 관리

에셋 프리뷰:

| Enemy | Bullet | Tile Palette |
| --- | --- | --- |
| ![Enemy prefab](docs/assets/vamgame/Assets-Prefabs-Enemy.prefab.png) | ![Bullet prefab](docs/assets/vamgame/Assets-Prefabs-Bullet-0.prefab.png) | ![Tile palette](docs/assets/vamgame/Assets-Tile-New-Palette.prefab.png) |

### subakgame

`subakgame`은 Unity 학습 과정에서 완성 빌드까지 만든 Windows 실행 게임입니다. 현재 보관된 자료가 빌드 형태라, 포트폴리오에서는 실행 가능한 결과물 중심으로 정리했습니다.

## What I Learned

- Unity 프로젝트를 Windows 실행 빌드로 완성하는 흐름
- 게임별 결과물을 포트폴리오 관점에서 분리하고 문서화하는 방식
- 플레이어, 적, 아이템, UI처럼 게임 루프를 구성하는 요소의 역할
- 빌드 파일과 소스 패키지를 GitHub에서 관리할 때의 용량/구조 고려

## Next Improvements

- 게임별 스크린샷 추가
- 짧은 플레이 GIF 또는 영상 링크 추가
- `subakgame` 원본 Unity project 또는 `.unitypackage` 추가
- `VamGame`의 주요 C# 스크립트 설명 보강
