### 컨테이너 기술이란?

리눅스에서 제공하는 개발환경 격리 기술.
기본적으로 host OS의 커널을 공유하고 host os에 없는 부분만 따로 사용함.

### 도커란?
컨테이너 기술을 사용해 프로세스를 컨테이너로 실행하고 관리하는 오픈 소스 프로젝트.
개발환경을 이미지라는 형태로 저장할 수 있게 하여 애플리케이션마다 개발환경 관리를 용이하게 함.

### 도커 파일, 도커 이미지, 도커 컨테이너의 개념
도커 파일: 도커 이미지를 만드는 파일. OS 이미지를 기반으로 필요한 이미지를 쌓고, 필요한 파일을 추가하는 형태로 내가 실행할 프로그램을 도커 이미지로 만드는 파일.
도커 이미지: 서비스 운영에 필요한 서버 프로그램, 소스코드 및 라이브러리, 컴파일된 실행 파일을 묶는 형태. 레이어 형태로 여러 개의 이미지를 묶어서 하나의 이미지로 만들 수 있음.
도커 컨테이너: 이미지를 컨테이너 기술 상에서 실행한 상태