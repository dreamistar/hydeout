---
layout: post
title: 하루패드를 공부해보자 _ 01
categories: Github초짜탈출기
use_math: true
---

## 0. 하루패드란? 

* 하루패드는 웹친화적인 문서를 작성하기 위한 마크다운 에디터! 

라고 하루패드 홈페이지에 설명되어 있다. 

Github 블로그를 운영하기 위해서는 컴퓨터에서 post를 작업하고 이를 다시 웹으로 전송해야 하는데, 이를 편하게 해주는 프로그램이다. 

(그냥 이렇게만 알고 있어도 당장 초짜가 쓰는데는 상관이 없지 않을까....)

http://pad.haroopress.com/user.html

위의 링크에서 자신의 운영체제를 골라 다운 받으면 편하게 쓸 수 있다. 
가장 중요한건,

#### 공짜다!


## 1. 목차넣기 
[TOC]
[] 안에 TOC를 입력하면 목차를 넣을 수가 있다. 
이때 TOC [TOC "float:left"]이면 왼쪽 정렬, [TOC "float:right"]이면 오른쪽 정렬이다. 

## 2. 큰 글씨를 쓰고 싶다면? 

큰 글씨를 쓰고 싶다면, 앞에 #을 붙여보자. 
# # 한 개
## # 두 개
### # 세 개
#### # 네 개
##### # 5...
###### # 6... 
####### # 7...부터는 없다. 


## 3. 코드를 넣어보자.
코드를 넣는 방법은 생각보다 매우 간단하다. 
~ 이 물결표시를 코드 앞 뒤로 넣어주면 된다. 
C언어의 {}를 담당한다고 보면 이해하기 쉽다. 


~~~python
print("저는 파이썬을 씁니다")
i = 2016
while i < "다른 언어를 하게 될까?" : 
  print("그건 모르겠다")
  print("그나저나 고양이는 완벽하다")
  i += 1
~~~


## 4. 수학표현식 
수학 표현식도 가능하다!
하지만, 이 기능은 하루패드 기본설정에는 꺼져있어서, 
**파일 - 환경설정 - 마크다운에 있는 수학표현식 사용을 체크**해야 활용이 가능하다. 
위의 코드 넣기와 동일하게$를 앞 뒤로 2개씩 넣어주었을 때 블록으로 수학 표현식을 쓸 수 있다. 
$$
3^x + \sqrt{3x+1} + (1+x)^x + x_1 + \sigma 
$$

이런식으로 표현이 가능하다. 

위의 식은 
3^x + \sqrt{3x+1} + (1+x)^x + x_1 + \sigma
라고 썼을 때의 결과물이다. 

