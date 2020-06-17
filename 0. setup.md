# FPGA Loopback using Zedboad
Zedboard에서 loopback을 구현해보자.
> Zedboard, Vivado v2018.2 (64-bit), Windows, Putty
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
C, C++로 쉽게 FPGA를 프로그래밍하고 보드의 CPU에서 소프트웨어를 실행시킬 수 있도록 한다.

3. Vivado SDK : Software Development Kit  
Software IDE로, bitstream을 FPGA에 프로그래밍하고 software application을 실행시킨다.

***
이어지는 튜토리얼
## 1. Zedboard에 Base System 구현하기
## 2. Zedboard에 Loopback 구현하기
