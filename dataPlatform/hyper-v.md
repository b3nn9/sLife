# 윈도우10에 Hyper-V 구성하기
- 파워쉘 실행 후, DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V 입력
- 참고: [Windows 10에 Hyper-V 설치](https://docs.microsoft.com/ko-kr/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v)  
~~~
Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

새로운 크로스 플랫폼 PowerShell 사용 https://aka.ms/pscore6

PS C:\Windows\system32> DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V

배포 이미지 서비스 및 관리 도구
버전: 10.0.19041.844

이미지 버전: 10.0.19042.1466

기능을 사용하도록 설정하는 중
[==========================100.0%==========================]
작업을 완료했습니다.
이 작업을 완료하려면 Windows를 다시 시작해야 합니다.
지금 컴퓨터를 다시 시작하시겠습니까? (Y/N) <- Y를 클릭하면, 재시작함^^
~~~
- 
