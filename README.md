# spring-gift-order

## step1
- 기능 요구 사항
  - 카카오 로그인을 통해 인가 코드를 받고, 인가 코드를 사용해 토큰을 받은 후 향후 카카오 API 사용을 준비한다.
  - 카카오계정 로그인을 통해 인증 코드를 받는다.
  - 토큰 받기를 읽고 액세스 토큰을 추출한다.
  - 앱 키, 인가 코드가 절대 유출되지 않도록 한다.
  - 특히 시크릿 키는 GitHub나 클라이언트 코드 등 외부에서 볼 수 있는 곳에 추가하지 않는다.