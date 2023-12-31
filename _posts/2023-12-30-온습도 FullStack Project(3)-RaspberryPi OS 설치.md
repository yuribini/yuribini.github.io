---
title: 온습도 FullStack Project(3)-RaspberryPi OS 설치
date: 2023-12-30 22:06:00 +09:00
categories: [Raspberry Pi, Project]
tags:
  [
    라즈베리파이,
    프로젝트,
    온습도,
    SSH,
    커스텀세팅,
    Raspberry Pi,
    라즈베리파이,
    OS 설치
  ]
---

## 👉🏻[(1)사용할 Stack 정리](<https://yuribini.github.io/posts/%EC%98%A8%EC%8A%B5%EB%8F%84-FullStack-Project(1)-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B2%8C-%EB%90%A0-Stack/>)

### 👉🏻[(2)RaspberryPi Model_OS선정](<https://yuribini.github.io/posts/%EC%98%A8%EC%8A%B5%EB%8F%84-FullStack-Project(2)-RaspberryPi-Model-,-OS%EC%84%A0%EC%A0%95/>)

<br>
<br>

# OS 설치

- Mac OS 기준으로 설명.
- Windows OS 도 별반 다르지 않다.

## 1. Imager Download

![Imager Download](/images/Imager_Download.png)

### [👉 Link https://www.raspberrypi.com/software/](https://www.raspberrypi.com/software/)

- Imager를 다운로드 한다.

<br>
<br>

## 2. Imager Setting

![Imager Menu](/images/Imager_Menu.png)

- Imager를 설치해주고 실행하면 위 창이 발생한다.
- 디바이스는 본인 모델 선택해주면 되고..

<br>

![Use Custom](/images/Use_Custom.png)

- 운영체제는 Use Custom 선택 후 지난 포스팅에 다운받았던 img.xz 파일을 선택해준다.
  > 지난 포스팅 👉🏻[(2편)OS선정](<https://yuribini.github.io/posts/%EC%98%A8%EC%8A%B5%EB%8F%84-FullStack-Project(2)-RaspberryPi-Model-,-OS%EC%84%A0%EC%A0%95/>)

<br>

![Setting Adjust](/images/Setting_Adjust.png)

<br>

![Custom Setting](/images/Custom_Setting.png)

- RaspberryPi 4 이전의 모델은 Wifi_5Ghz를 지원하지 않을 수 있으니 꼭 `2.4G`로 사용 및 입력하도록 하자.

<br>

![Custom Service](/images/Custom_Service.png)

- 위와 같이 세팅한 후 `예` 를 누르고 설치를 마무리 한다. 위 Setting에 Wifi 네트워크 세팅과 SSH 세팅이 모두 포함되어 있기 때문에 RaspberryPi 접속이 바로 가능해진다.
- 커스터마이징 세팅을 하지 않을 경우 별도로 모니터를 연결하여 세팅이 필요하니 꼭 커스터마이징 세팅을 하도록 한다.
