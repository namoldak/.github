![나몰닭깃헙상단이미지](https://user-images.githubusercontent.com/117756400/216939133-6d703bcf-80ce-4939-ada5-a583af07185e.jpg)

## 🐣 GITHUB
<div align=center>

✔️ 기술적 의사 결정, 트러블 슈팅, 유저 피드백 등은 각 깃허브에 추가되어 있습니다.  
</div>

#### [🐣 FRONTEND GITHUB](https://github.com/namoldak/Frontend)
#### [🐣 BACKEND GITHUB](https://github.com/namoldak/Backend)

<br /> <br />

# 🐔나만 모른 닭🐔
<div align=center>

***내 머리에 있는 거 뭐야? 나만 몰라?***  
”양세찬 게임” 혹은 “콜 마이 네임”으로 불리는 *키워드 맞추기* 게임!  
스무고개처럼 상대 플레이어에게 질문하면서 나의 키워드를 맞춰보세요🐤  
최대한 <u>헷갈리게 답변</u>하고 최대한 <u>날카롭게 질문</u>하세요!  
<br />
![나몰닭상단이미지](https://user-images.githubusercontent.com/117756400/216971099-fff770a8-8462-4ad0-91f1-64463703bf5f.png)  
</div>

<br /> <br />

## 🔗 나만 모른 닭 서비스 및 노션
#### [🐔 나만 모른 닭 서비스](https://namoldak.com)
#### [🐔 나만 모른 닭 브로슈어](https://colossal-chokeberry-fec.notion.site/39515b59c604426494e905a62410ce3b)

<br /> <br />

## 📢 주요 서비스 기능
<ul>
<li> 런닝맨의 양세찬 게임(aka. call my name 게임)을 온라인에서도 즐길 수 있게 웹으로 구현하였습니닭🐔 </li>
<li> 텍스트 채팅뿐만 아니라 음성/화상 채팅으로도 서로 대화를 나누며 게임을 즐길 수 있습니닭🐔 </li>
<li> 게임도 하고 게시판을 이용해 다른 유저들과 소통도 할 수 있습니닭🐔 </li>
<li> 소셜 로그인이 있어 별도의 회원가입이 필요하지 않습니닭🐔 </li>
</ul>

<br /> <br />

## 📽 페이지 소개

| 회원가입 및 로그인 | 마이페이지 |
|:------:|:------:|
| ![1회원가입및로그인](https://user-images.githubusercontent.com/117756400/217148826-0b851380-8fb6-4f15-860a-185ec9bab180.gif) | ![2마이페이지](https://user-images.githubusercontent.com/117756400/217147123-b5d36c26-c253-42a1-a725-0e2c06397644.gif) |

| 게임 룰 | 방 만들고 입장 |
|:------:|:------:|
| ![3게임룰](https://user-images.githubusercontent.com/117756400/217147543-a3d20992-a7aa-47fc-972a-e4d97a8ec26c.gif) | ![4방만들고입장](https://user-images.githubusercontent.com/117756400/217150029-462f4d0b-88f4-4929-a12d-101e8c1e1244.gif) |

| 게임 대기 페이지 | 게임 시작 및 게임하기 |
|:------:|:------:|
| ![5게임대기페이지](https://user-images.githubusercontent.com/117756400/217147619-a09f85da-96f3-47cf-bb02-8adef0ceabbe.gif) | ![6게임시작및게임하기](https://user-images.githubusercontent.com/117756400/217149536-23c4ec3c-3403-4d0c-993e-d13fe4541e3c.gif) |

| 정답 넘기기 및 정답 맞추기 | 커뮤니티 |
|:------:|:------:|
| ![7정답넘기기와정답맞추기](https://user-images.githubusercontent.com/117756400/217147360-1aead5da-05e4-4077-b623-49c602c5a32c.gif) | ![8커뮤니티](https://user-images.githubusercontent.com/117756400/217147494-fd52bba0-35e0-480b-ab84-a83c41fca523.gif) |

<br /> <br />

## ⚙️ 서비스 아키텍쳐
![나몰닭-아키텍쳐2](https://user-images.githubusercontent.com/117756400/216894689-8921deef-c813-42ca-a8f2-6e58f34fd4b8.jpg)

<br /> <br />

## 📌 핵심 기술
- 실시간 채팅을 위한 Web Socket
  - 화상 및 음성 채팅을 위한 WebRTC
  - 다양한 브라우저 환경을 지원하기 위한 SockJS
  - pub/sub 기반의 편리한 웹소켓 관리를 위한 메세징 프로토콜 STOMP
- Refresh Token의 생명 주기 관리를 위한 서브 데이터베이스로의 Redis 사용
- 생산성 증가 및 개발자 편의를 위한 CI/CD
- AWS CloudFront를 이용한 S3 이미지 엔드포인트 보안
- Intersection-observer API를 사용한 댓글 무한 스크롤
- OAuth 2.0 소셜 로그인을 통한 간편한 접근성

<br /> <br />

## 🛠 기술 스택

### Frontend Tech Stacks
<img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">  <img src="https://img.shields.io/badge/redux-764ABC?style=for-the-badge&logo=redux&logoColor=white">  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">  <img src="https://img.shields.io/badge/sockJS-010101?style=for-the-badge&logo=socket.io&logoColor=white">  <img src="https://img.shields.io/badge/webrtc-333333?style=for-the-badge&logo=webrtc&logoColor=white">
<br />
<img src="https://img.shields.io/badge/react router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=black">  <img src="https://img.shields.io/badge/styled components-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=black">  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<br /> <br />

### Backend Tech Stacks
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">  <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">  <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white">  <img src="https://img.shields.io/badge/spring security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
<br />
<img src="https://img.shields.io/badge/websocket-FFCD00?style=for-the-badge&logo=websocket&logoColor=white">  <img src="https://img.shields.io/badge/sockJS-010101?style=for-the-badge&logo=socket.io&logoColor=white">  <img src="https://img.shields.io/badge/webrtc-333333?style=for-the-badge&logo=webrtc&logoColor=white">  <img src="https://img.shields.io/badge/stomp-006272?style=for-the-badge&logo=stomp&logoColor=white">
<br />
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">  <img src="https://img.shields.io/badge/redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">  <img src="https://img.shields.io/badge/amazon ec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white">  <img src="https://img.shields.io/badge/amazon s3-569A31?style=for-the-badge&logo=amazons3&logoColor=white">  <img src="https://img.shields.io/badge/amazon rds-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white"> 
<br />
<img src="https://img.shields.io/badge/aws codedeploy-FF9E9F?style=for-the-badge&logo=awscodedeploy&logoColor=white">  <img src="https://img.shields.io/badge/github actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
<br /> <br />
  
### Team Collaboration Tools
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">  <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">  <img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">  <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">  <img src="https://img.shields.io/badge/postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white">  <img src="https://img.shields.io/badge/intellij-000000?style=for-the-badge&logo=intellijidea&logoColor=white">
<br />

</div>

<br /><br />

## 🧑🏻‍💻 개발 기간 & 조원
✔️ 2022.12.30 - 2022.02.09
<br />
✔️ 멤버 이름 클릭 시, 해당 멤버의 깃허브를 방문하실 수 있습니다.
<br /> <br />
<div align=center>

|  [김현빈](https://github.com/kimmy199535)  | [이정민](https://github.com/kkookk55) | [최수빈](https://github.com/123456soobin-choi) | 정희애 |
|:---:|:---:|:---:|:---:|
| ![현빈님캐릭터](https://user-images.githubusercontent.com/117756400/216781489-d5e60509-684d-4636-b7e6-af714a2d921c.png) | ![정민님캐릭터](https://user-images.githubusercontent.com/117756400/216781452-8767b30e-5180-4270-8685-448b87cde9a7.png) | ![수빈님캐릭터](https://user-images.githubusercontent.com/117756400/216781532-113c826a-a330-4573-8a13-525446a61e0b.png) | ![희애님캐릭터](https://user-images.githubusercontent.com/117756400/216781821-9adf9b05-907a-4d55-8ac4-11c09534a3c1.png) |
| FE/REACT | FE/REACT | FE/REACT | DESIGN |
| **[김아영](https://github.com/isladaisy)** | **[조소영](https://github.com/littlezero48)** | **[차이진](https://github.com/leejincha)** | **[홍윤재](https://github.com/PigletHong)** |
| ![내캐릭터](https://user-images.githubusercontent.com/117756400/216781592-6934710c-1e4a-43dd-aeb9-2117b5fed5f4.png) | ![소영님캐릭터](https://user-images.githubusercontent.com/117756400/216781599-b9559a95-20d8-4b76-90a4-12151263a203.png) | ![이진님캐릭터](https://user-images.githubusercontent.com/117756400/216889730-6221074f-7875-46c4-96c0-a516a7262ff9.png) | ![윤재님캐릭터](https://user-images.githubusercontent.com/117756400/216895789-d84c1ac7-16ec-42e8-ac42-d0b5a50ae9d0.png) |
| BE/SPRING | BE/SPRING | BE/SPRING | BE/SPRING |
</div>
<br /> <br /> <br />
