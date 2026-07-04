## 프로세스 분석과 개선

프로세스 분석과 개선(Process Analysis & Improvement)은 기업의 업무 및 생산활동을 구성하는 프로세스를 체계적으로 분석하여 낭비를 제거하고 성과를 향상시키는 활동이다. 전통적인 작업개선이 개별 공정과 작업에 초점을 두었다면, 현대의 프로세스 개선은 가치흐름(Value Stream) 전체를 대상으로 품질(Q), 원가(C), 납기(D), 유연성(F), 서비스(S)를 동시에 향상시키는 것을 목표로 한다. 최근에는 Lean, Six Sigma, TOC, BPR뿐만 아니라 Process Mining, Digital Twin, AI 기반 최적화 기술과 결합하여 데이터 기반의 지속적 개선 체계로 발전하고 있다.

```text
현상 파악
    ↓
문제 정의
    ↓
원인 분석
    ↓
개선안 도출
    ↓
실행
    ↓
성과 측정
    ↓
표준화 및 지속 개선
```

## 프로세스의 이해

### 프로세스의 정의

프로세스(Process)란 투입(Input)을 고객이 요구하는 산출(Output)로 전환하는 일련의 활동(Activity)의 집합이다.

### 프로세스의 구성

```text
Supplier
   ↓
Input
   ↓
Process
   ↓
Output
   ↓
Customer
```

이는 SIPOC 모델의 기본 구조이며 모든 프로세스 분석의 출발점이 된다.

### 프로세스 분석의 목적

* 낭비 제거
* 생산성 향상
* 품질 향상
* 리드타임 단축
* 원가 절감
* 고객가치 증대
* 지속적 개선 기반 구축

### 프로세스 분석의 관점

| 관점     | 분석 내용        |
| ------ | ------------ |
| 품질(Q)  | 불량, 재작업, 변동  |
| 원가(C)  | 비효율, 재고, 낭비  |
| 납기(D)  | 대기, 병목, 리드타임 |
| 유연성(F) | 생산변동 대응력     |
| 서비스(S) | 고객만족, 대응속도   |

## 프로세스 분석 기법

### 공정분석(Process Chart)

공정의 흐름을 작업, 검사, 운반, 대기, 저장으로 구분하여 분석하는 가장 기본적인 기법이다.

#### 공정분석 기호

| 기호 | 의미             |
| -- | -------------- |
| ○  | 작업(Operation)  |
| □  | 검사(Inspection) |
| →  | 운반(Transport)  |
| D  | 대기(Delay)      |
| ▽  | 저장(Storage)    |

#### 공정분석의 목적

* 불필요한 작업 제거
* 운반거리 감소
* 대기시간 감소
* 표준공정 수립

### 흐름분석(Flow Analysis)

자재, 정보, 작업자 및 설비의 흐름을 분석하는 기법이다.

#### 주요 기법

* 흐름공정도(Flow Process Chart)
* 유통선도(Flow Diagram)
* From-To Chart
* 활동관계도(ARC)

### 가치흐름분석(VSM)

가치창출 활동과 비가치활동을 구분하여 분석하는 Lean의 대표적 도구이다.

#### 분석 절차

```text
현재상태 분석
      ↓
낭비 식별
      ↓
미래상태 설계
      ↓
개선 실행
```

#### 주요 분석 항목

* Lead Time
* Cycle Time
* 재고량
* 정보흐름
* 자재흐름

### 프로세스 맵(Process Map)

업무 흐름과 의사결정 구조를 시각적으로 표현하는 기법이다.

#### 주요 유형

* SIPOC
* Swim Lane Diagram
* BPMN
* Workflow Diagram

## 가치부가 분석(Value Analysis)

### 개요

프로세스의 각 활동을 고객가치 관점에서 분석하는 기법이다.

### 활동의 분류

| 구분                              | 의미                    |
| ------------------------------- | --------------------- |
| VA(Value Added)                 | 고객이 비용 지불 의사가 있는 활동   |
| NNVA(Necessary Non Value Added) | 현재는 필요하지만 가치창출은 없는 활동 |
| NVA(Non Value Added)            | 제거 대상 활동              |

