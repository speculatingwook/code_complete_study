
# 코드 컴플리트 정리

<img width="202" alt="image" src="https://user-images.githubusercontent.com/105579811/230703295-6d155306-3d55-48b1-9592-f40b401defd4.png">

## 1부: 기초확립
### [소프트웨어 구현으로의 초대](./1부:기초_확립/1장:소프트웨어_구현으로의_초대)

- [소프트웨어 구현이란 무엇인가?](./1부:기초_확립/1장:소프트웨어_구현으로의_초대/소프트웨어_구현이란_무엇인가.md)
- [소프트웨어 구현이 중요한 이유는 무엇인가?](./1부:기초_확립/1장:소프트웨어_구현으로의_초대/소프트웨어_구현이_중요한_이유.md)

### [소프트웨어 개발의 이해를 돕기 위한 비유](./1부:기초_확립/2장:소프트웨어_개발의_이해를_돕기_위한_비유)

- [비유의 중요성](./1부:기초_확립/2장:소프트웨어_개발의_이해를_돕기_위한_비유/비유의_중요성.md)
- [소프트웨어 비유 사용법](./1부:기초_확립/2장:소프트웨어_개발의_이해를_돕기_위한_비유/소프트웨어_비유_사용법.md)
- [일반적인 소프트웨어 비유](./1부:기초_확립/2장:소프트웨어_개발의_이해를_돕기_위한_비유/일반적인_소프트웨어_비유.md)

### 준비는 철저하게: 선행조건

- 선행 조건의 중요성
- 작업 중인 소프트웨어의 종류 결정
- 문제 - 정의 선행 조건
- 요구사항 선행 조건
- 아키텍처 선행 조건
- 선행 조건에 소요되는 시간

### 구현시 결정해야 할 핵심 사항

- 프로그래밍 언어 선택
- 프로그래밍 규약
- 기술 흐름 파악
- 구현 실천법 선택

## 2부: 고품질 코드 작성

### 구현 설계

- 설계의 어려움
- 핵심 설계 개념
- 설계 빌딩 블록: 발견적 학습
- 설계 실천법
- 잘 알려진 방법론에 대한 의견

### 클래스 다루기

- 클래스의 토대: 추상 데이터형(ADT)
- 좋은 클래스 인터페이스
- 설계와 구현 문제
- 클래스를 작성하는 이유
- 프로그래밍 언어와 관련된 이슈
- 클래스를 넘어서: 패키지

### 고급 루틴

- 루틴을 작성하는 이유
- 루틴 수준의 설계
- 좋은 루틴 이름
- 루틴의 길이에 대한 문제
- 루틴 매개변수 처리
- 함수를 사용할 때 특별히 고려해야 할 사항
- 매크로 루틴과 인라인 루틴

### 방어적 프로그래밍

- 잘못된 입력으로부터 프로그램 보호
- 어셜션
- 오류 처리 기법
- 예외
- 오류로 인한 손상을 막기 위한 방책
- 디버깅 보조 도구
- 제품 코드를 얼마나 방어적으로 프로그래밍할 것인지 정하기
- 방어적 프로그래밍에 대해서 한 번 더 고민하기

### 의사코드 및 프로그래밍 프로세스

- 클래스 및 루틴 개발 단계 요약
- 전문가를 위한 의사코드
- PPP를 이용한 루틴 구현
- PPP 대안

## 3부: 변수
### 변수 사용 시 고려할 사항

- 데이터 사용 능력
- 변수 선언을 쉽게 만드는 방법
- 변수 초기화 가이드라인
- 범위
- 지속성
- 결합 시점
- 데이터형과 제어 구조 사이의 관계
- 변수를 한 목적으로만 사용하기

### 변수 이름의 기능

- 좋은 이름을 위한 고려 사항
- 특정 타입의 데이터 이름 짓기
- 이름 규약의 효과
- 비형식적인 이름 규약
- 표준 접두사
- 피해야 할 변수 이름

### 기본 데이터형
- 숫자 일반
- 정수
- 부동 소수점 수
- 문자와 문자열
- 불린 변수
- 열거형
- 이름 상수
- 배열
- 새로운 형 만들기(형 별명)

### 특이한 데이터형

- 구조체
- 포인터
- 전역 데이터

## 4부: 명령문

### 순차적 코드 구성하기

- 순서가 중요한 명령문
- 순서가 중요하지 않은 명령문

### 조건문 사용

- if 문
- case 문

### 반복문 제어

- 반복문 종류 선택
- 반복문 제어
- 반복문을 쉽게 작성하는 법 - 안에서부터 밖으로
- 반복문과 배열의 연관성

### 특이한 제어 구조

- 여러 곳에서 반환하는 루틴
- 재귀문
- goto 문
- 특이한 제어 구조에 대한 관점

