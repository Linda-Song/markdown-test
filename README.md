# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
###### 제목 6


# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈 (Line Break)

동해물과 백두산이 마르고 닳도록  (띄어쓰기 2번)  
하느님이 보우하사 우리나라 만세 <br/>
띄어쓰기 2번 또는 브레이크 태그 넣기

# 강조 (Emphasis)

_이탤릭_  
**두껍게**  
**_이탤릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>  


# 목록 (list)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 들여쓰기 2번 하면 소목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

-  순서가 필요하지 않은 목록
-  순서가 필요하지 않은 목록
-  순서가 필요하지 않은 목록
    -  순서가 필요하지 않은 목록
    -  순서가 필요하지 않은 목록
-  순서가 필요하지 않은 목록

# 링크(Links)
<a href="http://google.com">GOOGLE</a>

[GOOGLE](http://google.com)

<a href="http://naver.com" title="Naver로 이동!">NAVER</a>

[NAVER](http://naver.com "Naver로 이동!")

<a href="http://naver.com" 
title="Naver로 이동!"
target="_blank">NAVER</a> 

# 이미지 Image

![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](http://heropy.blog/)  클릭시 링크로 넘어감

# 인용문 (BlockQuote)

> 남의 말이나 글에서 직접 또는 
간접으로 따온 문장.  
> (네이버 국어사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문1~3

# 인라인(inline) 코드 강조

css에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="http://naver.com" target="_blank">NAVER</a> 
```
```css
.list > li {
  position: absolute;
  top: 40px;
}
```

``` javascript
function func() {
  var a = 'AAA'
  return a;
}
```
``` bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록 
```

# 표(Table)

position 속성

값 | 의미 | 기본값
-- |:--: |--: 
static | 기준 없음  | o
relative  | 요소 자신 | x
absolute | 위치 상 부모 요소 | x

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록</br>
하느님이 <u>보우하사</u> 우리나라 만세  
마크다운은 간단한 것만 되는 것이기에 원시 html을 사용해   
그 기능을 확장시키자

# 수평선 (Horizontal Rule)
---

***

___