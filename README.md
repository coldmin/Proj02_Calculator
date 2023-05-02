# ▶ 계산기 [v.1.0.0] ◀

## -- Update 현황 --

## 1. 개발 배경 및 목적
개발한 내용을 콘솔창에서 텍스트로만 확인하는 것보다 그래픽 형태로 구현된 결과물을 보고 싶었다. 이에, 자바에서 GUI를 만들어주는 대표적인 툴인 Swing과 AWT를 사용해서 키오스크를 만들고자 했으나, 우선 Swing과 AWT 패키지에 대한 이해와 적응을 위해 계산기를 먼저 만들어 보기로 했다. 계산기의 수준은 간단한 사칙연산이 가능하도록 하며, 추후 업데이트를 통해 더 높은 수준의 계산 기능을 추가해 보고자 한다.

## 2. 명세
 - +, -, x, ÷ 사칙연산이 기능한 계산기 구현


## 3. 개발 기획


## 4. 실행 화면
![image](https://user-images.githubusercontent.com/130851245/235635236-1ecaf17b-df47-451d-83bb-acb50e1cc643.png)


## 5. 개선이 필요한 부분
 - 소수점 계산 및 결과 표시: 현재는 소수점 계산이 불가하다. 우선 btnDot의 ActionEvent를 어떻게 코딩해야할 지 고민이 필요하다.
 - 지우기 기능: 입력한 내용을 지우는 버튼을 추가해야 한다.
 - 초기화 기능: 입력한 내용 및 결과 값을 초기화시키는 버튼이 필요하다.
 - 현재는 첫 숫자를 입력하고 연산 기능을 누르면 다음 숫자를 누르기 전에 0으로 표기되어 진행상황을 알기 어렵다. 따라서, =를 누르기 전까지는 결과 레이블 상단에 입력한 내용들이 진행되는 상황을 조금 작게 표기되도록 하면 좋겠다.  
