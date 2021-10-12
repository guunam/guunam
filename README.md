- HTTP/1.1 의 Host 헤더를 해석하세요.
	- 구현하지 못했습니다.

- 다음 사항을 설정 파일로 관리하세요.
	- application-properties.json 파일로 관리
	- host별로 root-directory는 다르게 구현하지 못했습니다.
	
- 403, 404, 500 오류를 처리합니다.
	- 설정 파일 활용하여 오류 핸들링

- 다음과 같은 보안 규칙을 둡니다.
	- RequestProcessor.java 에서 처리

- logback 프레임워크 http://logback.qos.ch/를 이용하여 다음의 로깅 작업을 합니다.
	- 구현하지 못했습니다.

- 간단한 WAS 를 구현합니다.
	- httpServer.java, RequestProcessor.java 등올 통해 구현
	- http://localhost:8000/Hello --> Hello.java 로 매핑 구현
	- http://localhost:8000/service.Hello --> service 패키지의 Hello.java 로 매핑 구현

- 현재 시각을 출력하는 SimpleServlet 구현체를 작성하세요.
	- http://localhost:8000/Time 으로 구현

- 앞에서 구현한 여러 스펙을 검증하는 테스트 케이스를 JUnit4 를 이용해서 작성하세요
	- 구현하지 못했습니다.
