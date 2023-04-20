---
layout: home
---

# 사용자
리눅스는 서버 1대에 여러 사용자가 동시에 접속하여 사용을 할 수 있는 다중 사용자 시스템 입니다.

## 사용자의 종류
리눅스 시스템에서는 크게 3가지 유형의 사용자가 있습니다. 리눅스 시스템에서는 사용자의 종류에 따라 권한이 제한되거나, 특정 작업을 수행하기 위한 권한만 부여됩니다. 이를 통해 시스템 보안을 강화하고, 사용자의 역할에 맞게 권한을 관리할 수 있습니다.

### 일반 사용자
일반 사용자는 시스템의 리소스를 사용하는 일반적인 사용자를 말합니다. 이들은 파일을 생성하거나 수정할 수 있으며, 시스템 설정을 변경하는 권한은 가지지 않습니다.
> 운영체계를 사용하는 시용자 계정
  
### 슈퍼 사용자 (Superuser 또는 Root)
슈퍼 사용자는 시스템의 모든 리소스에 접근할 수 있는 최상위 권한을 가진 사용자입니다.  운영체계에서 슈퍼 사용자(Super user), 운용 관리자(Administrator) 또는 루트(Root)는 시스템 관리자가 시스템 제어를 위한 특별한 권한을 가지고 있는 시용자 계정을 말합니다.  

* 슈퍼 유저에게는 사용자 생성 권환을 포함해, 모든 작업을 실행할 수 있는 권한이 주어짐

이들은 시스템 관리자로서, 시스템의 설정을 변경하고, 시스템에 대한 모든 권한을 가지며, 일반 사용자의 파일을 읽거나 수정할 수 있습니다. 그러나, 이들은 실수로 시스템을 손상시킬 수 있는 위험이 있기 때문에, 이 권한을 사용할 때에는 꼭 필요한 경우에만 사용하는 것이 좋습니다.  

### 서비스 계정
서비스 계정은 서버에서 실행되는 특정 서비스에서만 사용되는 계정입니다. 이들은 시스템 설정을 변경할 수 없고, 특정 작업에 필요한 권한만 가지고 있습니다. 예를 들어, 웹 서버에서는 'www-data'라는 서비스 계정을 사용하여 웹 페이지 파일에 대한 읽기/쓰기 권한을 부여합니다.  

## 사용자 관리
---
리눅스는 사용자를 관리하기 위한 파일들과 명령어들을 가지고 있습니다.
* [사용자 목록](/start/user/list)

* [계정생성](/start/user/account)
* [비밀번호 관리](/start/user/password)


## root 사용자
리눅스에서 root 사용자는 최상위 관리자 계정으로, 시스템의 모든 권한을 가지고 있습니다.  

### root란
root 사용자는 시스템의 모든 파일과 디렉토리에 대한 읽기, 쓰기, 실행 권한을 가지고 있기 때문에, 시스템의 모든 설정을 변경할 수 있습니다.  

그러나, 이러한 권한은 동시에 큰 책임도 수반합니다. 실수로 인해 시스템 파일이 손상될 수도 있고, 보안상의 문제로 악성 코드나 해커에게 취약해질 수도 있습니다. 따라서 root 권한은 가능한 경우에는 최소한으로 사용하고, 권한이 필요한 작업에 대해서만 사용하는 것이 좋습니다.

또한, root 권한을 가진 사용자는 일반적인 사용자들보다 우선순위가 높아서, 다른 사용자들이 생성한 파일을 읽거나 수정할 수도 있습니다. 따라서, root 권한을 가진 사용자는 다른 사용자들의 파일을 보호하기 위해 신중하게 작업을 수행해야 합니다.

### 권환 얻기
명령어 앞에 `sudo`명령을 같이 입력하면, root의 권환을 빌려와서 명령을 실행합니다. 이때 루트의 비밀번호를 입력하게 됩니다.

### root 비밀번호 재설정