### 테이블 활용 기법

- 테이블 활용 기법에서 일반적으로 고려해야 할 사항
- 직접 접근 방식
- 인덱스 접근 방식
- 단계적 접근 방식
- 그 밖의 테이블 참조 방법

### 제어와 관련된 일반적인 이슈

- 불린 표현식
- 복합문(블록)
- 널 명령문
- 지나치게 깊은 중첩 구조 처리
- 프로그래밍의 기초: 구조적 프로그래밍
- 제어 구조와 복잡성

## 5부: 코드 향상
### 소프트웨어 품질

- 소프트웨어 품질의 특성
- 소프트웨어 품질을 향상시키기 위한 기법들
- 품질 향상 기법의 상대적 효과성
- 품질 보증 활동 시기
- 소프트웨어 품질의 일반적인 원칙

### 협력 구현
- 협력 개발 방법 개요
- 짝 프로그래밍
- 형식적인 정밀 검토
- 여러가지 협력 개발 방법

### 개발자 테스트
- 소프트웨어 품질에서 개발자 테스트의 역할
- 개발자 테스트에 대한 바람직한 접근 방법
- 여러가지 교묘한 테스트 방법
- 전형적인 오류
- 테스트 지원 도구
- 테스트를 향상시키는 방법
- 테스트 기록을 보존하는 방법

### 디버깅
- 디버깅 이슈 소개
- 결함 발견
- 결함 수정
- 디버깅에서 심리학적으로 고려해야 할 사항
- 디버깅 도구 - 분명한 도구와 그렇지 않은 도구

### 리팩토링

- 소프트웨어 진화의 종류
- 리팩토링 소개
- 구체적인 리팩토링
- 안전한 리팩토링 방법
- 리팩토링 전략

### 코드 튜닝 전략
- 성능이란?
- 코드 튜닝 소개
- 느리고 비대한 부분
- 측정
- 반복
- 코드 튜닝 단계 요약

### 코드 튜닝 기법
- 논리 구조
- 반복문
- 데이터 변환
- 표현식
- 루틴
- 저급 언어를 이용한 재구성
- 변경이 많을수록 상태는 그대로

## 6부: 시스템 고려사항

### 프로그램의 크기가 구현에 미치는 영향
- 의사소통과 크기
- 프로젝트 크기의 범위
- 프로젝트 크기가 오류에 미치는 영향
- 프로젝트의 크기가 생산성에 미치는 영향
- 프로젝트의 크기가 개발 활동에 미치는 영향

### 구현 관리
- 훌륭한 코딩 장려
- 형상 관리
- 구현 일정 예측
- 측정
- 개발자를 사람으로 대우하기
- 관리자 관리

### 통합
- 통합 접근 방법의 중요성
- 통합 빈도 - 단계별 또는 점층적 접근 방법
- 점증적 통합 전략
- 일일 빌드와 스모크 테스트

### 프로그래밍 도구
- 설계 도구
- 소스코드 도구
- 실행코드 도구
- 도구 지향적인 환경
- 자신만의 프로그래밍 도구 개발
- 프로그래밍 도구에 대한 환상

## 7부: 소프트웨어 장인 정신

### 레이아웃과 스타일
- 레이아웃 기초 지식
- 레이아웃 기법
- 레이아웃 스타일
- 제어 구조의 레이아웃
- 개별 명령문 레이아웃
- 주석 레이아웃
- 루틴 레이아웃
- 클래스 레이아웃

### 스스로를 설명하는 코드

- 외부 문서
- 문서화를 위한 프로그래밍 스타일
- 주석을 작성할 것인가? 작성하지 않을 것인가?
- 효과적인 주석을 위한 핵심사항
- 주석 스타일
- IEEE 표준

### 개발자의 성격
- 성격은 주제를 벗어난 것 아닌가?
- 지성과 겸손
- 호기심
- 지적인 정직함
- 의사소통과 협동
- 창의성과 훈련
- 게으름
- 덜 중요한 특성
- 습관

### 소프트웨어 장인 정신에 대한 주제
- 복잡성 정복
- 자신에게 맞는 프로세스 선택
- 컴퓨터보다 사람을 위한 프로그램을 작성하라
- 언어에 제약을 받지 않고 언어를 활용한 프로그래밍
- 규약을 활용하여 핵심에 집중
- 문제 중심의 프로그래밍
- 낙석을 주의하라
- 반복, 반복, 또 반복
- 소프트웨어와 신조를 뗴어놓아라

### 더 많은 정보를 얻으려면
- 소프트웨어 구현에 관한 정보
- 구현 외의 주제
- 정기 간행물
- 소프트웨어 개발자의 독서 계획
- 전문가 협회에 가입