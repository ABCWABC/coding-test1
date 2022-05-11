# coding-test1
신고 결과 받기
- 매개변수
 1. 이용자의 ID가 담긴 문자열 배열 id_list
 2. 각 이용자가 신고한 이용자의 ID 정보가 담긴 문자열 배열 report
 3. 정지 기준이 되는 신고 횟수 k

## 구현과정
  1. {신고당한자, 신고자} 로 1:1 구성 > Map
  2. 신고자는 중복가능 > List


## map 특징
1. 키와 값의 쌍으로 저장
2. 키는 중복저장 안됨

  #### 구현클래스
  1. HashMap
  2. Hashtable
  3. TreeMap
  4. Properties

## collection - list 특징
1. 순서를 유지하고 저장
2. 중복저장 가능

  #### 구현클래스
  1. ArrayList
  2. Vector
  3. LinkedList

## collection - set 특징
1. 순서를 유지하지 않고 저장
2. 중복저장 안됨

  #### 구현클래스
  1. HashSet
  2. TreeSet
