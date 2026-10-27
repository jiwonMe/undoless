# Undoless

Undoless Sans · Undoless Serif — 한글 11,172자를 지원하는 실험적 파생 글꼴입니다.
학교안심 바른돋움·바른바탕의 윤곽을 바탕으로 만들었습니다.

현재 배포: **패키지 0.1.9 / 폰트 0.109**.

| 글꼴 | CSS family | 굵기 |
| --- | --- | --- |
| Undoless Sans | `Undoless Sans` | Regular 400, Bold 700 |
| Undoless Serif | `Undoless Serif` | Regular 400, Bold 700 |

## 웹에서 사용하기

HTML의 `<head>`에 다음 CSS를 추가합니다. 버전이 고정된 주소입니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jiwonme/undoless@v0.1.9/undoless.css">
```

글꼴을 적용할 요소에 `font-family`를 지정합니다.

```css
body {
  font-family: "Undoless Sans", sans-serif;
  font-weight: 400;
}

.serif {
  font-family: "Undoless Serif", serif;
}

strong {
  font-weight: 700;
}
```

CSS에서 직접 불러올 수도 있습니다. `@import`는 다른 규칙보다 앞에 둡니다.

```css
@import url("https://cdn.jsdelivr.net/gh/jiwonme/undoless@v0.1.9/undoless.css");
```

네 가지 `@font-face`를 선언하며 `font-display: swap`을 사용합니다.
CSS만 연결하면 페이지의 기존 글꼴은 바뀌지 않으므로 `font-family`도 지정해야 합니다.
전체 문자 WOFF2이며, 가변 폰트·이탤릭·문자 범위별 분할은 제공하지 않습니다.

## 직접 호스팅하기

저장소의 `undoless.css`와 `fonts/experimental/` 폴더를 같은 상대 경로로 복사합니다.

```html
<link rel="stylesheet" href="./undoless.css">
```

폰트 폴더의 저작권·라이선스 파일도 함께 보관합니다.
기존의 `fonts/experimental/fonts.css`도 같은 폴더의 WOFF2를 불러오는 진입점으로 사용할 수 있습니다.

## 데스크톱에서 사용하기

[fonts/experimental](fonts/experimental)의 `.otf` 파일을 내려받아 운영체제에 설치합니다.
웹에서는 용량이 작은 `.woff2`를 사용합니다.
각 배포 파일의 SHA-256은 [SHA256SUMS](SHA256SUMS)에 있습니다.

## 배포본에 관하여

이 저장소에는 공개 배포용 폰트·CSS·고지만 포함합니다.
작업 중인 재설계본과 과거 실험 산출물은 포함하지 않습니다.

원본 한글 2,350자의 부품으로 비어 있던 8,822자를 조합했습니다.
가로 95% 기반에서 한글 윤곽과 진행폭을 97%로 조정한 0.109 배포본입니다.
추가 한글은 알고리즘으로 합성한 초안이므로 시각 검토가 필요하며, 아직 본문용 완성판이 아닙니다.
KERIS·윤디자인·Pretendard의 공식 확장판이나 공식 배포물이 아닙니다.

## 라이선스와 출처

폰트는 **SIL Open Font License 1.1**로 배포합니다.
재배포 시 저작권·라이선스 고지를 함께 유지합니다.

- 원저작권: Copyright © KERIS. All rights reserved. / 원본 디자인: YoonDesign Inc.
- 기호 대체·커닝 구성 요소: Pretendard 1.3.9, Kil Hyung-jin. Pretendard의 윤곽은 사용하지 않았습니다.
- [OFL 전문](OFL.txt)
- [출처 및 변경 고지](fonts/experimental/NOTICE.txt)
- [Pretendard 라이선스](fonts/experimental/Pretendard-LICENSE.txt)

공식 출처는 `NOTICE.txt`에 기록돼 있습니다.
