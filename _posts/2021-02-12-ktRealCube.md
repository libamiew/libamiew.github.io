---
layout: post
categories: posts
title: KT Real Cube
subtitle: 영상기반 터치 인터렉션 컨텐츠
featured-image: /images/project/rapa2.png
tags: [Unity]
date-string: FEBRUARY 12, 2021
---

### Introduction

- 영상기반의 리듬감있는 터치 인터렉션 컨텐츠
- 기획, 영상디자인, 게임개발 참여
- 런처등의 시스템은 다른업체의 도움을 받아 진행

### Duration

- 2020 . 10 ~ 2021.02

### 🤝 개발 방식

**Engine** : Unity

**SDK :** Azure-Kinect 센서 SDK, Azure-Kinect Body Tracking SDK

**API** : Azure Kinect for Unity3D (Camera API + Body Tracking API)

- 바디트랙킹 기능을 이용해 뼈대정보를 포인트 클라우드로 띄우는 기능을 사용함
- 사용자가 복도에 들어서면 공간 전체 스캔이 되고, 이어서 벌이 사용자를 훑어보며 지나가는 애니메이션을 유니티에서 구현했다.
- 뼈대정보의 위치값을 이용해,  센서의 시작위치와 사용자의 위치값의 각도를 구한 후, 애니메이션 클립의 시간을 제어 할 수 있도록 정규화시킴으로써 애니메이션을 위치값으로 제어 할 수 있게 함.

**Design :** 레벨디자인은 에셋을 받아 재구성했다.

### 🤝 프로젝트 내용

메인쇼를 보러가기 전, 복도를 지나 가게 되는데 그 복도의 벽면에 프로젝션 맵핑된 컨텐츠가 보이게 구성. 주인공의 반대 세력인 빨간 불빛을 쏘는 벌이 마치 사용자들을 스캔하듯이 쭉 훑어, 자신의 세력인지 아닌지를 구별하는 스토리를 갖고있다.

### 🤝 프로젝트 데모

<iframe width="800" height="315" src="https://www.youtube.com/embed/Wp2_ochlWag" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>