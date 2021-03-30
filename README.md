# Markdown Syntax 정리

[Markdown Guide](https://www.markdownguide.org/ "마크다운 가이드")

[마크다운 위키백과 사이트](https://ko.wikipedia.org/wiki/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4 "마크다운 위키백과 사이트")

두 사이트를 참조하여 정리

---

<br/>



## 1. 제목(Headings)

* h1 부터 h6 까지 '#' 기호를 통해 헤더 층위 변경

```markdown
# h1

## h2

### h3

#### h4

##### h5

###### h6

```
==== **결과** ====

# h1

## h2

### h3

#### h4

##### h5

###### h6

============ <br/><br/>

---

## 2. Paragraphs(문단)

* 마크다운 문법은 한 줄 씩 띄어서 작성하는 것이 원칙이며 제목과 문단 조합을 사용하기 위해서는 다음과 같이 사용

```markdown

# 제목

<p>제목에 해당하는 문단입니다.</p>

```

==== **결과** ====

# 제목

<p>제목에 해당하는 문단입니다.</p>

============ <br/><br/>

* 제목을 # 외에 '=' 혹은 '-' 를 사용하여 나타낼 수도 있음

```markdown

h1
===============

h2
---------------

### h3
```

==== **결과** ====

h1
===============

h2
---------------

### h3

============ <br/><br/>

---

## 3. Line Breaks(개행)

* 문단 상에서 엔터를 여러 번 친다고 개행이 되지 않기 때문에 강제 개행을 위해서는 <br/>
<
br/> 태그를 사용

```markdown

## LILAC

오 라일락 꽃이 지는 날 goodbye<br/>
이런 결말이 어울려<br/>
안녕 꽃잎 같은 안녕<br/>

```

==== **결과** ====

## LILAC

오 라일락 꽃이 지는 날 goodbye<br/>
이런 결말이 어울려<br/>
안녕 꽃잎 같은 안녕<br/>

============ <br/><br/>

---

## 4. Emphasis(강조)

### - *이탤릭체*

```markdown

이탤릭체는 *Italic* 혹은 _Italic_ 처럼
하나의 '*' 혹은 '_'를 문자 양 옆에 사용

```

### - **볼드체**

```markdown

볼드체는 **Bold** 혹은 __Bold__ 처럼
두 개의 '**' 혹은 '__'를 문자 양 옆에 사용

```

### - __*이탤릭 & 볼드체 동시사용*__

```markdown

이탤릭과 볼드체를 동시에 사용하기 위해
__*Italic & Bold*__ 사용

```

### - <u>밑줄</u>

```markdown

밑줄은 <u>Highlight it!</u> 처럼
태그 <u>를 문자 양 옆에 사용

```

### - ~~취소선~~

```markdown

취소선은 ~~Cancel it!~~ 처럼
두 개의 물결 '~~'을 문자 양 옆에 사용

```

==== **결과** ====

-이텔릭체는 *Italic* 혹은 _Italic_

-볼드체는 **Bold** 혹은 __Bold__

-이탤릭과 볼드 __*Italic & Bold*__

-밑줄은 <u>Highlight it!</u>

-취소선은 ~~Cancel it!~~


============ <br/><br/>

---

<br/>

## Escaping Characters

### -' \* '와 ' \_ '를 문자로 사용하고 싶을 때

해당 문자를 이탤릭체가 아닌 텍스트 문자로 사용하고자 할 때는<br/>
이스케이프 문자 ' \ '를 이용

```
이스케이프 문자로 양 옆에 *과 _ 표시하기

\* Veritas Lux Mea \*
\__ Veritas Lux Mea \__
```

==== **결과** ====



\* Veritas Lux Mea \*

\__ Veritas Lux Mea \__

<br/>

---
<br/>

## 5. Blockquotes(인용구)
- 단일인용 : '>' 를 사용하여 표현
```
느낌이 오잖아 떨리고 있잖아 언제까지 눈치만 볼 거니 네 맘을 말해봐 딴청 피우지 말란 말이야 네 맘 가는 그대로 지금 내 손을 잡아
```
> 느낌이 오잖아 떨리고 있잖아
언제까지 눈치만 볼 거니
네 맘을 말해봐 딴청 피우지 말란 말이야
네 맘 가는 그대로 지금 내 손을 잡아

- 중첩인용 : '>' 를 중첩해서 사용
```
> 우연히 고개를 돌릴 때 마다 눈이 마주치는 건 몇일밤 내내 꿈속에 나타나 밤새 나를 괴롭히는 건
>> 그 많은 빈자리 중에서 하필 내 옆자릴 고르는 건 나도 모르게 어느새 실없는 웃음 흘리고 있다는 건
>>> 그럼 말 다했지 뭐 우리 얘기 좀 할까
>>>> 느낌이 오잖아 떨리고 있잖아 언제까지 눈치만 볼 거니 네 맘을 해봐 딴청 피우지 말란 말이야 네 맘 가는 그대로 지금 내 손을 잡아
```
> 우연히 고개를 돌릴 때 마다 눈이 마주치는 건 몇일밤 내내 꿈속에 나타나 밤새 나를 괴롭히는 건
>> 그 많은 빈자리 중에서 하필 내 옆자릴 고르는 건 나도 모르게 어느새 실없는 웃음 흘리고 있다는 건
>>> 그럼 말 다했지 뭐 우리 얘기 좀 할까
>>>> 느낌이 오잖아 떨리고 있잖아 언제까지 눈치만 볼 거니 네 맘을 해봐 딴청 피우지 말란 말이야 네 맘 가는 그대로 지금 내 손을 잡아


---

## 6. Lists(리스트)

### 순서가 있는 리스트(Ordered)
- 정렬된 숫자 뒤에 '.' 붙여 사용
( 0 이상의 정수여야 함 )

```
1. 순서 1
2. 순서 2
3. 순서 3
```
1. 순서 1
2. 순서 2
3. 순서 3
---

- 공백을 활용하여 중첩리스트 표현

```
1. 순서 1
2. 순서 2
3. 순서 3
    1. 순서 3-1
    2. 순서 3-2
4. 순서 4
```

1. 순서 1
2. 순서 2
3. 순서 3
    1. 순서 3-1
    2. 순서 3-2
4. 순서 4

<br/>

### 순서가 없는 리스트(Unordered)
* '*' 표현

```
* 리스트 1
* 리스트 2
```
* 리스트 1
* 리스트 2
---
+ '+' 표현

```
+ 리스트 1
+ 리스트 2
```
+ 리스트 1
+ 리스트 2
---
- '-' 표현

```
- 리스트 1
- 리스트 2
```
- 리스트 1
- 리스트 2

모두 동일하게 표현되기 때문에 어떤 것을 사용하여도 무방

 * 2n개의 공백(space)만을 삽입하여 중첩리스트 표현
```
- 리스트 1
(space)(space)- 리스트 2
(space)(space)(space)(space)- 리스트 3
```
- 리스트 1
  - 리스트 2
    - 리스트 3
<br/>

---

<br>

## 7. Code(코드 작성)

type `nano` 즉, ``` 기호를 쓰고자 하는 언어 앞에 붙이고 다음과 같이 작성

```
``` c
#include <stdio.h>

int main(){

    printf("Hello World-!!");

}
```
==== **결과** ====


``` c
#include <stdio.h>

int main(){

    printf("Hello World-!!");

}
```
---

<br>

## 8. Horizontal Rules(줄표 넣기)
* 줄표를 넣으려면 한 줄에 세 개 이상의 별표(***), 대시(---) 또는 밑줄(__) 사용


```
***
---
_________________
```

==== **결과** ====
***
---
_________________

============

<br><br>

---

## 9.  Links(링크 걸기)

* 링크 텍스트를 대괄호(예: [Twitch])로 묶은 다음 즉시 URL을 괄호 안에 삽입 <br>(예: (https://www.twitch.tv/)

```
[Twitch](https://www.twitch.tv/)
```
[Twitch](https://www.twitch.tv/)

---

<br>

* 위 방법이 귀찮거나 더 빠른 방법을 원한다면 URL 및 이메일 주소에 바로 꺾쇠 사용

```
<https://jieuninus.com/> <br>
<jeongmint@kakao.com>
```
<https://jieuninus.com/> <br/>
<jeongmint@kakao.com>

---
<br>

* 링크 뒤에 괄호() 나 큰따옴표""로 문자를 삽입하면 메모를 다는 것이 가능, 다음과 같이 모든 링크 형식을 정리할 수 있음

```
[1]: https://madeedam.com/
[1]: https://madeedam.com/ "New IU Fan Products"
[1]: https://madeedam.com/ 'New IU Fan Products'
[1]: https://madeedam.com/ (New IU Fan Products)
[1]: <https://madeedam.com/> "New IU Fan Products"
[1]: <https://madeedam.com/> 'New IU Fan Products'
[1]: <https://madeedam.com/> (New IU Fan Products)
(https://madeedam.com/)

```
[1]: https://madeedam.com/ 
[1]: https://madeedam.com/ "New IU Fan Products"
[1]: https://madeedam.com/ 'New IU Fan Products'
[1]: https://madeedam.com/ (New IU Fan Products)
[1]: <https://madeedam.com/> "New IU Fan Products"
[1]: <https://madeedam.com/> 'New IU Fan Products'
[1]: <https://madeedam.com/> (New IU Fan Products)
(https://madeedam.com/)

---
<br>

## 10. Images(이미지)

```
![GitHub Logo](images/logo.png)
Format: ![Alt Text](url)
```

![GitHub Logo](images/logo.png)
Format: ![Alt Text](url)

### Reference link 방식

```
![대체 텍스트][Img_id]

[Img_id]: 이미지 url "이미지 설명 정보"

```
![대체 텍스트][Img_id]

[Img_id]: https://images.velog.io/images/good159897/post/b889a389-5289-4d44-9d0f-1fbfcba53f97/markdown2.png "이미지 설명 정보"

- Reference로 사용할 경우 [이미지 id]와 ' : '를 아래와 같이 반드시 붙여서 작성해야 한다.
**[예시_id]: **

---

#### Markdown에서 이미지 크기를 조정하고 싶은 경우 `<img>` 태그를 사용하는 방법이 있다.

```
<img src="이미지 주소" width="100px" height="100px"> 이미지 설명</img>
```

<img src="https://images.velog.io/images/good159897/post/b889a389-5289-4d44-9d0f-1fbfcba53f97/markdown2.png" width="100px" height="100px" alt="Markdown Logo">
</img>

```
<img src="이미지 주소" width="200px" height="100px"> 이미지 설명</img>
```

<img src="https://images.velog.io/images/good159897/post/b889a389-5289-4d44-9d0f-1fbfcba53f97/markdown2.png" width="300px" height="100px" alt="Markdown Logo">
</img>

```
<img src="이미지 주소" width="50%" height="30%"> 이미지 설명</img>   
%로 크기 조정이 가능하다.
```

<img src="https://images.velog.io/images/good159897/post/b889a389-5289-4d44-9d0f-1fbfcba53f97/markdown2.png" width="50%" height="30%" alt="Markdown Logo">
</img>

<br>


11. HTML