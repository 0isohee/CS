# OS (운영체제)

### [01. OS]([github.com/0isohee/CS/OS/README.md?plain=1#L10](https://github.com/0isohee/CS/blob/main/OS/README.md?plain=1#L10))
### [02. 프로세스와 스레드](github.com/<organization>/<repository>/blob/<CS>/<OS>/README.md?plain=1#L5)
### [03. 스케줄링](github.com/<organization>/<repository>/blob/<CS>/<OS>/README.md?plain=1#L5)
### [04. 메모리](github.com/<organization>/<repository>/blob/<CS>/<OS>/README.md?plain=1#L5)
### [05. 가상 메모리](github.com/<organization>/<repository>/blob/<CS>/<OS>/README.md?plain=1#L5)
<br/>

### 01. OS 란?
운영체제 (OS, Operation System) 란, 하드웨어와 응용 소프트웨어 사이에 위치한 소프트웨어 계층이다. <br/>
컴퓨터 저장 장치에 설치되어, 컴퓨터가 부팅될 때 메모리에 로딩되어 사용된다.<br/>

### 01-1. 운영체제의 목적
1. 처리 능력 (throughput) 향상 - 일정 시간 내 시스템이 처리하는 일의 양을 향상시킴
2. 반환 시간 (turnaround time) 단축 - 사용자가 시스템에 요청한 작업 완료 시간 단축
3. 사용 가능도 (availabilty) 향상 - 시스템 자원을 빨리 제공할 수 있게 즉시 사용될 수 있게 함
4. 신뢰도 (reliability) 향상 - 시스템이 주어진 문제를 정확하게 해결해내는지, 정확한 값 줄 수 있도록 신뢰도 있어야함.

### 01-2. CPU & 메모리 구조
* CPU (중앙 처리 장치) 는 컴퓨터에서 연산을 처리하는 역할을 하며 다른 말로 프로세서라고도 함
* 메모리는 두 가지 종류가 있음
* 메모리 계층 구조 - (레지스터, 캐시 메모리는 CPU 내부에 위치!)
![image](https://github.com/user-attachments/assets/50141118-548a-4c6b-967f-ece381040171)

1) 주 기억장치
- 휘발성 메모리
- RAM
2) 보조 기억 장치
- 비 휘발성 메모리
- SSD, HardDisk

