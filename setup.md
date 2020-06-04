# FPGA Loopback using Zedboad
Zedboard에서 loopback을 구현해보자.
> Zedboard, Vivado v2018.2 (64-bit), Windows
***
## Vivado 다운받기
#### 다운로드
[여기](https://www.xilinx.com/support/download.html)에서 회원가입 후 WebPACK(무료 버젼)을 설치한다. 이 튜토리얼에서는 Vivado v2018.2 (64-bit)를 윈도우에서 사용한다.
#### 설치
설치가 완료되면 xsetup.exe를 실행하여 설치한다.
#### 라이센스 등록
[라이센스 센터](https://www.xilinx.com/getlicense)에서 ISE WebPACK License를 다운받는다. Manage Xilinx License 프로그램을 실행시켜 Load License 메뉴에서 Copy License를 클릭해 다운받은 라이센스를 등록한다.

##### 다운받은 프로그램들
1. Vivado design suite  


2. Vivado HLS : High Level Synthesis  
C, C++로 쉽게 FPGA를 프로그래밍하고 보드의 CPU에 소프트웨어를 돌릴 수 있도록 한다.

3. Vivado SDK : Software Development Kit

***
## 1. Zedboard에 Base System 구현하기
Zynq 보드에 아무 기능을 하지 않는 시스템을 구현하고, 이를 간단한 소프트웨어와 함께 보드에 프로그래밍한다. CPU가 간단한 어플리케이션을 실행하여 컴퓨터의 console에 Hello world를 출력하도록 한다. 이 과정은 6단계를 통해 진행된다.
(참고한 [사이트](http://www.fpgadeveloper.com/2014/07/creating-a-base-system-for-the-zynq-in-vivado.html)와 [유튜브](https://www.youtube.com/user/mamsadegh2/feed))
> Keyword : PL vs PS, AXI interface, Bitstream, Vivado SDK, xmd

### 1.1. 새로운 Vivado Project 만들기
새로운 RTL 프로젝트를 생성한다.


### 1.2. HDL Wrapper 생성하기

### 1.3. Bitstream 생성하기

### 1.4. 하드웨어를 Vivado SDK로 내보내기

### 1.5. 소프트웨어 개발

### 1.6. Test


***
## 2. Zedboard에 Loopback 구현하기
