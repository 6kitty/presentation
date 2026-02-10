# Presentation

보안 및 블록체인 분야에서 공부하고 발표한 자료들을 모아둔 레포지터리입니다.
시스템 해킹(포너블), 리버스 엔지니어링, 블록체인 보안, 악성코드 분석 기법 등 다양한 주제를 다루고 있습니다.

---

## 블록체인 / 스마트 컨트랙트

### 비트코인 가명성과 프라이버시 코인
> `251030_스윙세미나_비트코인가명성과프라이버시코인_최종.pdf` (46p)

비트코인이 완전한 익명이 아닌 가명(pseudonymous) 시스템이라는 점에서 출발하여, 트랜잭션 추적 기법과 이를 우회하기 위한 프라이버시 코인(Monero, Zcash 등)의 동작 원리를 소개합니다. 스윙 세미나에서 발표한 자료입니다.

### 스마트 컨트랙트 Audit과 Slither 맛보기
> `kucis 세미나 스마트 컨트랙트 audit과 Slither 맛보기.pptx`

스마트 컨트랙트 보안 감사(audit)의 필요성과 과정을 설명하고, Trail of Bits에서 개발한 정적 분석 도구 Slither를 활용해 솔리디티 컨트랙트의 취약점을 탐지하는 방법을 실습 중심으로 다룹니다. KUCIS 세미나에서 발표한 자료입니다.

### 스마트 컨트랙트 비즈니스 로직 취약점 탐지를 위한 정적 분석 프레임워크
> `스마트 컨트랙트 비즈니스 로직 취약점 탐지를 위한 정적 분석 프레임워크.pdf` (12p)

Reentrancy, Integer Overflow 같은 일반적인 취약점을 넘어, 스마트 컨트랙트의 비즈니스 로직 자체에서 발생할 수 있는 취약점을 정적 분석으로 탐지하는 프레임워크를 제안합니다.

---

## 리버싱 (Reverse Engineering)

### 리버싱 5주차 - Windows Anti-Debugging
> `리버싱 5주차.pdf` (21p)

Windows 환경에서의 안티디버깅 기법을 다룹니다. `IsDebuggerPresent`, `NtQueryInformationProcess` 등 디버거 탐지 API와 이를 우회하는 방법을 학습합니다.

### 리버싱 6주차 - Linux Anti-Debugging & ptrace
> `리버싱 6주차.pdf` (21p)

Linux 환경에서의 안티디버깅 기법을 다룹니다. `ptrace` 시스템 콜을 활용한 디버거 탐지 원리와 우회 기법을 학습합니다.

---

## 포너블 (Pwnable)

### 포너블 4주차 - ROP (Return Oriented Programming)
> `포너블 4주차.pdf` (30p)

NX(DEP) 보호 기법이 적용된 환경에서 코드 실행을 달성하기 위한 ROP 기법을 다룹니다. 가젯 체이닝을 통해 기존 코드 조각들을 조합하여 임의 명령을 실행하는 방법을 학습합니다.

### 포너블 5주차 - ARM 32bit Exploitation
> `포너블 5주차.pdf` (22p)

ARM 32bit 아키텍처 환경에서의 시스템 해킹을 다룹니다. x86과 다른 ARM의 레지스터 구조, 호출 규약, 그리고 ARM 환경에 맞는 익스플로잇 기법을 학습합니다.

### 포너블 6주차 - ARM 64bit Exploitation
> `포너블 6주차.pdf` (12p)

ARM 64bit(AArch64) 아키텍처 환경에서의 시스템 해킹을 다룹니다. 32bit와의 차이점과 64bit 환경 특유의 익스플로잇 기법을 학습합니다.

---

## 악성코드 분석 기법

### Reflective DLL Injection
> `31기 육은서 - reflective dll injection.pdf` (17p)

Windows 환경에서 디스크에 DLL 파일을 남기지 않고 메모리 상에서 직접 DLL을 로드하는 Reflective DLL Injection 기법을 분석합니다. 일반적인 DLL Injection과의 차이점, 동작 원리, 그리고 탐지 방법까지 다룹니다.
