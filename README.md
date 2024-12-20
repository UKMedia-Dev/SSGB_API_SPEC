# SSGB_API_SPEC
## API 명세 주소
- 사용자 기능: https://sotalk-api-spec.netlify.app
- 관리자 기능: https://sotalk-api-spec.netlify.app/admin.html

## Mock Server
- OAS 파일을 통한 목 서버 생성 방법 (https://www.npmjs.com/package/@stoplight/prism-cli?activeTab=dependents)
- 여러 상태 코드의 응답을 받는 방법(https://github.com/stoplightio/prism/blob/master/docs/getting-started/03-cli.md#modifying-responses)

### 목 서버 실행 방법

**사전 준비**
```shell
npm i @stoplight/prism-cli
```
**실행 명령어**
```shell
# 사용자 기능 
prism mock https://sotalk-api-spec.netlify.app/openapi.yml
# 관리자 기능
prism mock https://sotalk-api-spec.netlify.app/openapi-admin.yml
```

## 참고자료
- [How to embed code from Swagger UI directly into HTML](https://swagger.io/docs/open-source-tools/swagger-ui/usage/installation)
