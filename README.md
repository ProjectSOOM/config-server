## SOOM Config Server
각 서비스의 구성정보(application.yml)를 동적으로 불러올 수 있게 해주는 Config Server 입니다.

ConfigData 레포지토리에 구성정보들을 저장하여 사용합니다.

[Config Data Repository 바로가기](https://github.com/ProjectSOOM/config-data)

### 환경변수
|Variable|Description|
|---|---|
| CONFIG_SERVER_PORT | ConfigServer 의 포트번호 |
| CONFIG_SERVER_ADDRESS | ConfigServer 의 호스트이름 혹은 ip주소 |
| EUREKA_SERVER_PORT | EurekaServer 의 포트번호 |
| EUREKA_SERVER_ADDRESS | EurekaServer 의 호스트이름 혹은 ip주소 |
| EUREKA_SERVER_HOSTNAME | EurekaServer 의 호스트이름(for instance) |
| EUREKA_SERVER_DEFAULT_ZONE | EurekaServer Default Zone |
| GIT_REPO_URL | Config Data 를 담은 Repository 의 URL |
| GIT_ID | Repository 접근 권한을 가진 계정의 ID |
| GIT_PERSONAL_ACCESS_TOKEN | Repository 접근 권한을 가진 계정의 [토큰](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) |