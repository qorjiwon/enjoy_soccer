# 축구관련 정보제공 챗봇
 [![node-16.15.0](https://img.shields.io/badge/Node-16.15.0-green?logo=nodedotjs)](https://nodejs.org/ko/)
 [![express-4.18.1](https://img.shields.io/badge/Express-4.18.1-green?logo=express)](https://expressjs.com/ko/)
<!--Table of Contents-->
## Table of Contents
1. About the Project
2. Getting Started (Installation)
3. Usage
4. Roadmap
5. Contributing
6. Contact


<!--About The Project-->
## About The Project
- Line 채널 ID로 챗봇을 추가하여 사용할 수 있습니다.
- 해당 챗봇을 통하여 경기 일정과 소속선수 그리고 팀, 득점, 도움 순위 정보를 제공합니다.
- Papago API를 이용하여 한글과 영어 입력이 모두 지원 가능하도록 했습니다.

### Built With
- [Node.js](https://nodejs.org/ko/)
- [Express](https://expressjs.com/ko/)
- [Javascript](https://developer.mozilla.org/ko/docs/Web/JavaScript)
- [Line API](https://developers.line.biz/en/services/messaging-api/)
- [Papago API](https://developers.naver.com/apps)
- [Sports API](https://www.api-football.com/documentation-v3#section/Authentication)


<!--Getting Started (Installation)-->
## Getting Started

### Prerequisites
- npm
```
npm install
```

### Installation
- Messaging API
1. Get a free API Key at <https://developers.line.biz/en/services/messaging-api/>
- Sports API
2. Get a free API Key at <https://www.api-football.com/>
3. Clone the repo
```
git clone https://github.com/qorjiwon/enjoy_soccer.git
```
4.Install NPM packages
```
npm install
```

<!--Usage-->
## Usage
1. Line 앱에서 "FootballManager" 채널을 추가해 주세요.  
   - 라인 채널 아이디 : @561ankpu
   
2. 채팅창에 들어가면 챗봇이 안내 문구를 전송합니다.  
<img src="https://github.com/qorjiwon/enjoy_soccer/assets/82700743/f9bee73b-dbad-4507-8ddc-1a6bf6018980" width="300px" height="800px"></img>
3. 안내 문구에 따라 리그 번호 혹은 팀명을 입력합니다.<br>
<img src="https://github.com/qorjiwon/enjoy_soccer/assets/82700743/9e38b7d9-9a17-4b0b-8ce2-9f45a24a1eed" width="300px" height="300px"></img><br/>  
<p align="right">(<a href="#top">back to top</a>)</p>

<!--Roadmap-->
## Roadmap
- [x] Line 채널 만들기
- [x] 한->영, 영->한으로 메세지 번역하기
- [x] leagueID로 teamID 받아오기
- [x] teamID로 leagueID 받아오기
- [x] 메세지 공백 처리하기
- [x] 기능 별 Sports API에서 추출한 json파일 파싱하는 함수 구현하기

<!--Contributing-->
## Contributing
1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!--Contact-->
## Contact
- 박찬수 : suplife0@khu.ac.kr
- 백지원 : wldnjsl2001@khu.ac.kr
- 차가민 : gmcha0323@khu.ac.kr

<p align="right">(<a href="#top">back to top</a>)</p>
