# VamGame

## Overview

`VamGame`은 뱀파이어 서바이벌 스타일의 2D 액션 생존 게임입니다. 플레이어가 몰려오는 적을 피하면서 무기와 아이템을 성장시키는 구조로 제작했습니다.

## Play

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

## Portfolio Summary

Unity의 2D 게임 루프, 적 스폰, 성장 시스템, UI 흐름을 학습하며 만든 생존형 액션 게임입니다. 반복 생성되는 적과 투사체를 관리하기 위해 풀링 구조를 사용했고, 플레이어 성장과 결과 화면까지 하나의 플레이 흐름으로 구성했습니다.
