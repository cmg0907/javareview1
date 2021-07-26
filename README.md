# javareview1


### IF 문 

## 기본예시

```
if (조건문) {
    <수행할 문장1>
    <수행할 문장>
    ...
}else {
    <수행할 문장A>
    <수행할 문장B>
    ...
}
```


## 조건문?
> 참과 거짓을 판단하는 문장을 말한다.

```
boolean money = true;
if (money) {
...
```


## 비교연산자

```
비교연산자	  설명
x < y 	   x가 y보다 작다
x > y 	   x가 y보다 크다
x == y 	   x와 y가 같다
x != y	   x와 y가 같지 않다
x >= y	   x가 y보다 크거나 같다
x <= y	   x가 y보다 작거나 같다
```

> - Ex) 만약 3000원 이상의 돈을 가지고있으면 택시를타고 아니면 걸어가라
```
int money = 2000;
if (money >= 3000) {
    System.out.println("택시를 타고 가라");
}else {
    System.out.println("걸어가라");
}
```
> - money >=3000이라는 조건문이 거짓이되기에 else를 다음문장에서 수행하게함































### Switch/case 문

> switch/case문은 if문과 비슷하지만 더정형화됨 파이썬에는 없음


- switch/case문의 구조
```
switch(입력변수) {
    case 입력값1: ...
         break;
    case 입력값2: ...
         break;
    ...
    default: ...
         break;
}
```









