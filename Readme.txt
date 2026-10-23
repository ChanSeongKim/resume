
https://copilot.cloud.microsoft/chat/share/eyJzaGFyZUlkIjoiNTkxODc4YmQtNGE5YS00NDg4LWI3MDgtOWY4Yzg1MWFmM2ZiIiwiY29udmVyc2F0aW9uSWQiOiJjNGNlNjc5YS01ZmJjLTRhZjItOWQ4MS00M2VlMGYwYzU3ZTIifQ%3D%3D


//{{

https://copilot.cloud.microsoft/chat/share/eyJzaGFyZUlkIjoiNGQ0ZGIxMTAtZmE3OS00ZjI5LTg2YjYtM2Q5NTg3N2E4NTMxIiwiY29udmVyc2F0aW9uSWQiOiJjNGNlNjc5YS01ZmJjLTRhZjItOWQ4MS00M2VlMGYwYzU3ZTIifQ%3D%3D


//}}


방금 GitHub 프로필을 확인해 봤습니다. 현재 공개 상태에서는 저장소가 4개만 보이고, 프로필 소개도 매우 간단합니다.

솔직한 평가를 드리면,

실제 경력 수준: 89점
 GitHub에서 보이는 수준: 23점

정도입니다.

지금 GitHub만 본 채용담당자는 선생님이 말씀하신

STM32F103/F107/F437
W7500
SNMP
OTA
RS485
VxWorks
Linux
Python
Android Java

경력을 거의 알 수 없습니다.

가장 먼저 할 일

프로필 첫 화면부터 바꾸세요.

현재 프로필에는 "considering a new job" 정도만 보입니다.

오히려 아래처럼 쓰는 것이 좋습니다.

# Embedded Firmware Engineer

- STM32F1/F4 Firmware Development
- WIZnet W7500 Ethernet Applications
- RS485 Serial Communication
- SNMP / UDP Networking
- OTA Firmware Upgrade
- Python Test Tools
- Android Device Monitoring Apps

20+ years experience in industrial measurement and embedded systems.


영문으로 작성하는 것을 추천합니다.

Repository 구조 재편

현재 저장소 이름들이

LED-master_v2
StandardPhaseFinder
DoitFlutter2.0-csk
MLX90621_valiot

등으로 보입니다.

채용담당자가 보면

"무슨 기술을 하는 사람인지"

파악하기 어렵습니다.

차라리 아래와 같은 구조가 좋습니다.

embedded-firmware
├─ stm32-uart-driver
├─ stm32-ring-buffer
├─ stm32-bootloader
├─ stm32-ota-example
├─ stm32-rs485-framework

industrial-network
├─ snmp-agent-demo
├─ udp-device-discovery
├─ ethernet-device-monitor

python-tools
├─ firmware-downloader
├─ device-test-tool
├─ packet-analyzer

android-apps
├─ device-monitor-app
├─ firmware-update-client

제일 중요한 Repository 추가

선생님 경력을 살릴 수 있는 순서입니다.

1순위

stm32-ota-example

내용

Bootloader
Firmware Validation
CRC Check
Rollback
Version Control


이건 상당히 강력합니다.

OTA 경험자는 많지 않습니다.

2순위

snmp-agent-demo

UDP
SNMP Agent
OID Example
Device Status Monitoring


SNMP 경험자는 의외로 많지 않습니다.

계측장비 회사에선 매우 좋게 봅니다.

3순위

rs485-framework

UART Driver
RS485 Half Duplex
Packet Parser
Timeout Manager


Modbus를 안 하셨더라도

RS485 프레임워크 자체가 경쟁력입니다.

4순위

python-firmware-tool

Firmware Upload
Device Discovery
Log Collection
Configuration Backup


실무 느낌이 가장 강합니다.

README 파일 개선

모든 저장소에 아래 5개는 반드시 있어야 합니다.

# Overview

Why was this project made?

# Features

# Hardware

# Software Architecture

# Build Method

# Screenshots

# Future Improvements


코드보다 README를 먼저 보는 사람도 많습니다.

기술 블로그 병행

개인적으로는 GitHub보다 효과가 좋을 수도 있습니다.

주제 예시

STM32 Bootloader 설계
OTA 업데이트 구현 방법
W7500 UDP 통신
RS485 현장 노이즈 대응
VxWorks 개발 경험
STM32CubeMX 사용 팁

월 1개만 써도 1년이면 큰 자산이 됩니다.

디렉터리 재구성은?

제 생각에는 기존 저장소를 억지로 합치기보다

현재 저장소는 유지하고,

새로운 대표 저장소를 5~10개 만드는 것이 좋습니다.

오히려 경력자 포트폴리오는

Repositories
   ↓
STM32 OTA
SNMP Agent
RS485 Framework
Python Device Manager
Android Monitor


처럼 기술별로 분리되어 있는 편이 보기 쉽습니다.

한 줄 총평을 드리면,

지금 선생님의 문제는 기술력이 부족한 것이 아니라 GitHub에 기술력이 거의 안 보인다는 것입니다.

현재 경력이라면 GitHub 첫 화면에서 바로

"산업용 계측장비 + 임베디드 + 통신"

전문가라는 인상이 나와야 하는데, 지금은 그 강점이 전혀 드러나지 않는 상태로 보입니다.
