---
layout: home
---

# 개발자를 위한 Linux

리눅스는 기업이나 산업현징에서 사용되는 대용량 컴퓨터의 운영체계인 유닉스 OS 와 기능이 동일한 개방형 운영체계로 시작되었지만, 현재는 많은 게발자의 자발적 참여틀 통하여 정보 시스템을 제공하기 위한서버 운영체계의 큰부분을 차지하고 있다.  

더옥이 개인용 컵퓨터의 윈도우 운영체계틀 대신하는 개방형 운영체계를 비롯하여하여 모바일 스마트폰을 구성히는 운영체계에서도 리눅스가 사용되고 있다. 리눅스 운영체제에 대해서 알아보도록 한다.  


## 01.리눅스와 소개
---
리눅스는 컴퓨터 운영체제 중 하나로, 소스코드를 공개하고 무료로 배포하는 오픈소스 소프트웨어입니다

### 01-1.운영체제
컴퓨터 운영체제는 컴퓨터 하드웨어와 소프트웨어 간의 인터페이스 역할을 하며, 사용자와 컴퓨터 자원 간의 상호작용을 관리하는 소프트웨어입니다.  

* [운영체제란?](/prologue/os)
운영체제는 컴퓨터 시스템의 핵심 요소 중 하나입니다. 또한, 하드웨어를 초기화 하고 운영체제를 호출하는 시스템에 대해서도 같이 알아 봅니다. 
  * [bios](/prologue/os/bios)
  * [firmware](/prologue/os/firmware)

* [인터페이스](/prologue/os/interface)
운영체제의 인터페이스는 일반적으로 사용자가 시스템과 상호작용하는 방식을 정의하며, 시스템의 기능을 사용하고 다룰 수 있는 방법입니다.
  * cli
  * gui
  * api

* [운영체제의 종류](/prologue/os/type)

### 01-2.리눅스란?
리눅스는 유닉스(UNIX)와 유사한 기능을 갖춘 오픈 소스 운영체제입니다. 유닉스는 초기에는 주로 대형 컴퓨터 시스템에서 사용되었지만, 리눅스의 등장으로 개인용 컴퓨터나 서버 등 다양한 기기에서 사용되고 있습니다. 

* [유닉스](/prologue/unix)
* [솔라리스](/prologue/solaris)
* [리눅스](/prologue/linux)


### 01-3.개발자로서 리눅스
개발자라면 리눅스 운영체제 환경에 많이 노출이 될 것입니다. 이제는 개발자라면 리눅스 운영체제를 알고 사용해야 하는 것은 필수가 되어 가고 있습니다.

* [오픈 소스 운영체제](/prologue/develop)
* [다양한 개발 도구 지원](/prologue/develop)
* [안정성과 보안성](/prologue/develop)
* [높은 성능](/prologue/develop)

### 01-4.[리눅스의 종류](/prologue/distribution)
리눅스는 다양한 배포판(distribution)이 존재합니다. 이러한 배포판은 서로 다른 특징과 용도를 가지고 있으며, 사용자들은 자신의 필요에 맞게 선택할 수 있습니다.  

* [배포본이란?](/prologue/distribution)
* [오픈소스 라이센스](/prologue/opensource)

### 01-5.[리눅스 운영체제의 구조](/prologue)
리눅스 운영체제의 핵심은 바로 `커널`입니다. 또한, 대부분의 조작은 cli 명령을 통하여 실행됩니다. 일부 gui 환경을 위하여 x-windows 시스템을 제공합니다.

* [커널](/prologue/kernel)  
리눅스 커널은 운영 체제의 핵심을 이루는 소프트웨어로, 하드웨어와 소프트웨어를 관리하고 운영체제의 기능을 제공합니다.

* [cli](/prologue/cli)  
CLI(Command Line Interface)는 사용자가 텍스트 명령어를 입력하여 컴퓨터와 상호 작용하는 인터페이스입니다.

* [x-window](/prologue/xwindow)  
X Window System은 리눅스와 같은 운영 체제에서 GUI(Graphical User Interface)를 생성하기 위한 오픈 소스 소프트웨어입니다.

### 01-6.[리눅스의 활용](/prologue/application)
리눅스는 서버, 클라우드, 임베디드 시스템, 슈퍼컴퓨팅 등 다양한 분야에서 활용됩니다.
* 서버
* 클라우드
* 슈퍼컴퓨팅

#### 임베디드 시스템
Embedded Linux는 임베디드 시스템에서 사용하도록 설계된 특수 운영 체제로, 임베디드 애플리케이션을 개발하고 배포하기 위한 가볍고 유연한 플랫폼을 제공합니다.  
* [라즈베리파이](/prologue/iot)

## 02.리눅스 [설치](/setup)
---
리눅스를 설치하는 방법에 대해서 학습합니다. 리눅스의 설치는 크게 물리적 설치, 가상머신, Subsystem 방식으로 설치하여 사용할 수 있습니다.

