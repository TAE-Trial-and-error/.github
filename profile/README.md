## TAE-Trial-And-Error 
![header](https://capsule-render.vercel.app/api?type=waving&color=D3E3FD&height=300&section=header&text=TAE-Trial-and-error&fontSize=90)
 
<hr/>

##  💻member

|이름|깃허브 주소|
|---|---|
|윤창욱|[changukdfwe의 github](https://github.com/changukdfwe)|
|박경빈|[acbine의 github](https://github.com/acbine)|
|박재웅|[pjw2229의 github](https://github.com/pjw2229)|
|한종혁|[1arged의 github](https://github.com/1argeD)|

## WE MAKE

<hr/>

## ⚽troubleshooting 
|트러블| 내용 | 해결방안 |
|---|---|---|
|css 오류 |탭 구현시 모든 CSS를 불러와서 div,td,tr 등 해당 요소에 직접적으로 스타일을 변경했을 경우 일부 기능들이 적용되지 않거나 css가 깨지는 오류 발생|원래 보이는 화면은 통일 시키려고 했기 때문에 큰 문제는 아니었다. 같은 형식으로 맞추거나 css를 해당 요소에 직접 주지 않는 식으로 구현하여 해결|
|script 오류|탭으로 구현시 total의 js로 만들어 진 html 이기 때문에 스크립트를 생성하지 못하여, 프론트의 기능들이 동작하지 않았음.|메인페이지의 total.js에 필요한 함수를 다른 html의 스크립트를 직접 넣는 식으로 구현을 해결을 하였음. 하지만, 이렇게 구현하니 팀원 4명이 같은 js파일을 수정해야하는 상황이 발생하여, html에 필요한 js파일을 불러오는 스크립트를 작성하도록 구현해주는 형식으로 해결함.|
|js 파일 오류|탭 구현시 비동기적으로 해당 페이지를 불러오기 때문에 페이지 로딩이 필요한 경우 일부 함수들이 작동되지 않았다.|위의 문제를 해결하고 나서 생긴 오류로 탭 비동기적으로 탭의 html 일부만 변경되기 때문에 서버의 응답이 해당 html로 갔을 경우 total에는 적용되지 않는 오류가 발생하였다. 이런 부분의 비동기가 필요할 경우 동기적으로 작업하던 클라이언트에서 ajax와 xmlhttprequest를 통해서 비동기적으로 요청을 보내고 서버에서는 화면이 그려지지 않는 RestController와 @ResponseBody 등 JSON을 통해 정보만 전달하도록 구현하였다. |
|시큐리티 쿠키|세팅한 쿠키가 스큐리티에 막혀서 작동 되지 않음|로그인 기능과 통합을 하면서 시큐리티가 화면을 유지 시켜주기 위해서 사용된 쿠키를 막아서 생긴 오류로 시큐리티의 HttpFirewall(잠재적인 위험이나 동작들을 차단해주는 인터페이스)에 DefaultHttpFirewall로 방화벽이 막고 있던 쿠키를 허용 하도록 설정하여 해결하였다. |
|시큐리티 iframe|iframe이 보안상의 문제로 권유되지 않는 형식이라 스프링 시큐리티에서 제한을 하여 팝업창을 열리지 않았음.| SecurityFilterChain에서 해더를 frameOptionsConfig.sameOrigin()으로 같은 도메인에서는 접근이 가능하더록 설정하여 해결해였다.|

<hr/>


## useStack
<div align="center">
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=Conda-Forge&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=Spring&logoColor=white" />
  <img src="https://img.shields.io/badge/H2 database-007396?style=flat&logo=H2 database&logoColor=white" />
  <img src="https://img.shields.io/badge/thymeleaf-white?style=flat&logo=thymeleaf&logoColor=green" />
  <img src="https://img.shields.io/badge/javascript-yellow?style=flat&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/lombok-red?style=flat&logo=lombok&logoColor=black" />
  <img src="https://img.shields.io/badge/springsecurity-6DB33F?style=flat&logo=lombok&logoColor=6DB33F" />
  <img src="https://img.shields.io/badge/springboot-6DB33F?style=flat&logo=lombok&logoColor=6DB33F" />
  <img src="https://img.shields.io/badge/mysql-4479A1?style=flat&logo=mysql&logoColor=#479A1" />
<div>


