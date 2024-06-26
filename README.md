### 2023.07 ~ 몇시에 나갈까 서비스 (운영 중) - 개인 프로젝트

URL: https://몇시에나갈까.com/ 

https://github.com/Juminn/portfolio/assets/90203114/a9052148-d8af-4ecb-a768-6aeb32bd3a05
- 이 서비스는 개인의 대중교통 기회비용과 교통상황을 고려하여 최적의 출발 시간과 대중교통 루트를 제안합니다.
- 시간대별 교통 상황과 개인별 선호도를 이용하여, 사용자에게 가장 알맞은 출발 시간과 대중교통 옵션을 제공해 드립니다.

```
사용예시

출퇴근 자율제로 어느 출근시간을 선택할지 고민 중인 경우 출근 가능 시간대와 목적지를 입력하면,
최적의 출발 시간을 제안해 드립니다. 이를 통해 교통 체증 없이 여유로운 출근길을 만들어드립니다.

Ex) 출퇴근 자율제로 인해 07 ~ 11시 사이에 출근해야하는 A씨는 지하철을 가장 선호하며,
    걷기보단 버스를 좋아한다.
    input(설정 값): 시간: 07~11, 시간당 대중교통 비용( 지하철 비용: 7000, 버스: 9000, 걷기: 11000 )
    output: 가장 기회비용이 적게드는 출퇴근 시간과 루트를 제공
```

- 네이버 지도API와 개인 기회비용 데이터를 활용한 출퇴근 시간과 대중교통 추천 서비스를 총괄
- 기획 및 Front-end, Back-end, Infra
- React, Spring boot, AWS

```
ToBe

1. 설문기능을 추가하여 수치입력 대신 간단한 설문을 통해 대중교통별 기회비용을 산출하는 방법을
    추가할 예정 
2. 택시, 자가용도 추가하여 최선의 이동수단 선택을 제안할 예정
3. 이 서비스에서 얻은 기회비용 데이터와 직방 월세 데이터를 이용해 실제 금전비용 월세 값에
   시간과 대중교통이용 기회비용을 더한 정확한 거주 비용을 제공할 예정
```

```
서비스 홍보

온라인: 개발자 커뮤니티에 게시글을 올려 홍보중
오프라인: 그립톡을 통해 소량 배포하였고 추가기능 완성 후 대량 배포 예정 중
```
  
Front, 서비스 이용법: https://github.com/Juminn/When-to-go-front <br/>
Server: https://github.com/Juminn/When-Are-You-Leaving

-인프라 구성도(AWS)

![image](https://github.com/Juminn/portfolio/assets/90203114/d0d6917c-7476-4757-bd5d-20fe49e9bd1e)



### 2023.05 ~ [자동차공업사 개인사이트 개발 및 운영](https://github.com/Juminn/Car-Web) - 개인 프로젝트

URL: https://car-engineer-su.com/

![image](https://github.com/Juminn/Car-Web/assets/90203114/e47990bf-9950-44b7-ab36-4b6105ab1063)

- 아버지 자동차공업사 홍보를 위해 웹사이트 제작 후 운영중
- React, Spring boot, AWS
- 역할: 총괄 - AWS를 통해 CI/CD 구축하고 Front-end 와 Back-end도 분리하여 개발, 배포 진행
- 구조1: user - react(front-end) - spring boot(back-end)
- 구조2: github(CI) - codebuild(AWS - CD) - [ S3(AWS - front Storage), EC2(AWS - Server) ]- CloudFront(AWS - CDN) - route53(AWS - DNS, hositng)

### 2021.03~2021.07 [습관 교정 프로그램(Habit corrector using I3D cnn model) 제작](https://github.com/Juminn/Habit-Corrector) - 1인 프로젝트


![시연영상 줄임](https://user-images.githubusercontent.com/90203114/201026180-fd1d0c00-78ba-4246-a820-6bf69a727138.gif)

- python, tensorflow, cuda
- 역할: 총괄 - pre-trained 모델을 fine-tuning 해서 습관 교정 프로그램 제작, 훈련을 위한 데이터 셋 제작 및 optical-flow 이미지로 가공

### 2021.09~2022.05 [GPS와 BLE 기반 COVID-19 접촉자 파악 및 전자출입 명부 자동 시스템](https://github.com/Juminn/GPS-based-Covid-19-tracking) 구축 - 4인 프로젝트

![실생활시연](https://user-images.githubusercontent.com/90203114/201134425-a55a6b7e-dbfe-4c0a-a192-a3586b468483.gif)

- 제1저자로서 팀원 세 명, 교수님과 함께 GPS와 BLE 기반 COVID-19 접촉자 파악 및 전자출입 명부 자동 시스템 구축 및 학술논문 작성
- 사용자용 Android App(java)과 서버(Spring boot)구축
- 역할: 기획, Java로 안드로이드 앱 기능 개발(GPS 관련 기능, BLE 통신 기능), 서버 로직 설계와 보완

### 2022.06~2022.09 [페어 프로그래밍 학습 플랫폼](https://github.com/JaeJuParkKangJeong/cowede-websocket) 개발 - 5인 프로젝트

![페어프로그래밍 시연 짧게](https://user-images.githubusercontent.com/90203114/201276877-3bf95dcd-c0e8-4361-9db7-4431f47be09e.gif)

- 페어 프로그래밍 학습 플랫폼 개발
- react(front), node.js(back-end)
- 역할: node.js로 백엔드 개발(매칭과 동시편집 기능)

### 2021.09~2021.12 [유튜브 리얼타임 코멘트 크롬 확장 프로그램](https://github.com/Juminn/ChromeExtentsion_WebCommunication) 제작 - 3인 프로젝트

![시연짧게](https://user-images.githubusercontent.com/90203114/201276974-da85bd84-d298-43c7-acf8-309bc9cef922.gif)

- 유튜브 리얼타임 코멘트 크롬 확장 프로그램 제작
- JAVA Script, html, css(Chrome Extension)
- Node.js(server)
- MySQL(DB)
- 역할: front 기능 개발담당
