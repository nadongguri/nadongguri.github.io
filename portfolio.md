# Portfolio


## Tizen TV graphics device driver 개발 (2013.09 ~ )
![](/image/bootlogo_driver.png)

TV가 처음 켜지는 과정에서 HW와 SW의 초기화가 이루어 지며 일정 시간이 소요되므로 이 때 boot logo가 화면에 표시 됩니다.

일반적으로 HW module과 device driver는 1:1대응이 되기에 초기 logo 표시를 위한 관련 module을 제어하고 

해당 module에 대응하는 driver간 자원 공유를 관리하는 driver를 설계/개발하였습니다.


## 2D display HW simulator 개발 (2011.09)
![](/image/2D_simulator.png)

개발언어 : C

Display HW module 검증을 목적으로 제작되었습니다.


User library의 API interface를 유지하며 Simulation layer를 제작하고
HW module은 Verilog 코드를 C로 변환하여 동일한 입력값을 HW와 SW simulator에 주었을 때 같을 결과값이 나오도록 하였습니다.


## Tizen mobile reference application 개발(2010.08 ~ 2010.12)
{% include youtube.html id="PVnJXEfA3A8" %}  

개발언어 : C++, C

Tizen platform 개발 초기 mobile용 reference
bluetooth, search, email applicaion을 개발하였습니다.


## DLNA기기 연결간 AR 활용 방안 선행 개발(2010.04 ~ 2010.07)
{% include youtube.html id="qfkhUQN5xhY" %}  

개발언어 : Java, C++

DLNA 기기들을 QR코드 마커를 이용 AR로 Server와 Player를 찾고 연결하는
Android application을 개발 하였습니다.

## 모바일 게임 개발(2010.03 ~ 2010. 06)
{% include youtube.html id="SvlgI1kM3fk" %}  

개발언어 : Objective-C, Lua

음악 리듬에 맞춰 터치하며 점수를 얻는 게임으로
게임 기획, 스크립트 작성을 하였습니다.


## 3D wave simulation game using DirectX(2009.11 ~ 2010.02)
{% include youtube.html id="978twYe2kck" %}  

개발언어 : C++

3D로 표현한 파형 simulation에 게임을 접목시킨 프로젝트로
게임 로직, 물 수제비(단순 알고리즘으로 표현), BGM 부분을 맡았습니다.


## ETC
### 개발 관련 반복되는 작업들은 python이나 bash로 자동화 코드를 작성하여 사용 및 동료 개발자에 배포합니다.
### 아래 3개의 오픈소스 프로젝트에 컨트리뷰션 중입니다.
* [node-addon-api](https://github.com/nodejs/node-addon-api) : node.js의 N-API를 C++로 wrapping한 module로 testcode 작성에 기여 중입니다.
* [bacardi](https://github.com/lunchclass/bacardi) : node-addon-api와 같 native language binding을 지원하는 모듈로 동료들과 만든 프로젝트입니다.
* [absolute](https://github.com/lunchclass/absolute) : PWA기반 O2O 서비스 제공 platform로 동료들과 만든 프로젝트입니다.
