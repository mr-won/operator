# operator
실무용 연산자 정리 (filtering)

(s_ip  AND d_ip ) AND NOT (s_port AND d_port) ~

프로퍼티 별로 묶어서 쿼리 작성

쿼리 작성 시 숫자는 따옴표x 문자는 따옴표 포함, 대소문자 구별, NOT뒤에 띄어쓰기 X


이렇게 하면 쿼리 로직을 추가하기도 쉽고 튜닝하기 쉬워짐
## 연산자 교환 법칙 적용 됩니다.
(A AND B) AND C-> (A AND B OR C) 결합 법칙

## 포함, 제외 동일 조건

## 논리 연산자(검색용)
AND 
NOT
OR

like 
in 
## 와일드 카드(검색용)
%    
*      
