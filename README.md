# MultiPlayTest

tsconfig.json에서 "./index.d.ts", "./" 비교 하였을때, 유저들이 건의한 에러와 같은 에러가 발생하는것을 확인 하였습니다.
두 경우 모두 Play는 가능하나, "./index.d.ts"의 경우 QR코드 생성시 
System.Exception: (node:69498) UnhandledPromiseRejectionWarning: Error: [tsl] ERROR
      TS2688: Cannot find type definition file for './index.d.ts'.와같은 에러가 발생합니다.
"./"의 경우 QR코드 생성에도 문제가 없습니다.
