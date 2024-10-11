---
category: 문법
Date: 
인물_저자: 
출처: https://gist.github.com/ihoneymon/652be052a0727ad59601
tags:
  - 마크다운
  - 문법
aliases:
  - 마크다운 문법
---
# 1. 마크다운

## 1.1. 마크다운이란?

마크다운(Markdown)은 2004년 존 그루버(John Gruber)와 애런 스워츠(Aaron Swartz)에 의해 개발된 경량 마크업 언어입니다. 주로 웹에서 텍스트를 서식화하는 데 사용되며, HTML 같은 복잡한 태그를 사용하지 않고도 간단한 문법으로 텍스트를 꾸밀 수 있다는 점에서 매우 인기가 있습니다.

# 2. Markdown 사용법(문법)

## 2.1. Header

```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is A H5
###### This is  H6

## 2.2. BlockQuote
이메일에서 사용하는 `>` 블럭 인용 문자를 이용한다.
```
> This is a first blockquote.
> 	>This is a first blockquote.
> 	>	>This is a first blockquote.
```
> This is a first blockquote.
> 	>This is a first blockquote.
> 	>	>This is a first blockquote.

이 안에서는 다른 마크다운 요소를 포함할 수 있다.

## 2.3. 목록
### 2.3.1. 순서 있는 목록(번호)
1. 첫 번째
2. 두 번째
3. 세 번째
### 2.3.2. 순서 없는 목록
```
- 빨강
	- 빨강
		- 빨강
		+ 빨강
```
- 빨강
	- 빨강
		- 빨강
		+ 빨강
## 2.4. 코드
4개의 공백 또는 하나의 탭으로 들여쓰기를 만나면 변환되기 시작하여 들여쓰지 않은 행을 만날때까지 변환이 계속된다.
```
This is a normal paragraph:

	This is a code block.

end code block.
```
This is a normal paragraph:

	This is a code block.

end code block.

	안녕하세요. 이 위치는 코드 블럭입니다.

