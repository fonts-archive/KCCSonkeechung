# KCC 손기정체

[배포처 바로가기](https://gongu.copyright.or.kr/gongu/wrt/wrt/view.do?wrtSn=13305046&menuNo=200023)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `KCC Sonkeechung`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/KCCSonkeechung/KCCSonkeechung.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/KCCSonkeechung/KCCSonkeechung.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'KCC Sonkeechung';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/KCCSonkeechung/KCCSonkeechung.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KCCSonkeechung/KCCSonkeechung.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KCCSonkeechung/KCCSonkeechung.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KCCSonkeechung/KCCSonkeechung.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/KCCSonkeechung/subsets/KCCSonkeechung-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/KCCSonkeechung/subsets/KCCSonkeechung-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "KCC Sonkeechung", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
CCL-저작자표시 
저작자의 이름, 저작물의 제목, 출처 등 저작자에 관한 표시를 해주어야 합니다. 
출처(저작자)만 밝히면 상업/비영리목적으로 이용할 수 있고 저작물의 변경이 가능합니다.
```
