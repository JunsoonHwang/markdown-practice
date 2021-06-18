# 제목(header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
<!-- #의 개수로 중요도 지정 -->

# 문장(paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈

<!-- 띄어쓰고 싶은 부분 커서올리고 띄어쓰기 두번 or <br/>태그 사용 -->

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산
대한 사람 대한으로 길이 보전하세

# 강조

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록  
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    <!-- 들여쓰기 2번 -->

1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록

- 순서가 필요하지 않은 목록

# 링크
<!-- html 문법 -->
<a href="https://google.com">GOOGLE</a>

<!-- 마크다운 문법 -->
[GOOGLE](https://google.com)

<!-- html 문법 -->
<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

<!-- 마크다운 문법 -->
[NAVER](https://naver.com "NAVER로 이동!")

<!-- html 문법 -->
<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

# 이미지

<!-- ! 붙이면 이미지
     ! 안붙이면 링크 -->
![HEROPY](https://heropy.blog/css/images/logo.png)

<!-- 이미지를 누르면 링크로 이동 -->
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

# 인용문

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어사전)

> 인용문
>> 인용문2
>>> 인용문3

# 인라인 코드 강조

CSS에서 `background` 혹은
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.
<!-- 문장 드래그하고 `누르면 앞뒤 한방에 완성 -->

# 블록 코드 강조

```html
<a href="https://google.com" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA'
  return a;
}
```

``` bash
$ git commit -m 'Study Markdown'
# $ = 터미널에 입력하는 내용 의미
# 실제 입력시 무시하고 git부터 입력
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표

position 속성

값 | 의미 | 기본값
--|:--:|--:
<!-- 머리부분 몸통부분 -->
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML

동해물과 <span style="text-decoration: underline;">백두산이</span> 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

---

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY">

# 수평선

---

***

___