## 공장자동화 기술

**공장자동화(Factory Automation, FA)**는 생산설비, 제어시스템, 정보시스템을 통합하여 생산공정을 자동으로 운영하고 최적화하는 기술이다. 과거에는 PLC 기반의 설비 자동화가 중심이었다면, 현재는 IIoT, AI, Digital Twin, CPS, Edge Computing 등을 포함하는 스마트팩토리(Smart Factory) 개념으로 발전하고 있다.

```
공장자동화(Factory Automation)
│
├── 1. 자동화 개요
│      ├── Factory Automation(FA)
│      ├── Automation Pyramid
│      ├── CIM
│      ├── Smart Factory
│      ├── Industry 4.0
│      └── Digital Transformation(DX)
│
├── 2. 자동화 설비
│      ├── PLC
│      ├── PAC
│      ├── CNC
│      ├── Robot
│      ├── Cobot
│      ├── AGV
│      ├── AMR
│      ├── Conveyor
│      ├── AS/RS
│      └── Machine Vision
│
├── 3. 제어기술
│      ├── Sequence Control
│      ├── PID Control
│      ├── Motion Control
│      ├── Servo
│      ├── Inverter(VFD)
│      ├── Sensor
│      ├── Actuator
│      └── Safety PLC
│
├── 4. 산업통신
│      ├── Fieldbus
│      ├── Modbus
│      ├── PROFIBUS
│      ├── PROFINET
│      ├── EtherNet/IP
│      ├── EtherCAT
│      ├── OPC UA
│      └── MQTT
│
├── 5. 생산정보시스템
│      ├── MES
│      ├── ERP
│      ├── APS
│      ├── SCADA
│      ├── HMI
│      ├── Historian
│      ├── WMS
│      └── QMS
│
├── 6. 스마트팩토리 기술
│      ├── IIoT
│      ├── CPS
│      ├── Digital Twin
│      ├── Edge Computing
│      ├── Cloud
│      ├── AI
│      ├── Big Data
│      └── Predictive Maintenance
│
├── 7. 생산자동화 기법
│      ├── FMS
│      ├── FMC
│      ├── CIM
│      ├── CAD/CAM
│      ├── CAPP
│      ├── Lean Automation
│      ├── Jidoka
│      └── SMED
│
├── 8. 품질 자동화
│      ├── Vision Inspection
│      ├── SPC
│      ├── Traceability
│      ├── RFID
│      ├── Barcode
│      └── AI Inspection
│
└── 9. 성과지표(KPI)
       ├── OEE
       ├── Availability
       ├── Performance
       ├── Quality Rate
       ├── MTBF
       ├── MTTR
       ├── Automation Rate
       ├── Throughput
       ├── Cycle Time
       └── FPY
```

## 자동화 5대 원소

자동화 시스템은 센서, 프로세서, 액추에이터, 소프트웨어, 네트워크라는 5가지 핵심 요소가 유기적으로 결합하여 작동한다.

### 센서(Sensor)

외부 환경이나 작업 대상의 상태 변화를 감지하여 전기적 신호로 변환하는 입력 역할을 수행한다.

* **감지 및 측정**  
    온도, 압력, 위치, 변위, 빛 등 물리량을 측정하여 신호 전달
* **주요 구성 요소**  
    광센서, 근접센서, 압력센서, 비전 시스템

### 프로세서(Processor)

센서로부터 수집한 데이터를 분석하고 정해진 로직에 따라 판단하여 제어 명령을 하달한다.

* **제어 및 연산**  
    입력 데이터를 바탕으로 실시간 상태 판단 및 제어 신호 생성
* **주요 구성 요소**  
    PLC(Programmable Logic Controller), Industrial PC, MCU

### 액추에이터(Actuator)  

프로세서의 제어 신호를 받아 물리적인 운동이나 제어 동작을 직접 실행하는 출력 역할을 수행한다.

* **동작 구동**  
    전기적 신호를 기계적 운동 에너지로 변환하여 장치 작동
* **주요 구성 요소**  
    서보모터, 유압/공압 실린더, Solenoid Valve

### 소프트웨어(Software)

자동화 시스템 전체의 동작 알고리즘을 제어하고 데이터를 관리 및 모니터링한다.

* **알고리즘 및 관리**  
    제어 로직 구현, 사용자 인터페이스 제공, 데이터 시각화
* **주요 구성 요소**  
    SCADA, HMI, MES, 제어 프로그램

### 네트워크(Network)  