### 대표 사례

| 활동   | 구분   |
| ---- | ---- |
| 가공   | VA   |
| 품질검사 | NNVA |
| 운반   | NVA  |
| 대기   | NVA  |
| 재고   | NVA  |

Lean 개선의 핵심은 NVA를 제거하고 NNVA를 최소화하는 것이다.

## 문제해결 및 원인분석

### 5Why 분석

"왜?"를 반복하여 문제의 근본원인을 찾는 기법이다.

### 특성요인도(Fishbone Diagram)

문제 원인을 체계적으로 분류하여 분석하는 기법이다.

#### 6M 관점

* Man
* Machine
* Material
* Method
* Measurement
* Mother Nature

### 파레토 분석

중요 소수(Vital Few)와 사소한 다수(Trivial Many)를 구분하여 개선 우선순위를 결정한다.

```text
20% 원인
      ↓
80% 문제 발생
```

### FMEA

잠재적 고장과 영향을 사전에 분석하는 예방 중심 기법이다.

#### 평가 요소

| 요소         | 의미  |
| ---------- | --- |
| Severity   | 심각도 |
| Occurrence | 발생도 |
| Detection  | 검출도 |

```text
RPN = S × O × D
```

### Fault Tree Analysis(FTA)

사고나 문제의 발생 원인을 논리적으로 추적하는 연역적 분석 기법이다.

## 프로세스 개선 방법론

### PDCA Cycle

지속적 개선의 기본 사이클이다.

```text
Plan
 ↓
Do
 ↓
Check
 ↓
Act
```

### Kaizen

현장 중심의 지속적이고 점진적인 개선 활동이다.

#### 특징

* 전원 참여
* 저비용 개선
* 지속적 개선
* 표준화 중시

### Lean 생산

고객가치 창출을 방해하는 낭비를 제거하는 개선 철학이다.

#### Lean 5원칙

* Value
* Value Stream
* Flow
* Pull
* Perfection

#### Lean의 8대 낭비

| 구분              | 내용     |
| --------------- | ------ |
| Overproduction  | 과잉생산   |
| Waiting         | 대기     |
| Transportation  | 운반     |
| Over Processing | 과잉가공   |
| Inventory       | 재고     |
| Motion          | 동작     |
| Defect          | 불량     |
| Talent          | 인재 미활용 |

### Six Sigma

변동을 감소시켜 품질을 향상시키는 통계적 개선 방법론이다.

#### DMAIC

```text
Define
 ↓
Measure
 ↓
Analyze
 ↓
Improve
 ↓
Control
```

### TOC(Theory of Constraints)

시스템의 제약조건을 중심으로 성과를 향상시키는 방법론이다.

#### TOC 5단계

```text
제약 발견
    ↓
제약 활용
    ↓
제약 종속
    ↓
제약 능력 향상
    ↓
반복
```

### BPR

프로세스를 근본적으로 재설계하여 혁신적 성과를 달성하는 방법론이다.

#### 특징

* 근본적 변화
* 프로세스 중심
* IT 활용
* 혁신 추구

### 개선 방법론 비교

| 구분   | Kaizen | Lean  | Six Sigma | TOC   | BPR |
| ---- | ------ | ----- | --------- | ----- | --- |
| 목표   | 지속개선   | 낭비제거  | 변동감소      | 병목개선  | 혁신  |
| 접근   | 현장 중심  | 흐름 중심 | 데이터 중심    | 제약 중심 | 재설계 |
| 개선수준 | 점진적    | 점진적   | 점진적       | 집중개선  | 혁신적 |

## 프로세스 개선의 핵심 기법

### ECRS

| 구분        | 내용  |
| --------- | --- |
| Eliminate | 제거  |
| Combine   | 결합  |
| Rearrange | 재배치 |
| Simplify  | 단순화 |

### Line Balancing

작업부하를 균등하게 배분하여 병목을 제거하는 기법이다.

### 병목관리

병목공정의 처리능력이 전체 시스템 성과를 결정한다.

### SMED

준비교체시간을 단축하여 생산 유연성을 향상시키는 기법이다.

### Poka-Yoke