### 02-1.다운로드 및 인스톨러
리눅스 설치를 위한 iso 설치 이미지를 다운로드 받습니다.
* [iso이미지란](/setup/iso) :
CD, DVD 또는 USB 드라이브와 같은 저장 매체에 복사하여 사용할 수 있는 운영 체제 또는 소프트웨어의 설치 파일입니다.
* [인스톨러](/setup/installer) :
프로그램 인스톨러는 컴퓨터에 소프트웨어를 설치하기 위한 프로그램이며, 설치 과정에서 필요한 작업들을 자동화하여 사용자에게 편의성을 제공합니다.

### 02-2.배포본별 설치방법
인스톨러는 각 배포판마다 다르며, 사용자에게 직관적이고 간편한 설치 경험을 제공하기 위해 지속적으로 업데이트되고 개선됩니다.  

* [Ubuntu](/setup/ubuntu) :
우분투 리눅스는 데비안 계열의 리눅스 배포판으로, 사용하기 쉽고 안정적인 운영체제입니다. 무료로 사용할 수 있으며, 개발 및 서버 운영 등 다양한 분야에서 활용됩니다.  

* [CentOS](/setup/centos) :
CentOS Linux는 Red Hat Enterprise Linux (RHEL)의 무료 클론 버전으로, 안정성과 보안성이 뛰어난 서버 운영체제입니다.  

* [OracleLinux](/setup/oracle) :
Oracle Linux는 Red Hat Enterprise Linux과 100% 호환되는 무료 및 오픈 소스 리눅스 배포판으로, 엔터프라이즈 환경에서 최적화되어 있습니다.

* [rocky](/setup/rocky) :
Rocky9 Linux는 CentOS를 기반으로 만들어진 무료 및 오픈 소스 리눅스 배포판입니다.

### 02-3.윈도우 서브시스템 WSL
WSL(Windows Subsystem for Linux)은 윈도우 운영체제에서 리눅스 커널을 실행하여 리눅스 환경과 동일한 명령어와 도구를 사용할 수 있도록 하는 기술입니다.  
* [wsl 배경](/setup/wsl)
* [wsl 시스템](/setup/wsl/system)

#### WSL 배포판 및 설치
* [wsl 배포판](/setup/wsl/distribution)
* [wsl 설치 및 명령어](/setup/wsl/command)



### 02-4.[가상머신](/setup/virtual)
가상머신은 호스트 운영체제 위에서 다른 운영체제를 실행시키는 가상 환경을 제공하는 소프트웨어입니다.  

* [Virtualbox](/setup/virtual/virtualbox)  
VirtualBox는 x86 가상화를 제공하는 무료 오픈 소스 가상화 소프트웨어입니다.

* [VMWare](/setup/virtual/vmware)  
VMware는 가상화 기술을 사용하여 가상 컴퓨터를 만들어주는 소프트웨어 회사dml 제품 입니다.

### 02-5.물리적 설치
베어메탈 서버는 가상화 기술을 사용하지 않는 하드웨어 가상화 기술을 의미합니다. 
* [Bare-Metal](/setup/bare)
* [멀티부팅](/setup/bare/multiboot)

### 02-6.[호스팅 서비스](/setup/hosting)
호스팅 서비스에서도 다양한 리눅스 운영체제 시스템이 적용되고 있습니다.
* [서버호스팅](/setup/hosting/server)
* [웹호스팅](/setup/hosting/web)
* [클라우드](/setup/cloud)
리눅스 클라우드는 인터넷을 통해 가상화된 리눅스 서버 및 서비스를 제공하는 클라우드 컴퓨팅 서비스입니다. 

  * [가상화란?](/setup/cloud/virtual)

## 03.[기초 사용법](/start)
---
리눅스를 설치하였다면, 이제 리눅스 운영체제를 사용해 보도록 합니다. 먼저 가장 기초적인 리눅스 조작방법에 대해서 알아 보도록 합니다.

### 03-1.사용자 관리
리눅스는  보안과 유지 보수를 위하여 다양한 사용자 관리 시스템을 적용하고 있습니다.

#### 3.1.1.[다중 사용자 시스템](/start/multi)
다중 사용자 시스템이란 여러명의 사용자가 동시에 간은 OS에 접근하여 사용을 할 수 있다는 의미 입니다.

* [사용자 자원 공유](/start/share)
* [사용자 보안](/start/secure)
* [효율성](/start/usefull)
* [유지 보수](/start/maintance)

#### 3.1.2.[사용자관리](/start/user)
리눅스는 사용자 계정과 권한을 관리하기 위해 UID(사용자 식별자)와 GID(그룹 식별자)를 사용합니다.
* [사용자 목록](/start/user/list)
* [계정관리](/start/user/account)
* [비밀번호 관리](/start/user/password)

