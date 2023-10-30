<div align="center">
	<img src="https://github.com/lol-voice-chat/.github/assets/105103712/bccba31c-e118-4353-a915-681265cd66d9" width="120">
	<h1>롤보챗 (Lol Voice Chat)</h1>
	<p>
		<b>롤에서 매칭된 팀원과 음성채팅이 가능한 데스크탑 어플리케이션 서비스</b>
	</p>
	<br>
	<br>
	<br>
</div>

롤보챗은 롤에서 만난 사람들과 음성으로 대화할 수 있는 데스크탑 앱입니다. 

매칭이 잡히고 챔피언 선택창으로 넘어가는 순간부터 롤보챗 앱을 이용하고 있는 팀원끼리 자동으로 보이스방이 생성됩니다. 

또한 챔피언 선택 후 게임로딩창으로 넘어가면, 팀원과 적팀이 서로 음성으로 대화할 수 있습니다. 게임이 시작되면 전체보이스방은 자동으로 끊깁니다.

롤보챗은 보이스 말고도 전채채팅, 소환사 정보 표시, 최근 함께한 소환사, 단축키, 기타 설정 등 다양한 기능이 있습니다. 

[롤보챗 FE 개발 회고](https://velog.io/@tkyung05/%EB%A1%A4%EB%B3%B4%EC%B1%97-FE-%EA%B0%9C%EB%B0%9C-%ED%9A%8C%EA%B3%A0)

<br>

## 다운로드
지원하는 운영체제 : window, mac os 

- [macOS(arm64)](https://github.com/lol-voice-chat/lvc-app/releases/download/v0.1.3/lvc-0.1.3-arm64-mac.zip) 
- [macOS(intel)](https://github.com/lol-voice-chat/lvc-app/releases/download/v0.1.3/lvc-0.1.3-mac.zip) 
- [window](https://github.com/lol-voice-chat/lvc-app/releases/download/v0.1.2/lvc-Setup-0.1.2.exe)

<br/>

## 🙇‍♂️ 팀원
|                                         Frontend                                         |                                           Backend                                           |
| :--------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------:
| <img src="https://avatars.githubusercontent.com/u/105103712?v=4" width=200px /> | <img src="https://avatars.githubusercontent.com/u/80371249?v=4" width=200px /> | 
|                            [tkyung05](https://github.com/tkyung05)                             |                    [nswon](https://github.com/nswon)                |

<br/>

## ⚙️ 기술스택
### FE

* **Language |** Typescript

* **Framework |** Electron

* **Library |** React.js, Recoil, Socket.io, Mediasoup

* **CSS |** Styled-Components 

* **Module Bundler |** Webpack

* **Package Manager |** Npm
  
<br/>

### BE
* **Language |** Typescript, Javascript

* **Framework |** Electron, Nodejs

* **Library |** Socket.io, Mediasoup, Redis, class-transformer, league-connect, electron-builder, webpack

* **Module Bundler |** Webpack

* **Package Manager |** Npm

<br/>

## 🧏‍♂️ 핵심 기능
### 로그인을 하지않아도 롤만 켜주면 자동으로 유저의 정보를 불러옵니다.
<p align="center">
<img width="900" alt="스크린샷 2023-10-29 오후 11 25 26" src="https://github.com/lol-voice-chat/.github/assets/105103712/2b98a477-16dc-4580-844e-b3b0a6499b0d">
  
<img width="900" alt="스크린샷 2023-10-29 오후 11 32 24" src="https://github.com/lol-voice-chat/.github/assets/105103712/b146b709-9819-4dc2-9d7b-6f0d1dcbe4f4">
</p>

### 유저의 최근전적과 승률 등 유용한 정보를 제공합니다.
<p align="center">
<img width="400" alt="스크린샷 2023-10-29 오후 11 10 55" src="https://github.com/lol-voice-chat/.github/assets/105103712/8e1151dd-a890-4996-8d5e-d8a5eeacf0f9">
</p>

### 팀 보이스 - 큐가 잡히면 팀원간의 음성채팅이 가능하며 팀원의 정보도 함께 제공합니다. 
<div align="center">
  <img width="400" alt="스크린샷 2023-10-29 오후 11 39 26" src="https://github.com/lol-voice-chat/.github/assets/105103712/1b0d9d7c-8171-46c6-9883-5765cbf5562e">
  <img width="500" alt="스크린샷 2023-10-29 오후 11 40 05" src="https://github.com/lol-voice-chat/.github/assets/105103712/118a131c-a626-4db0-a7aa-bdecdf01d02b">
</div>

### 챔피언 선택시 실시간으로 해당 챔피언에 맞는 UI와 정보가 업데이트됩니다.
<div align="center">
  <img width="800" alt="스크린샷 2023-10-29 오후 11 15 22" src="https://github.com/lol-voice-chat/.github/assets/105103712/0a56632f-0718-41d5-a001-e62aa83ae86a">
  <img width="800" alt="스크린샷 2023-10-29 오후 11 15 44" src="https://github.com/lol-voice-chat/.github/assets/105103712/f7cfc5ce-f56b-42ee-98ec-400f8d9f89c8">
</div>

### 리그 보이스 - 로딩창에서 부터 미니언이 생성되기까지 적팀, 우리팀 모두 함께 음성채팅을 이용할 수 있습니다.
<div align="center">
  <img width="336" alt="스크린샷 2023-10-29 오후 11 50 05" src="https://github.com/lol-voice-chat/.github/assets/105103712/421aa3ba-352c-410b-8559-023765ff291a">
  <img width="576" alt="스크린샷 2023-10-29 오후 11 16 55" src="https://github.com/lol-voice-chat/.github/assets/105103712/08d1c332-1a11-4c53-a678-d76c03eb6749">
</div>

### 유저 UI에 마우스를 오버하면 해당 유저와 챔피언에 맞는 정보를 제공합니다. 
<div align="center">
  <img width="473" alt="스크린샷 2023-10-29 오후 11 17 03" src="https://github.com/lol-voice-chat/.github/assets/105103712/0bf463c0-8804-4a1c-9419-22806535d218">
</div>


## 다른 기능들도 궁금하시다면 아래 링크의 시연 영상을 확인해주세요
### 👉 [시연 영상]()
