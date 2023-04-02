- 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)
	애플리케이션과 필요한 모든 파일을 하나의 런타임 환경으로 묶는 데에 사용하는 기술이다.  컨테이너는 단일 구성 단위로서 모든 컨텍스트의 모든 운영 체제에서 쉽게 이동하거나 실행할 수 있다. 즉, 어떤 환경에서나 실행하기 위해 필요한 모든 요소를 포함하고 있는 소프트웨어 패키지이다.
- 도커란 무엇입니까? (100자 이내로 요약)
	리눅스 컨테이너에 리눅스 애플리케이션을 프로세스 격리 기술을 사용하여 더 쉽게 컨테이너로 실행하고 관리하 ㄹ수 있게 해주는 오픈소스 프로젝트이다. 여기서 도커는 일반적으로 도커 엔진이나 도커에 관련된 모든 프로젝트를 말한다.
- 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?	도커 파일은 도커에서 이미지를 생성하기 위해 작성하는 파일이다. 도커 파일 내에는 생성할 이미지에 대한 정보를 작성한다. 즉, 이미지 생성을 위한 템플릿이라고 생각하면 된다.
	도커 이미지는 서비스 운영에 필요한 서버 프로그램, 소스코드, 라이브러리, 컴파일된 실행 파일을 묶어놓은 것이다. 즉, 컨테이너를 생성하거나 실행하는 데에 필요한 모든 파일과 설정값을 지닌 파일이다.
	도커 컨테이너는 이미지를 실생한 상태로 응용 프로그램의 종속성과 함께 응용 프로그램 자체를 패키징 혹은 캡슐화하여 격리된 공간에서 프로세스를 동작시키는 기술이다.
	도커 파일은 도커 이미지 생성을 위한 것이고 도커 이미지는 도커 컨테이너 생성 및 실행을 위한 것이다.