#### 3.1.3.[그룹관리](/start/group)
리눅스에서 사용자 그룹은 여러 사용자들을 논리적으로 묶어서 권한과 자원에 대한 접근 제어를 관리하는 기능을 말합니다.
* [그룹이란](/start/group)
* [그룹관리 명령어](/start/group/command)

### 03-2.접속 및 로그인
리눅스에서 로그인(Login)이란, 사용자가 자신의 계정으로 시스템에 접근하여 작업을 시작하는 것을 말합니다.  

#### 03-2.1.접속 프로세스
* [로그인 이란](/start/login)
* [로그인 기록](/start/login/log)

#### 03-2.2.접속해제
* [로그아웃](/start/logout) : 세션을 종료합니다.
  * [x-window](/start/logout/gui)
  * [콘솔](/start/logout/cli)

#### 03-2.3.가상터미널
* [TTY](/start/tty) : 로그인 화면을 표시하는 `가상 터미널`을 말합니다. 

#### 03-2.4.root사용자
리눅스에서 `root`는 최상위 관리자 계정으로, 시스템의 모든 권한을 가진 사용자입니다.
* [최상위 관리자란?](/start/root)
* [sudo 관리자](/start/root/sudo)
* [su 권환획득](/start/root/su)

### 03-3.에디터 사용하기
리눅스 시스템의 기능 및 설정들은 텍스트 파일로 구성되어 있습니다. 이를 수정하기 위해서는 텍스트 문서 편집기가 필요합니다. 리눅스에서 제공하는 텍스트 편집기의 종류와 사용법에 대해서 알아 보도록 합니다.

* [에디터의 종류](/start/edit)

#### 에디터 사용하기
* [vi](/start/edit/vi)
* [nano](/start/edit/nano)
* [gedit](/start/edit/gedit) 

### 03-4.종료
리눅스는 다중사용자 및 서버용 운영체제를 기반으로 하고 있습니다. 시스템의 안정적인 종료를 위하여 다양한 방법의 시스템 종료 방법들이 존재합니다.  
* [리눅스를 종료하는 방법](/start/out) : 컴퓨터 종료
* [logout](/start/logout) : 세션의 종료


### 03-5.리다이렉션과 파이프
리눅스는 표준 입출력을 제어하여 다양한 출력과 입력을 대체할 수 있습니다.
* [리다이렉션이란](/start/redirection) : 입출력을 제어합니다.
* [파이프란](/start/pipe) : 두 개 이상의 명령어를 조합하여 사용할 때 유용한 기능입니다.


### 03-6.그외기능
리눅스는 콘솔상에서 작업을 편리하게 하기 위한 유용한 기능들을 가지고 있습니다.
* [자동 완성 기능](/start/auto)
* [명령어 그룹핑](/start/grouping)


## 04.[리눅스 시스템](/system)
---
리눅스를 이해하기 위한 기본적인 시스템으로는 파일 시스템, 프로세스, 사용자 계정, 네트워크 등이 있습니다. 파일 시스템은 파일과 디렉토리 구조를 가지고 파일을 관리하며, 프로세스는 실행 중인 프로그램을 의미합니다. 사용자 계정은 사용자 정보를 저장하고 권한을 관리하는 역할을 합니다.  

### 04-1.리눅스 부팅
부팅(Boot)이란 컴퓨터를 켤 때, 운영체제가 실행되기 전에 `초기화` 및 `로딩` 과정을 거치는 것을 말합니다.
* [부팅단계](/system/boot)
  - [BIOS/UEFI](/system/boot)
  - [부트 로더](/system/boot)
  - [커널 로드](/system/boot)
  - [init 프로세스](/system/boot)
  - [런레벨](/system/boot)
  - [로그인](/system/boot)

### 04-2.[파일시스템](/system/file)
파일 시스템은 파일과 디렉토리를 계층적으로 구성하며, 파일과 디렉토리를 관리하는 데 사용됩니다.  

### 운영체제의 파일 시스템
운영체제의 파일 시스템은 하드 디스크나 다른 저장 장치에 파일을 저장하고 관리하는 방식을 결정하는 체계입니다.
* [파일 시스템이란?](/system/file)
* [파일 시스템의 종류](/system/file/ext)

#### 파일과 디렉터리
* [파일이란?](/system/file/file)
* [디렉터리란?](/system/file/directory)
* [경로](/system/file/path)

#### 디스크
리눅스에서 새로운 디스크를 추가하고, 포맷하는 방법에 대해서 알아 봅니다.
* [디스크 관리](/system/disk)
* [디스크 추가](/system/disk/add)
* [디스크 모니터링](/system/disk/monitor)

### 04-3.권환
사용자는서버 시스템을사용할수 있는 범위의 제한을가지고파일과 디렉토리 등에 접근할 수 있도록 되어 있다.
* [소유권](/system/ownership)
* [허가권](/system/permit)


