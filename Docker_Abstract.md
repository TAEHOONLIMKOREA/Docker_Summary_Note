![header](https://capsule-render.vercel.app/api?text=Docker%20Summary%20Note&fontSize=50&animation=fadeIn&fontColor=eeeeee)

# 1. 개요
## 1-1. 도커 개념
Docker는 가상화 컨테이너에 Application 배포를 자동화시켜주는 오픈소스 엔진으로 마이크로서비스 아키텍처와 함께 각광받고 있는 엔진이다. 

서버 환경이 전통적인 온프레미스 환경에서 클라우드로 바뀌면서 가상서버를 손쉽게 늘리고 관리할 수 있게 되었지만 이에 따른 배포는 불편한 점이었다. 
Docker가 제공하는 경량화된 가상화 컨테이너 기술은 환경의 배포와 확장을 하는데 엄청난 이점을 제공해준다.

![image](https://user-images.githubusercontent.com/87262811/210510036-0ab2f630-edef-42b6-9949-56b08e97d72e.png)

Docker 는 Container 와 Image 라는 개념으로 구성되며, Network 및 Data 와 같은 리소스들을 각 엔진별로 다룰 수 있고 이를 위한 인터페이스로 Docker 서버에서 REST API 를 제공한다.

![image](https://user-images.githubusercontent.com/87262811/210501063-a34bf59a-b250-42fb-a8aa-5dd9dc71577a.png)
맥이나 윈도우에선 가상환경위에 리눅스를 깔아서 도커를 실행하기 때문에 더 느림..

![image](https://user-images.githubusercontent.com/87262811/210514053-1c42909e-78b1-4575-97bf-426bfc9324fc.png)
<br> <앱스토에서 프로그램을 다운받고 실행시키는 것과 유사함> <br>
*도커 허브 : 깃 허브 같은 이미지파일들이 공유되어있는 홈페이지  <br>
*이미지 : Docker 컨테이너를 만들기 위한 Read Only Layer  <br>
*컨테이너 : 실행된 또는 실행 가능한 Docker 이미지  <br>


## 1-2. 컨테이너 배포 절차

![image](https://user-images.githubusercontent.com/87262811/210515604-5345bc17-7811-4ea1-927d-be2cee71b9dd.png)

| 번호 | 설명 |
| ------ | ------ |
| ① 개발 | 개발자 PC에서 APP 개발 |
| ② Repository 배포 | 배포서버에 소스 업로드 |
| ③ Registry 배포 | 배포서버에 소스 저장(배포) |
| ④ Image 생성 | Doker Image 생성 후 Registery 등록 |
| ⑤ Container 생성 | docker Image 다운로드 및 실행 |

## 1.3 도커의 기대효과 및 구현 사례

|  | 기대효과 및 구현 사례 |
| ------ | ------ |
| 성능 개선 | 개발과 운영 호환성 증가 |
| 플랫폼 비종속 | 운영체제 커널에 관계없이 실행 |
| Google | Gmail 및 자사 서비스 운영 |
| Microsoft | Windows Server 2016에 도커 적용 |
| Amazon | AWS에 도커 활용 및 기능 지원 |

