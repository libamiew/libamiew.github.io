---
layout: post
categories: posts
title: KT Real Cube
subtitle: 영상기반 터치 인터렉션 컨텐츠
featured-image: /images/project/cat1.png
tags: [Unity]
date-string: FEBRUARY 12, 2021
---

### Introduction

- 기획, 영상디자인, 개발 참여
- 스토리를 따라 진행되는 영상기반 인터렉션 컨텐츠
- 외부업체와의 협업을 통해 현장 센서 연동과 런처 프로그램의 구조 파악 및 구성

### Duration

- 2021 . 01 ~ 2021.05

### 🤝 개발 방식

**Engine** : Unity

**Sensor :** RealSense

- 2D 애니메이션으로 버튼의 움직임 구현.
- OSC 좌표를 센서에서 받아와 좌표값대로 레이캐스트를 쏘아서 클릭 이벤트 구현.
- 로컬 디렉토리에 있는 JSON 파일을 읽고 쓰는 기능을 이용하여 총 4명의 유저데이터를 저장하고, 순위를 메기는 시스템 구현.
- 영상리소스는 외부폴더에 따로빼서 관리하기 쉽도록 구성.


**Design :** 

- 모션그래픽 2D 애니메이션을 위해 일러스트레이터에서 작업후 애프터이펙트에서 애니메이션 작업. 2D로 안되는 부분은 유니티에서 3D로 구현함.
- 튜토리얼 UI, 리워드 게시판 UI, 배틀모드 UI 구현 

### 🤝 프로젝트 데모

<iframe width="800" height="315" src="https://www.youtube.com/embed/4sWsA__VeuM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>