1. HTTP/1.1 의 Host 헤더를 해석하세요.

 -> 구현하지 못했습니다.
 
 
2. 다음 사항을 설정 파일로 관리하세요.

 -> application-properties.json 파일로 관리
 
 -> 8000 포트에서 동작
 
 -> host별로 root-directory는 다르게 구현하지 못했습니다.
 
 -> 403,404,500 오류 html 파일 이름 저장
 
 
3. 403, 404, 500 오류를 처리합니다.

 -> 설정 파일 활용하여 오류 핸들링
 
 
4. 다음과 같은 보안 규칙을 둡니다.

o 다음 규칙에 걸리면 응답 코드 403 을 반환합니다.

▪ HTTP_ROOT 디렉터리의 상위 디렉터리에 접근할 때

▪ 확장자가 .exe 인 파일을 요청받았을 때

 -> RequestProcessor.java 에서 처리
 
 
5. logback 프레임워크 http://logback.qos.ch/를 이용하여 다음의 로깅 작업을 합니다.

 -> 구현하지 못했습니다.
 
 
6. 간단한 WAS 를 구현합니다.

 -> httpServer.java, RequestProcessor.java 등올 통해 구현
 
 -> http://localhost:8000/Hello --> Hello.java 로 매핑 구현
 
 -> http://localhost:8000/service.Hello --> service 패키지의 Hello.java 로 매핑 구현
 
 
7. 현재 시각을 출력하는 SimpleServlet 구현체를 작성하세요.

 -> http://localhost:8000/Time 으로 구현
 
 
8. 앞에서 구현한 여러 스펙을 검증하는 테스트 케이스를 JUnit4 를 이용해서 작성하세요

 -> 구현하지 못했습니다.
