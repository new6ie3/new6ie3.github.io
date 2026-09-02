---
layout: project
title: Plunderer
permalink: /projects/plunderer/
image: /images/projects/plunderer.png

engine: Unity
language: C#
period: 2025.01 - 2025.06
team: 1인 개발

github: https://github.com/...
video: https://youtube.com/...
---

# 프로젝트 소개

Plunderer는 실시간 전술 RPG 프로젝트입니다.

강력한 능력치로 적을 압도하는 것이 아니라
잠입과 탈취, 환경을 활용하여 상황을 극복하는 것을
핵심 플레이 방식으로 설계했습니다.


## 개발 정보

| 항목 | 내용 |
|---|---|
| 개발 기간 | 2025.01 ~ 2025.06 |
| 개발 인원 | 1인 |
| 엔진 | Unity |
| 언어 | C# |
| 플랫폼 | PC |


## 주요 기능

### 플레이어 시스템

플레이어의 이동과 상태를 관리했습니다.

- 이동
- 점프
- 달리기
- 피격
- 사망


### 전투 시스템

무기 종류에 따른 공격 시스템을 구현했습니다.

- 근접 공격
- 원거리 공격
- 탄약
- 재장전
- 피격 판정


## 기술적으로 고민한 부분

### Object Pooling

총알을 Instantiate와 Destroy로 반복 생성하는 경우
불필요한 메모리 할당과 해제가 발생했습니다.

이를 해결하기 위해 Object Pooling을 적용했습니다.


## 스크린샷

![게임 화면](/images/projects/plunderer/gameplay01.png)

![전투 화면](/images/projects/plunderer/gameplay02.png)


## 영상

[플레이 영상 보기](https://youtube.com/...)


## GitHub

[GitHub Repository](https://github.com/...)
