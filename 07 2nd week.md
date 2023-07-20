# 2023 07 13

><목차>

1. [유니티: 텍스트 선명도](#유니티-텍스트-선명도)
2. [유니티: 그림 선명도](#유니티-그림-선명도)
3. [유니티: 리스트 C#](#유니티-리스트)
4. [유니티: 형변환 C#](#유니티-형변환)
1. [깃허브: 마크다운 사용법](#깃허브-마크다운-사용법)
2. [깃허브: 줄바꿈](#깃허브-줄바꿈)

# 유니티: 텍스트 선명도

## Canvas -> Inspector-> Canvas Scaler -> Dynamic Pixels Per U
## 깨지면 높이기
<br><br>
# 유니티: 그림 선명도

## Canvas -> Inspector-> Canvas Scaler -> Refernce Pixels Per U
## 깨지면 낮추기
<br><br>
# 유니티: 리스트
# C#
## using System.Collections.Generic; //기본
## List<자료형> 리스트 이름 = new List<자료형>(); //선언
## 리스트이름.Add(변수); //리스트에 추가
## 리스트이름.Clear();  //리스트 초기화
## 리스트이름.Count  //리스트 길이
## 리스트이름.Insert(리스트에 넣을 위치. 변수); //리스트 도중 추가


## 리스트이름.GetRange(변수1,변수2) //변수1 부터 시작 변수2(횟수)까지 출력
### 예시: list.Add(1); list.Add(2); list.Add(3); List<int> list2 = list.GetRange(1,2);
### 결과: 23;

## 자료형.Join("사이에 넣을것", 리스트 이름.ToArray());
### 예시: list.Add(1); list.Add(2); list.Add(3); string line = string.Join(",", list.ToArray());
### 결과: 1,2,3
<br><br>

## 유니티 형변환
## C#
### int -> string : 변수이름.ToString();
### string -> int : intParse.(변수이름);

<br><br>
# 깃허브: 마크다운 사용법

## 확장자 md 붙일 것
<br><br>
# 깃허브: 줄바꿈

## <"br><br">   ""떼고 쓸것
