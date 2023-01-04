![header](https://capsule-render.vercel.app/api?text=Docker%20Summary%20Note&fontSize=50&animation=fadeIn&fontColor=eeeeee)

Docker는 가상화 컨테이너에 Application 배포를 자동화시켜주는 오픈소스 엔진으로 마이크로서비스 아키텍처와 함께 각광받고 있는 엔진이다. 

서버 환경이 전통적인 온프레미스 환경에서 클라우드로 바뀌면서 가상서버를 손쉽게 늘리고 관리할 수 있게 되었지만 이에 따른 배포는 불편한 점이었다. 
Docker가 제공하는 경량화된 가상화 컨테이너 기술은 환경의 배포와 확장을 하는데 엄청난 이점을 제공해준다.

![image](https://user-images.githubusercontent.com/87262811/210510036-0ab2f630-edef-42b6-9949-56b08e97d72e.png)

Docker 는 Container 와 Image 라는 개념으로 구성되며, Network 및 Data 와 같은 리소스들을 각 엔진별로 다룰 수 있고 이를 위한 인터페이스로 Docker 서버에서 REST API 를 제공한다.

![image](https://user-images.githubusercontent.com/87262811/210501063-a34bf59a-b250-42fb-a8aa-5dd9dc71577a.png)
맥이나 윈도우에선 가상환경위에 리눅스를 깔아서 도커를 실행하기 때문에 더 느림..

![image](https://user-images.githubusercontent.com/87262811/210512114-579f81a0-6e31-42ad-b68a-223a2952f89c.png)
*도커 허브 : 깃 허브 같은 이미지파일들이 공유되어있는 홈페이지
*이미지 : Docker 컨테이너를 만들기 위한 Read Only Layer
*컨테이너 : 실행가능한 Docker 이미지
