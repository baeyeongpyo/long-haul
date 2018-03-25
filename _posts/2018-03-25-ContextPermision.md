---
layout: post
title: Android Context 타입
description: Android Context
category: android
tags: [이론]
---




|                            | Application | Activity | Service | Conten Provider   | Broadcast Recevier |
|----------------------------|:-----------:|:--------:|:-------:|:-----------------:|:------------------:|
| show a Dialog              |     NO      |    YES   |   NO    |       NO          |         NO         |
| Start an Activity          |     NO      |    YES   |   NO    |       NO          |         NO         |
| Layout Inflation           |     NO      |    YES   |   NO    |       NO          |         NO         |
| Start a Service            |     YES     |    YES   |   YES   |       YES         |         YES        |
| Bind to a Service          |     YES     |    YES   |   YSE   |       YES         |         NO         |
| Send A Broadcast           |     YSE     |    YES   |   YSE   |       YES         |         YES        |
| Register BroadcastReceiver |     YES     |    YES   |   YES   |       YES         |         NO         |
| Load Resource Values       |     YES     |    YES   |   YES   |       YES         |         YES        |
