---
layout: post
title:  "Visual Studio 프로그램이 끝난 후 콘솔창 유지"
subtitle:   "콘솔창 유지 메모"
categories: tip
tags: tip
---

1. 코드 내에 `system("pause");` 삽입


2. 메뉴 [프로젝트] - [속성] - [구성속성] - [링커] - [시스템] 탭에서
 `콘솔 Console (/SUBSYSTEM:CONSOLE)` 선택