### 04-4.프로세스 관리
프로세스(Process)는 실행 중인 프로그램을 의미하며, 컴퓨터 시스템에서 작업의 기본 단위입니다. 각 프로세스는 독립된 메모리 공간과 실행 상태를 가지며, 운영체제에 의해 관리됩니다.  

#### 04-4.1.프로세스
운영체제의 프로세스는 실행 중인 프로그램으로, 시스템에서 할당 받은 자원을 이용하여 작업을 수행합니다.
* [프로세스란?](/system/process)
* [프로세스 제어](/system/process/run)  
* [프로세스 명령어](/system/process/command)  

#### 04-4.2.서비스 프로세스
서비스는 백그라운드에서 실행되며, 시스템에서 제공하는 기능이나 애플리케이션을 제어하는 데 사용되는 프로그램입니다.
* [서비스(데몬)](/demon)

### 04-5.프로세스 스케쥴
운영체제의 프로세스 스케줄링은 CPU 자원을 효율적으로 분배하고, 프로세스 실행 순서를 결정하는 것을 말합니다. 

#### 04-5.1.스케쥴러
스케줄링은 시스템에서 실행할 프로세스를 선택하고 CPU 자원을 할당하는 작업을 의미합니다. 
* [스케쥴이란](/system/schedule)
* [스케쥴이란 알고리즘](/system/schedule/algorism)

#### 04-5.2.스케줄러의 종류
프로그램을 자동으로 매일, 매시간 반복 실행시켜야 되는 경우가 있습니다. 리눅스가 자동으로 프로그램을 실행하는 방법등 2가지가 있습니다.  
* [crontab](/system/schedule/crontab) : 주기적으로 실행
* [inittab](/system/schedule/inittab) : 리눅스가 시작될때 자동실행

### 04-5.시스템 설정
리눅스 설치 및 동작을을 위한 다양한 설정 방법에 대해서 알아 보도록 합니다.

#### 04-5.1.[시스템체크](/system/check)
* 버젼체크
* hostname


#### 04-5.2.시간대 설정
서버의 설정이 한국/서울로 안되어 있는 경우가 있습니다.
* [타임존 설정](/system/setting/time)
* [로케일](/system/setting/locale)




## 05.기본 명령어
---
리눅스를 사용하기 위한 기본적인 명령어들에 대해서 알아 보도록 합니다.

### 05-1.프로그램 설치
리눅스에서 프로그램을 설치하는 방법은 여러 가지가 있습니다. 소스 코드를 컴파일하여 설치하는 방법과 패키지 관리자를 사용한 설치방법이 있습니다.

#### 소스 코드를 컴파일하여 설치하는 방법
리눅스에서는 소스 코드를 직접 컴파일하여 프로그램을 설치할 수도 있습니다. 이 방법은 패키지 관리자를 사용하지 않으므로, 최신 버전의 프로그램을 설치하고자 할 때 유용합니다.  
* [컴파일이란](/system/compile)
* [컴파일 설치](/system/compile/install)

#### 패키지 관리자를 사용한 설치방법
리눅스 배포판마다 다른 패키지 관리자를 사용합니다. 대표적인 패키지 관리자로는 `APT`, `YUM`, `DNF`, `Pacman` 등이 있습니다. 각 패키지 관리자는 고유한 명령어를 제공하며, 해당 명령어를 사용하여 프로그램을 설치할 수 있습니다.  

* [패키지 관리란?](/system/package)

데비안 계열  
* [DPKG와 APT](/system/package/apt)  

래드햇 계열  
* [rpm과 yum](/system/package/yum)
* [dnf](/system/package/dnf)


### 05-2.SSH 설치 및 터미널접속
리눅스 터미널 접속이란, 터미널 프로그램을 사용하여 리눅스 서버나 컴퓨터에 원격으로 접속하는 것을 말합니다. 터미널 접속을 통해 리눅스 시스템을 원격으로 관리하고 작업할 수 있으므로, 서버 운영이나 개발 작업 등에서 필수적인 기술입니다.

#### [원격 접속](/system/remote)  
터미널 접속을 통해 CLI(Command Line Interface)를 통해 리눅스 시스템을 제어하고, 명령어를 입력하여 작업을 수행할 수 있습니다. 

* [ssh](/system/remote/ssh)  
일반적으로 SSH(Secure Shell) 프로토콜을 사용하여 원격으로 터미널 접속을 수행합니다. SSH를 사용하면 인터넷을 통해 안전하게 원격 서버에 접속할 수 있습니다. 

* [telnet](/system/remote/telnet)
Telnet이나 FTP를 사용하여 원격 서버에 접속하는 것이 있지만, 보안상의 이유로 사용되지 않습니다. 

  
#### 클라이언트 접속도구
* [putty 설치](/system/remote/putty) 
* [윈도우터미널](/system/remote/winterm)

### 05-3.GUI 접속도구
gui환경의 작업을 원하는 경우에는 vnc를 이용할 수 있습니다.
* [vnc](/system/remote/vnc)
* 윈도우 원격접속

