# 한밭대학교 유성 리빙랩 - 온결팀
> **종량제 봉투 지급 효율화 프로그램 (B팀)**
주기적으로 수행되는 **종량제 봉투 지급 대상자 명단 관리**를 자동화하여 **행정 효율성 향상 + 인력 부담 감소**를 목표로 함



## 팀 구성
|학번|이름|소속|
|---|---|---|
|20231418|이민지|컴퓨터공학과|
|20232034|이수현|컴퓨터공학과|
|20211929|정택준|컴퓨터공학과|
|20242049|강윤서|컴퓨터공학과|

<br>

## 목차
- [01. 프로젝트 개요](#teamateproject-background)
- [02. 시스템 설계](#system-design)
  - [1) 기술 스택](#tech-stack)
  - [2) 플로우 차트](#flow-chart)
  - [3) 실행 화면](#실행-화면)
- [03. 결론 및 기대효과](#conclusion)
- [04. 발표 자료](#presentation)

## TeamateProject Background

### 배경
  - 행정복지센터에서는 **분기별로 종량제 봉투를 일괄 지급** 업무를 수행해야 함
  - 대상자 정보(이름·주민등록번호·세대원 수)를 수작업으로 조회
  - 반복적인 행정 처리 업무로 인한 **업무 부담 증가**
### 문제점
  - 업무 효율성 저하
    - 단순 조회 업무를 수작업으로 하므로 업무 효율성이 저하됨
  - 자동화 시스템 부재
    - 행정망 특성상 개발자 모드를 통한 일반적인 매크로 시스템 도입이 어려움
    


## System Design
> 본 프로젝트는 **OpenCV**와 **PyautoGUI**를 기반으로 이미지 인식 기반 매크로를 구현한다.

### 1) Tech Stack

#### 1) 핵심 기술
<img
      src="https://go-skill-icons.vercel.app/api/icons?i=python,opencv,pandas"
    />

#### 2) 기술 소개
|**구분**|**목적**|
|:--:|:--:|
|GUI 자동화| PyAutoGUI |
|이미지 처리|OpenCV|
|데이터 처리|pandas|
|GUI|Tkinter|
|패키징|Pyinstaller|

#### 3) 사용 툴
<img
      src="https://go-skill-icons.vercel.app/api/icons?i=notion,figma,mermaid,huggingface,git,github"
    />

<br>

---


### Flow Chart
![flowchart](./004%20images/flowchart.png)

### 실행 화면
![window](./004%20images/active_window.png)

<br>

## Conclusion
> 본 프로그램은 **종량제 봉투 지급 대상자 명단 관리 자동화**를 통해 행정 담당자의 업무 부담을 줄이고, 지급 업무의 정확성과 효율성을 높이는 것을 목표로 한다.

### 기대효과
- 수작업 시간 절감
- 중복 및 누락 최소화
- 데이터 구조 표준화
- 행정 신뢰도 향상

## Presentation

### 2차 워크숍 발표자료
[발표자료 바로가기](./002%20Presentation/유성구청리빙랩_온결_2차%20워크숍%20발표자료.pdf)  
![cover](./004%20images/cover2.png)

---

### 중간 발표자료
[발표자료 바로가기](./002%20Presentation/유성구청리빙랩_온결_중간발표자료.pdf)  
![cover](./004%20images/cover1.png)

---

### 최종 발표자료
[발표자료 바로가기](./002%20Presentation/유성구청리빙랩_온결_최종발표자료.pdf)  
![cover](./004%20images/cover3.png)