작업자의 실수를 사전에 방지하는 오류방지 기법이다.

## 프로세스 성과관리

### KPI 체계

```text
전략 KPI
    ↓
프로세스 KPI
    ↓
공정 KPI
    ↓
작업 KPI
```

### 주요 성과지표

#### 품질

* 불량률
* FPY
* RTY
* Sigma Level

#### 납기

* Lead Time
* Cycle Time
* Takt Time
* On-Time Delivery

#### 원가

* 제조원가
* 물류비
* 재고비용

#### 생산성

* 노동생산성
* 설비생산성
* OEE

## 디지털 기반 프로세스 혁신

### BPM

프로세스의 설계, 실행, 모니터링, 개선을 통합 관리하는 체계이다.

### Process Mining

정보시스템 로그 데이터를 활용하여 실제 프로세스를 분석하는 기술이다.

#### 핵심 기능

| 기능          | 내용             |
| ----------- | -------------- |
| Discovery   | 실제 프로세스 도출     |
| Conformance | 표준 프로세스 적합성 검증 |
| Enhancement | 프로세스 개선        |

### Digital Twin

가상공간에 실제 프로세스를 구현하여 성능을 검증하는 기술이다.

### AI 기반 프로세스 최적화

* 이상 탐지
* 병목 예측
* 수요예측
* 생산계획 최적화
* 공정조건 최적화

## 프로세스 혁신의 발전 과정

```text
공정분석
    ↓
ECRS
    ↓
Kaizen
    ↓
Lean
    ↓
Six Sigma
    ↓
TOC
    ↓
BPR
    ↓
BPM
    ↓
Process Mining
    ↓
Digital Twin
```

프로세스 개선은 단순한 작업개선에서 데이터 기반의 자율 최적화 체계로 발전하고 있다.

## 최근 동향

### Lean Digital Transformation

Lean과 디지털 기술의 융합

### Hyper Automation

RPA, AI, Workflow를 활용한 업무 자동화

### Process Intelligence

실시간 프로세스 분석 및 의사결정 지원

### Autonomous Factory

자율 운영 생산시스템 구축

### ESG 기반 프로세스 혁신

* 탄소배출 최소화
* 에너지 효율 향상
* 자원순환 최적화

## 프로세스 분석과 개선의 종합

프로세스 분석과 개선은 기업의 모든 활동을 고객가치 관점에서 재해석하여 낭비를 제거하고 성과를 향상시키는 핵심 관리기법이다. 전통적인 공정분석과 ECRS를 기반으로 Lean, Six Sigma, TOC, BPR로 발전하였으며, 최근에는 Process Mining, Digital Twin, AI 기반 최적화 기술과 결합하여 데이터 중심의 지속적 개선 체계로 진화하고 있다. 궁극적으로는 QCDFS 경쟁우선순위를 달성하고 스마트 제조혁신의 기반을 제공한다.

### 범위 연계

| 연계 영역       | 주요 내용                        |
| ----------- | ---------------------------- |
| 작업방법 및 시간연구 | 공정분석, ECRS, 동작개선             |
| 표준작업관리      | 표준화, 작업표준서                   |
| 생산계획수립      | 병목관리, 리드타임                   |
| 품질관리        | Six Sigma, FMEA              |
| 공급망관리       | VSM, 리드타임                    |
| 생산혁신기술      | BPR, BPM                     |
| 스마트팩토리      | Process Mining, Digital Twin |
| 공장자동화기술     | 데이터 기반 공정최적화                 |

### 각주

[^1]: 프로세스 개선의 발전 흐름은 IE(Industrial Engineering) → TQM → Lean → Six Sigma → BPM → Digital Transformation으로 이어진다.

[^2]: Process Mining은 ERP, MES, SCM 등의 시스템 로그 데이터를 활용하여 실제 업무흐름을 분석하는 기술로 스마트팩토리의 핵심 분석도구로 평가된다.

[^3]: Gartner는 Hyper Automation과 Process Intelligence를 디지털 운영혁신의 핵심 기술로 제시하고 있으며, 제조업에서는 AI·RPA·Digital Twin과 결합한 자율 운영체계 구축이 확대되고 있다.

