# VamGame

![VamGame cover](../../docs/assets/vamgame-cover.png)

`VamGame`은 뱀파이어 서바이벌 스타일의 2D 액션 생존 게임입니다. 몰려오는 적을 피하면서 무기와 아이템을 성장시키는 구조로, Unity의 기본 게임 루프와 런타임 오브젝트 관리 흐름을 학습하며 제작했습니다.

상세 포트폴리오 문서: [docs/vamgame.md](../../docs/vamgame.md)

## Project Summary

| Item | Description |
| --- | --- |
| Type | 2D action survival game |
| Role | 개인 학습 프로젝트 / 구현, 빌드, 문서화 |
| Engine | Unity |
| Language | C# |
| Build | Windows executable |
| Package | `VamGame.unitypackage` 포함 |

## Why I Built This

Unity에서 플레이어 이동, 적 생성, 전투, 아이템, UI, 게임 결과 화면까지 하나의 플레이 흐름으로 연결하는 연습을 하기 위해 만들었습니다.

단순히 캐릭터를 움직이는 데모가 아니라, 적이 생성되고 플레이어가 생존하며 성장하는 반복 플레이 구조를 만드는 데 초점을 두었습니다.

## Key Features

- 플레이어 이동과 생존 처리
- 적 생성과 추적
- 무기와 총알 처리
- 아이템 및 장비 시스템
- 레벨업과 HUD 표시
- 게임 결과 화면
- 오브젝트 풀링 기반 생성 관리

## Run

Windows에서 아래 실행 파일을 실행합니다.

```text
Build/VamGame/vam.exe
```

## Included Files

- `VamGame.unitypackage`: Unity 프로젝트 에셋 패키지
- `Build/VamGame/`: Windows 실행 빌드

## Main Systems

- 플레이어 이동과 생존 처리
- 적 생성과 추적
- 무기, 총알, 아이템, 장비 시스템
- 레벨업과 HUD
- 오브젝트 풀링 기반 생성 관리

## Core Scripts

- `Player`
- `Enemy`
- `Weapon`
- `Spawner`
- `PoolManager`
- `LevelUP`
- `HUD`
- `GameResult`

## Tech Stack

- Unity
- C#
- 2D
- Object Pooling
- Windows Build

## Project Structure

```text
vamgame/
├── README.md
├── VamGame.unitypackage
└── Build/
    └── VamGame/
        ├── vam.exe
        └── vam_Data/
```

## Portfolio Summary

Unity의 2D 게임 루프, 적 스폰, 성장 시스템, UI 흐름을 학습하며 만든 생존형 액션 게임입니다. 반복 생성되는 적과 투사체를 관리하기 위해 풀링 구조를 사용했고, 플레이어 성장과 결과 화면까지 하나의 플레이 흐름으로 구성했습니다.

## Asset Preview

| Enemy | Bullet | Tile Palette |
| --- | --- | --- |
| ![Enemy prefab](../../docs/assets/vamgame/Assets-Prefabs-Enemy.prefab.png) | ![Bullet prefab](../../docs/assets/vamgame/Assets-Prefabs-Bullet-0.prefab.png) | ![Tile palette](../../docs/assets/vamgame/Assets-Tile-New-Palette.prefab.png) |

## What I Learned

- Unity에서 플레이어, 적, 무기, UI를 하나의 게임 흐름으로 연결하는 방식
- 반복 생성되는 오브젝트를 관리할 때 풀링 구조가 필요한 이유
- 게임 결과 화면까지 포함해 플레이 시작부터 종료까지 완성된 루프를 만드는 과정