### 05-4.[기본명령어](/command)
* 도움말
* [명령어 히스토리](/command/history)


## 06.네트워크
---


### 06-1.네트워크 장비(라우팅과 라우터)
네트워크 장비는 컴퓨터 네트워크에서 데이터를 전송하고 수신하는 기능을 담당하는 장치로, 라우터, 스위치, 허브 등이 있습니다. 이들 장비는 네트워크의 안정성과 속도, 보안 등을 유지하고 관리하는 역할을 합니다.  

* [네트워크 구성](/network/wire)
  - 유선네트웍
  - 무선네트웍
* [LAN](/network/hardware)
* [WAN](/network/hardware)
* [스위치와 허브](/network/hardware)
* [ROUTER](/network/hardware)

### 06-2.네트워크 기초
네트워크는 인터넷을 비롯한 다양한 네트워크 환경에서 데이터 통신이 가능하도록 지원합니다. 이러한 시스템들은 리눅스의 기본적인 구성 요소이며, 이를 이해하는 것이 리눅스를 다루는 데 중요합니다.

* [IP 주소](/network/ip)
* [클래스](/network/ip/class)
* [서브넷 마스크](/network/ip/mask)

* [포트](/network/ip/port)
* [소켓](/network/ip/soket)
* [주소체계](/network/ip/address)

* [tcp/ip](/network/tcp)

### 06-3.네트워크 설정과 보안
리눅스에서 네트워크 설정을 위한 방법에 대애허 알아 봅니다. 
* 기본적인 네트워크 명령어의 사용법 (ex. ifconfig, ip, route 등)
* 네트워크 인터페이스의 구성과 설정 방법
* [호스트 이름](/network/host)
* [도메인](/network/domain)
* [Demon](/network)

#### 네트워크 보안 기초
리눅스에서 보안은 시스템 자원 및 데이터를 외부의 공격으로부터 안전하게 보호하는 것을 의미합니다.  

방화벽 설정  
* [방화벽](/network/firewall)
* [ACL](/network/acl)

### 06-4.포트 포워딩 [NAT 설정](/network/nat)
리눅스에서 NAT(Network Address Translation)는 프라이빗 네트워크 주소를 퍼블릭 네트워크 주소로 변환하여 인터넷 접속을 가능하게 하는 기술입니다.  
- [net](/network/nat)
- [포트 포워딩](/network/nat)
  * [virtualBox](/network/nat/virtualbox)
  * [vmware](/network/nat/vmware)


### 리눅스 네트워크 설정
* [ip확인 및 설정](/system/ip)

## 07.도구설정
---
리눅스 환경에서 시스템을 관리하고, 개발을 위한 유용한 도구들을 알아 보도록 합니다.

### 07-1.curl
curl(client url) 명령어는 프로토콜들을 이용해 URL 로 데이터를 전송하여 서버에 데이터를 보내거나 가져올때 사용하기 위한 명령줄 도구 또는 라이브러리 입니다.
* [curl](/tools/curl)

### 07-2.깃 사용하기
소스코드의 버젼이력을 관리하는 형상관리 도구 입니다. 최근에는 소스코드의 개발 배포를 깃을 통하여 서버에 배포를 하고, 문제가 있는 경우 쉽게 이전의 상태로 되도릴 수 있습니다.
* [git 설치](/tools/git)
* 깃허브

### 07-3.vscode 연동
리눅스를 직접 설치한 경우에는 x-window 에서 실행할 수 있는 vscode 코드 편집기를 설치합니다. 또는, wsl과 같은 윈도우 환경의 리눅스라면 remote 연결을 통하여 리눅스의 코드를 변경할 수 있습니다.

* [vscode 설치](/tools/vscode)
* [원격연결](/tools/vscode/remote)


### 07-4.[gcc](/dev/gcc) 및 환경구축
Linux에서 gcc를 설치하여 c언어 프로그램을 작성해 보는 연습을 해봅니다.  
* 설치하기
  - [gcc](dev/gcc) 설치
  - g++ 설치

* configure 와 make

> c언어 문법 및 학습하기


## 08.쉘 프로그래밍
---
셀의 개념과 명령문 처리 방식을 이해한다. 셀 스크립트의 작성과 실행 방법을 익힌다. 다양한 문법을 활요하여 셀 스크립트를 작성한다.  

쉘 스크립트 작성 방법과 실행  
* [리눅스 셀](/shell)
* [Bash 쉘과 변수](/shell)
* [Bash 쉘의 주요기능](/shell)
* [Bash 쉘 스크립트](/shell)  

조건문, 반복문, 함수 등 기본 문법  
* [위치 매개변수](/shell)
* [입력과 출력](/shell)
* [셀 프로그램](/shell)



## 09.[서버스와 데몬](/demon)
---
서비스와 데몬은 백그라운드에서 실행되는 프로그램으로, 서비스는 사용자가 명령어를 입력하여 실행되며, 데몬은 시스템이 부팅될 때 자동으로 실행됩니다.  

