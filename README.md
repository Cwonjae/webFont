# 웹폰트
무료 폰트를 웹폰트로 사용하기

제 개인적인 사용이 목적.
나눔바른고딕, 나눔스퀘어(font-weight:700 & 400), 배달의민족(한나체, 주아체)

**<head></head>삽입방법**

웹사이트 HTML문서의 ``<head></head>``사이에 아래 코드를 삽입.
```
나눔바른고딕
<link href="https://cdn.rawgit.com/Cwonjae/webFont/a0ddaa75/NanumBarun.css" rel="stylesheet" type="text/css" />

배달의민족
<link href="https://cdn.rawgit.com/Cwonjae/webFont/a0ddaa75/DeliveryRace.css" rel="stylesheet" type="text/css" />

나눔스퀘어
<link href="https://cdn.rawgit.com/Cwonjae/webFont/a0ddaa75/nanumsquare.css" rel="stylesheet" type="text/css" />
```

**CSS @import 삽입방법**

CSS파일안의 스타일 시트 맨위 상단에 아래 코드를 삽입.
```
나눔바른고딕
@import url('https://cdn.rawgit.com/Cwonjae/webFont/a0ddaa75/NanumBarun.css');

배달의민족
@import url('https://cdn.rawgit.com/Cwonjae/webFont/a0ddaa75/DeliveryRace.css');

나눔스퀘어
@import url('https://cdn.rawgit.com/Cwonjae/webFont/a0ddaa75/nanumsquare.css');
```

##적용하기
폰트를 적용 방법 - CSS에 다음과 같이 추가.
```
font-family: 'NanumBarunGothic', '나눔바른고딕', sans-serif;
font-family:'BM JUA','배달의민족 주아',sans-serif;
font-family:'BM HANNA','배달의민족 한나', sans-serif;
font-family: 'Nanum Square', sans-serif;

```

