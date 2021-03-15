# thymeleafBase

## 프로젝트 세팅 방법
---
### 1. Download Zip 또는 git clone
---
### 2. 로컬 pc에 프로젝트를 받아왔다면, eclipse실행
---
### 3. import project
---
#### 1. Existing Gradle Project
#### 2. setting.gradle의 프로젝트이름과 동일한지 확인
  ``` gradle
  rootProject.name = 'demo'
  ```
  ``` gradle
  rootProject.name = '${프로젝트 폴더 이름}
  ```
#### 3. Refresh Gradle Project

#### 4. Boot Dashboard 활성화

#### 5. 추가된 프로젝트 실행

#### 6. 접속 확인
- [타임리프 Hello World](http://localhost:8090/sample/ex1)
- [타임리프 반복문](http://localhost:8090/sample/ex2)
- [로그인폼1](http://localhost:8090/sample/loginForm/login1)
- [로그인폼2](http://localhost:8090/sample/loginForm/login2)
- [로그인폼3](http://localhost:8090/sample/loginForm/login3)
- [로그인폼4](http://localhost:8090/sample/loginForm/login4)
- [로그인폼5](http://localhost:8090/sample/loginForm/login5)
- [로그인폼6](http://localhost:8090/sample/loginForm/login6)
- [로그인폼7](http://localhost:8090/sample/loginForm/login7)
- [로그인폼8](http://localhost:8090/sample/loginForm/login8)
- [ADMIN LTE 메인 1](http://localhost:8090/sample/admin/index)
- [ADMIN LTE 메인 2](http://localhost:8090/sample/admin/index2)
- [ADMIN LTE 메인 3](http://localhost:8090/sample/admin/index3)
---
> 부트스트랩 : 기본적인 레이아웃으로 구성된 css 라이브러리
---
> Admin LTE : 부트스트랩 기반으로 자주사용하는 화면구성 템플릿 제공
  >> 차트, 테이블, 검색, 카드, 게시판, 갤러리 프로필 등등...
---
> thymeleaf : jsp와 동일한 메커니즘으로 서버사이드 템플릿 엔진 중 하나
  >> 레거시 spring은 jsp를 주로 해왔기때문에 springboot에서도 jsp가 친숙하지만
  >> jsp보다 가볍고, 문법이 단순하여 springBoot의 표준 템플릿엔진으로 채택되었다.
  >> java진영의 템플릿엔진 중 러닝커브가 가장 낮아 신규프로젝트일 경우, 타임리프를 선택하는 경우가 많음.
  
    