### 09-1.서버, 서비스 및 데몬
* [서버란?](/demon/server)
* [데몬이란?](/demon/demon)
* [서비스란?](/demon/service)

### 09-2.데몬의 실행 및 관리
* [systemd란](/demon/systemd)
* [런-레벨](/demon/runlevel)
* [service](/demon/service)  
* [systemctl](/demon/systemctl)  

### 09-3.파일 전송 데몬
다양한 리눅스의 데몬을 학습해 보고 설치를 해보도록 합니다.

* [ftp](/demon/ftp) : 파일올리기
* [Samba](/demon/samba)

### 09-4.도메인 네임 서비스
Linux 서버의 DNS는 도메인 이름을 IP 주소로 변환하여 네트워크의 리소스를 찾고 연결하는 서비스입니다.  
* [dns란?](/demon/dns)
* [dns 수정 및 설정](/demon/dns/setting)

### 09-5.메일 관련 데몬
* [Mail](/demon/mail)

* Postfix 메일 서버 설치와 설정
* Dovecot 메일 서버 설치와 설정



## 10.웹 서버스
---
리눅스의 웹 서비스는 Apache, Nginx 등의 웹 서버 소프트웨어를 사용하여 다양한 웹 사이트 및 웹 어플리케이션을 호스팅하고 제공합니다.

### 10-1.web 서버란
웹 서버는 인터넷 상에서 HTTP를 통해 클라이언트의 요청에 응답하여 웹 페이지나 파일 등을 제공하는 컴퓨터 프로그램입니다.

* [웹서비스란?](/web/service)

#### 리눅스 웹서버
* [Web Server의 역할](/web/server)
* [Web server의 장점](/web/server)
* [웹 서버의 종류](/web/server)


### 10-2.아파치
아파치 웹서버는 가장 대중적인 오픈 소스 웹서버로, HTML 문서 및 웹 페이지를 제공하는 소프트웨어입니다.  

* [아파치란](/web/apache)
* [apt로 설치하기](/web/apache/apt) 
우분투 환경에서 아파치 웹서버를 설치하는 방법에 대해서 알아 봅니다.
* [yum으로 설치하기](/web/apache/yum) 
centOS 환경에서 설치하는 방법에 대해서 알아 봅니다.
* [아파치 설정](/web/apache/conf)


### 10-3.엔진엑스
엔진엑스 웹서버는 가벼우면서도 고성능인 웹 서버로, 동시접속자가 많은 웹사이트나 애플리케이션의 처리에 적합한 소프트웨어입니다.

* [nginx란](/web/nginx)
  * [apt로 설치하기](/web/nginx/apt) 
  * [yum로 설치하기](/web/nginx/yum) 
  * [nginx 설정](/web/nginx/conf)


### 10-4.도메인 설정 및 보완
HTTPS는 데이터를 암호화하여 보안을 유지하므로, 웹사이트에서 민감한 정보를 주고받거나 사용자 인증과 같은 중요한 작업을 수행하는 경우 반드시 사용해야 합니다.

* SSH 서버와 클라이언트

#### HTTPS
* [https란](/web/https)

