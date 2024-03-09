# typeface-arita

## 아리따 글꼴 웹폰트

> 아모레퍼시픽의 기업 아이덴티티를 담은 글꼴로 ‘나눔의 가치’를 실현하고자 합니다.\
> 사회와 함께 아름다움을 향유하는 문화를 통해 나눔의 가치를 실현하고자 하는 아모레퍼시픽의 기업 글꼴이자 누구나 무료로 사용할 수 있도록 배포하는 나눔 글꼴입니다. 아리따 서체는 2016년 1월 세계 3대 디자인 공모전인 독일의 ‘iF 디자인 어워드(International Forum Design Awards) 2016’ 에서 커뮤니케이션 부문 본상을 수상하였으며, 2015년 7월 레드닷 디자인 어워드에서도 수상한 바 있습니다.

https://www.apgroup.com/int/ko/about-us/visual-identity/arita-typeface/arita-typeface.html

아리따 글꼴 웹폰트입니다. [Demo](https://htmlpreview.github.io/?https://github.com/taevel02/typeface-arita/blob/main/index.html)

### 지원 폰트 및 굵기

아리따 돋움, 아리따 부리, 아리따 산스(로마자), 아리따 흑체(중국어)를 모두 지원합니다.

아라따 글로벌을 적용하는 경우, 한글, 영문, 한자를 지원하는 통합 글꼴을 사용할 수 있습니다.

#### 아리따 돋움(한글)

> 품격 있는 말씨를 사회와 나누기 위해 2005년 처음으로 시도한 본문용 글꼴입니다. 기존의 직선적이고 딱딱한 느낌의 돋움체에서 부드러운 곡선이 돋보이는 새로운 표정의 글꼴을 제시했습니다.

font-weight Thin(100), Light(300), Medium(500), Semi Bold(600), Bold(700)을 지원하며, 기본값은 Meidum입니다.

#### 아리따 부리(한글)

> 긴 문장에 적합한 본문용 글꼴로 2014년 완성된 아리따 부리는 현대적인 여성의 단아하고 지적인 멋스러움을 담고 있습니다. 국내 최초로 머리카락같이 가는 헤어라인 서체를 개발해 기업 글꼴의 새로운 흐름을 제시한 점을 높게 평가 받고 있습니다.

font-weight Hairline(100), Light(300), Medium(500), Semi Bold(600), Bold(700)을 지원하며, 기본값은 Meidum입니다.

#### 아리따 산스(로마자)

> 2012년 선보인 아리따 글꼴의 첫 로마자 서체입니다. 아리따 산스는 휴머니스트 산 세리프 계열로 부드럽고 우아한 표정을 지니고 있습니다.

font-weight Thin(100), Light(300), Medium(500), Semi Bold(600), Bold(700)을 지원하며, 기본값은 Meidum입니다.

#### 아리따 흑체(중국어)

> 국내 첫 중문 기업 서체인 아리따 흑체는 아모레퍼시픽이 추구하는 현대적인 여성의 아름다움을 담아냈습니다. 2016년 6월 본문용 굵기의 아리따 흑체를 시작으로, 두 가지 굵기를 추가하여 아리따 흑체 3종이 2017년 완성됐습니다.

font-weight Light(300), Medium(500), Bold(700)을 지원하며, 기본값은 Meidum입니다.

#### 아리따 글로벌

한글(숫자, 특수문자)에 아리따 돋움 혹은 부리를, 영문에 아리따 산스를, 중국어에 아리따 흑체를 적용한 글로벌 글꼴입니다.\
font-weight Light(300), Medium(500), Bold(700)을 지원하며, 기본값은 Meidum입니다.
한글, 영문에 한하여 font-weight Thin(100)을 지원합니다.

### 사용방법

npm

```bash
npm i install typeface-arita
```

```javascript
import "typeface-arita";
```

link 방식

```html
<link
  rel="stylesheet"
  type="text/css"
  href="https://cdn.jsdelivr.net/gh/taevel02/typeface-arita/arita.min.css"
/>
```

import 방식

```css
@import url("https://cdn.jsdelivr.net/gh/taevel02/typeface-arita/arita.min.css");
```

\# 일반

https://cdn.jsdelivr.net/gh/taevel02/typeface-arita/arita.css
https://cdn.jsdelivr.net/gh/taevel02/typeface-arita/arita-global-dotum.css
https://cdn.jsdelivr.net/gh/taevel02/typeface-arita/arita-global-buri.css

\# 최소버전

https://cdn.jsdelivr.net/gh/taevel02/typeface-arita/arita.min.css
https://cdn.jsdelivr.net/gh/taevel02/typeface-arita/arita-global-dotum.min.css
https://cdn.jsdelivr.net/gh/taevel02/typeface-arita/arita-global-buri.min.css

#### css 적용방법

```css
font-family: "Arita Dotum";
font-family: "Arita Buri";
font-family: "Arita Sans";
font-family: "Arita Heiti";

/* Global 1 or 2 */
font-family: "Arita";
```
