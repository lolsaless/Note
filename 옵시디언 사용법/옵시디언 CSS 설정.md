# CSS 기본설정

## 행간, 문단 간격 조절

```
/* 기본 텍스트의 행간 조정 */
.cm-contentContainer {
  line-height: 1.6;
}

/* 문단 간격 조절*/
.markdown-source-view :is(.cm-line+.cm-line) {
  padding-top: 0.7em!important;
}
```

## 옵시디언 헤더, 색상 변경
https://wimmer.tistory.com/19