#### 보안 및 인증서
* SSL 인증서 설치와 설정
* [Let's Encription](/web/https/letsEncription)








### 10-5.Was서버
서버에서 WAS(Web Application Server)란, 웹 애플리케이션을 실행하는 미들웨어로, 웹 서버와 데이터베이스 서버 사이에서 동작하여 애플리케이션의 로직 수행 및 데이터 처리를 담당하는 소프트웨어입니다.  

* [was란](/web/was)
* [was의 역할](/web/was)

### 10-6.연동설정
Web 서버는 정적인 파일 제공과 로드 밸런싱 등의 역할을, WAS는 동적인 데이터 처리와 비즈니스 로직 수행을 담당하여 서로 보완적인 역할을 합니다.

#### [톰켓서버](/web/was/tomcat)
Apache Tomcat은 웹 애플리케이션 배포 및 관리를 위한 플랫폼을 제공하는 오픈 소스 Java 기반 웹 애플리케이션 서버입니다.  
> 톰켓이 실행되기 위해서는 [java가 설치](/dev/java)되어 있어야 합니다.

* [톰켓 버젼](/web/was/tomcat)
  * [tomcat9](/web/was/tomcat/tomcat9) 패키지 설치 방법
  * [tomcat10](/web/was/tomcat/tomcat10) 다운로드 설치 방법

* WAS 연동 및 배포하기  
Tomcat과 Apache를 연결하여 Apache를 프런트 엔드 프록시 서버로 사용하여 정적 콘텐츠를 처리하고 동적 요청을 Tomcat에 전달함으로써 웹 애플리케이션의 성능과 확장성을 개선할 수 있습니다.
  * [deploy](/web/was/tomcat/deploy)
  * [connector](/web/was/tomcat/connector)
    * [아파치연동](/web/was/tomcat/connector/apache)
    * [Nginx연동](/web/was/tomcat/connector/nginx)

#### Weblogic
> 실습 : Weblogic 설치 해보자

## 11.[데이터베이스](/database) 구축하기
---
리눅스에 데이터베이스를 설치하고, 각종 응용 프로그램과 연동하여 서비스를 구동해 보도록 합니다.

### 11-1.데이터베이스란?
데이터베이스 서버에 대하여 좀더 자세히 알아 보도록 합니다.

* 데이터베이스의 종류
다양한 데이터베이스를 설치하고 사용을 해보도록 합니다.  

### 11-2.파일 기반형
SQLite는 경량화된 오픈소스 SQL 데이터베이스 관리 시스템으로, 서버가 필요하지 않으며 파일 기반의 데이터베이스로서 쉽게 이식성이 높은 솔루션으로 사용됩니다.
* [sqlight](/database/sqlight)

### 11-3.관계형
관계형 데이터베이스는 데이터를 테이블 형태로 정리하고, 이를 관계를 이용해 연결시켜 관리하는 데이터베이스 시스템입니다.

* [mysql](/database/mysql)
* [마리아db](/database/mariadb)
* [postgresql](/database/postgresql)
* [oracle](/database/oracle)

### 11-4.NoSQL
noSQL은 관계형 데이터베이스가 아닌 비관계형 데이터베이스를 말하며, 데이터 구조를 자유롭게 구성하고 확장성과 가용성을 높이기 위해 설계된 데이터베이스입니다.
* [몽고DB](/database/mongo)

### 11-5.In Memory 상주형
Redis와 Memcached는 모두 메모리 기반의 key-value 저장소로, 데이터를 캐싱하기 위해 사용되는 NoSQL 데이터베이스입니다.
* [redis](/database/redis)
* memcahe


## 12.개발환경 및 세팅
---
리눅스 서버에서 운영할 수 있는 다양한 개발환경을 설정합니다. 

### [php 개발하기](/dev/php)
php는 웹 응용프로그램을 쉽게 만들수 있는 스크립트 언어 입니다. php를 설치하기 위해서는 먼저 [apache](/web/apache) 또는 [nginx](/web/nginx)와 같은 웹서버가 설치되어 있어야 합니다.

#### PHP 설치 및 테스트
PHP를 설치하고 간단한 구동 코드를 작성해 봅니다.
* [php](/dev/php) 설치
* 컴파일 설치

### PHP와 MySQL 연동

#### PHP 응용프로그램 활용하기
PHP로 작성된 응용프로그램을 설치하고, 운영해 봅니다. 홈페이지, 블로그, 쇼핑몰, 웹하드, ERP등 다양한 오픈소스들이 존재합니다.  
* wordpress를 통하여 웹사이트 실행
* prestashop을 통하여 쇼핑몰구축

#### PHP 언어 학습하기
보다 전문적인 개발을 하기 위해서는 php 언어를 학습해야 합니다. 최신의 php 언어를 학습하기 원한다면 [php.jiny.dev](https://php.jiny.dev) 학습 사이트를 참조하세요.

### [JAVA](/dev/java)
Java는 객체 지향 프로그래밍 언어로, 다양한 플랫폼에서 동작하는 이식성이 높은 언어입니다.  
* [java란?](/dev/java)
* [java 설치하기](/dev/java)

#### JSP 프로그래밍
JSP 프로그래밍은 웹 서버에서 실행할 수 있는 동적 웹 페이지를 만드는 데 사용되는 Java 기반 웹 개발 기술입니다.
* 톰켓설치
* [jsp 및 서블릿](/dev/java/jsp)
* [이클립스 톰켓연동](/dev/java/eclipse)


### [NodeJS](/dev/nodejs)
Node.js는 서버 측 자바스크립트 런타임 환경으로, 비동기 I/O 처리와 이벤트 기반 프로그래밍을 지원하여 높은 성능과 확장성을 가진 언어입니다.
* 노드
* nodeExpress
* deno

#### 노드JS 관리도구
* [Volta](/tools/volta) 는 자바스크립트 도구 관리자 입니다. 
* PM2

### 파이선
파이썬은 인터프리터식, 객체 지향적, 동적 타이핑 대화형 언어로, 간결하고 읽기 쉬운 코드를 작성할 수 있으며 다양한 분야에서 사용되는 인기있는 프로그래밍 언어입니다.  
* [파이선 이란](/dev/python)
* [파이선 설치](/dev/python/setup)
  * 파이선 업그레이드
  * 장고 프레임워크
  * 주피터노트북

### [rust](/dev/rust)
Rust는 시스템 프로그래밍 언어로, 안정성과 속도에 중점을 둔 메모리 안전성을 보장하는 현대적인 언어입니다.  
* [Rustup 설치하기](/dev/rust)
* [PATH 설정하기](/dev/rust)

### [go](/dev/go)
Go는 구글에서 만든 간단하고 빠른 컴파일 언어로, 동시성 및 병행성을 위한 기능을 내장한 인기있는 프로그래밍 언어입니다.
* [Go 다운로드하기](/dev/go)
* [설치 경로 설정하기](/dev/go)
* [환경 변수 설정하기](/dev/go)

## 13.X-Window
Linux X Window는 그래픽을 표시하고 사용자 입력을 관리하기 위한 윈도우 시스템 및 툴킷을 제공하는 그래픽 사용자 인터페이스(GUI)입니다.  
* [x-window란](/xwindow)


## 14.시스템 관리
---
시스템을 위한 리눅스 서버를 운영하는 경우, 시스템 관리를 위하여 네트워크 상황을 상시 모니터링하고 관리해야 하는 업무는 중요한 업무이다.

### 14-1.서버 모니터링과 알림 설정
시스템 모니터링은 서버나 시스템의 성능 및 상태를 지속적으로 감시하여 이상 현상을 조기에 파악하고 대응할 수 있는 작업입니다.  

* [시스템 측정 및 상태](/system/monitor)

* [로그 파일과 시스템 모니터링](/system/monitor/log)
* [패킷 분석 및 디버깅 도구의 사용 방법](/system/monitor/packet)

### 14-2.시스템 백업과 복구
백업 및 복구는 데이터를 잃거나 손상되는 경우를 대비하여 중요한 정보를 보호하기 위해 데이터를 저장하고 복원하는 과정입니다.  
* [tar를 이용한 백업과 복구](/system/backup)
* [rsync를 이용한 백업과 복구](/system/backup)
* [dd를 이용한 백업과 복구](/system/backup)
* [원격 백업](/system/backup)


### 14-3.시스템 로그

### 14-4.외부도구
* Zabbix 서버 설치와 설정

## 15.[클라우드](/cloud)
---
클라우드는 인터넷을 통해 온디맨드로 컴퓨팅 리소스를 제공하는 기술을 말합니다.

* [네이버](/cloud)
네이버 클라우드는 한국내 최대 규모의 클라우드 서비스이며, 안정성과 성능, 한국어 지원 등을 강점으로 갖추고 있습니다.

* [AWS](/cloud)
AWS는 Amazon이 제공하는 클라우드 컴퓨팅 플랫폼으로, 유연한 스케일링과 다양한 클라우드 서비스 제공 등이 특징입니다.

* [Azure](/cloud)
Azure는 마이크로소프트에서 제공하는 클라우드 플랫폼으로, 대규모 응용 프로그램을 구축, 배포 및 관리할 수 있는 다양한 서비스를 제공합니다.

* [google](/cloud)
구글 클라우드는 뛰어난 확장성과 안정성을 갖춘 클라우드 서비스이며, 기계 학습과 인공 지능 분야에서 높은 수준의 지원을 제공합니다.

* [oracle](/cloud)
오라클 클라우드는 기업용 클라우드 서비스로, 기존 오라클 데이터베이스와 호환되며 인프라, 플랫폼, 소프트웨어 서비스를 제공합니다.

* [vultr](/cloud)
Vultr는 저렴한 가격과 고성능의 클라우드 서버 인프라를 제공하는 클라우드 서비스입니다.

## 16.도커
---
도커는 컨테이너 기반의 오픈소스 가상화 플랫폼으로, 소프트웨어를 빠르고 쉽게 개발, 배포 및 실행할 수 있게 해주는 도구입니다.

### 도커
도커는 애플리케이션을 손쉽게 배포, 실행, 관리하기 위한 컨테이너 기반의 오픈소스 플랫폼입니다.  
* 컨테이너란
* [도커 설치](/doker/install)

## 17.마이크로서비스
마이크로서비스 서버 운영은 소프트웨어 개발의 아키텍처 접근 방식으로, 대규모 애플리케이션을 더 나은 모듈성, 유연성 및 안정성을 위해 독립적으로 개발, 배포 및 확장할 수 있는 더 작고 독립적인 서비스로 분할합니다.  


## 18.쿠버네티스
쿠버네티스는 컨테이너화된 애플리케이션의 배포, 확장, 관리를 자동화하는 오픈소스 플랫폼입니다.  
* 쿠버네티스 활성화

## 19.배포
Linux 서버에서 개발된 소스 코드를 배포하는 방법을 알아 봅니다.
* [코드 배포 및 테스트](deploy)

## 20.웹서버 운영
* 웹서버 분산

## 21.데이터베이스
* 리플리케이션
* 데이터베이스 사용자 및 권한 관리
* 백업과 복원

## 22.장애복구
* root 비밀번호 재설정

## 23.보완
* 부트로더 잠금
* Linux 보안 정책

## 24.시스템 관리

### 24-1.스토리지 관리
* 파일 시스템과 디스크 관리
* RAID 구성과 관리
* LVM 구성과 관리


## 참고자료