각 구성 요소 간의 데이터를 실시간으로 송수신하여 유기적으로 연결하는 통신 인프라를 제공한다.

* **통신 및 연결**  
    장치 간 정보 공유 및 상위 시스템과의 데이터 연동
* **주요 구성 요소**  
    Industrial Ethernet, Fieldbus, Modbus, OPC UA


자동화 5대 원소는 각각 고유한 기능을 담당하며 상호작용을 통해 시스템 전체를 구동한다. 각각을 요약 정리하면 다음과 같다.

![](https://yeonkyupark.github.io/pepc2e/images/automation_5_componets.png)

| 요소 | 주요 역할 | 대표 예시 |
| --- | --- | --- |
| **센서**(Sensor) | 감지 및 정보 입력 | 광센서, 비전 카메라 |
| **프로세서**(Processor) | 판단 및 제어 연산 | PLC, 산업용 PC |
| **액추에이터**(Actuator) | 물리적 구동 및 출력 | 모터, 유공압 실린더 |
| **소프트웨어**(Software) | 로직 작성 및 데이터 관리 | SCADA, HMI 프로그램 |
| **네트워크**(Network) | 장치 간 데이터 통신 | Ethernet/IP, Modbus |  

## 자동화 기술 변천 단계

자동화 기술은 순수 기계식 제어에서 출발하여 전기 시퀀스, 프로그래밍 제어, 자율 지능형 제어로 진화해 왔다.

### 기계식 자동화 단계

태엽, 캠, 기어 등 순수 기계 구조를 이용하여 정해진 동작을 반복 구동하는 단계이다.

* **핵심 제어 방식**  
    캠(Cam), 링크 메커니즘, 기어 조합
* **특징 및 한계**  
    유연성이 전혀 없어 동작 변경 시 기계 부품 전체를 교체해야 함

### 전기·유공압 시퀀스 제어 단계

릴레이와 유공압 스위치를 활용하여 전기 신호 순서에 따라 순차 제어를 구현하는 단계이다.

* **핵심 제어 방식**  
    릴레이(Relay) 회로, 하드와이어드(Hard-wired) 로직
* **특징 및 한계**  
    공정 변경 시 배선을 전면 재작업해야 하는 불편함 존재

### 프로그래밍 가능 자동화 단계

컴퓨터 기반의 제어장치가 등장하여 소프트웨어 수정만으로 공정을 변경하는 단계이다.

* **핵심 제어 방식**  
    PLC(Programmable Logic Controller), CNC(Computer Numerical Control)
* **특징 및 한계**  
    다품종 대량 생산이 가능해졌으나 개별 기기 간 데이터 연결성은 미흡함

### 유연 및 컴퓨터 통합 자동화 단계

컴퓨터 네트워크로 제조 설비를 통합하여 생산 체계 전체를 유연하게 제어하는 단계이다.

* **핵심 제어 방식**  
    FMS(Flexible Manufacturing System), CIM(Computer Integrated Manufacturing)
* **특징 및 한계**  
    공정 전환 속도가 빨라졌으나 실시간 대규모 데이터 분석에는 한계 존재

### 지능형 자율 자동화 단계

인공지능과 사물인터넷 기술이 융합하여 설비가 스스로 상태를 진단하고 최적 제어를 수행하는 단계이다.

* **핵심 제어 방식**  
    AI(Artificial Intelligence), IoT(Internet of Things), 디지털 트윈(Digital Twin)
* **특징 및 한계**  
    단순 자동화를 넘어 자율적 의사결정 및 자율 보전 가능

제어 주체와 기술 매체가 발전함에 따라 생산 체계의 유연성과 지능화 수준이 획기적으로 향상되었다. 각 단계별 내용을 정리하면 다음과 같다.

| 단계 | 제어 주체 | 주요 제어 매체 | 대표적 특징 |
| --- | --- | --- | --- |
| **기계식 자동화** | 기계 메커니즘 | 캠, 기어, 톱니바퀴 | 고정된 단일 동작 반복 |
| **시퀀스 제어** | 전기회로 | 릴레이, 스위치 | 배선 순서 기반의 제어 |
| **프로그래밍 자동화** | 마이크로프로세서 | PLC, CNC | 소프트웨어 프로그램 제어 |
| **유연 통합 자동화** | 산업용 네트워크 | FMS, CIM | 설비 간 연동 및 유연 생산 |
| **지능형 자율 자동화** | AI 및 클라우드 | CPS, 알고리즘 | 자율적 판단 및 최적화 |
