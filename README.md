# 웹폰트
무료 폰트를 웹폰트로 사용하기

제 개인적인 사용이 목적.
나눔바른고딕, 나눔스퀘어(font-weight:700 & 400), 배달의민족(한나체, 주아체)

웹사이트 HTML문서의 ``<head>``안에 아래 코드를 삽입.
```
<link href="https://cdn.rawgit.com/singihae/Webfonts/master/style.css" rel="stylesheet" type="text/css" />
```

**@import**
CSS파일 및 ``<head>``안의 스타일 시트에 아래 코드를 삽입.
```
나눔바른고딕
@import url('https://cdn.rawgit.com/singihae/Webfonts/master/NanumBarun.css');

배달의민족
@import url('https://cdn.rawgit.com/singihae/Webfonts/master/DeliveryRace.css');

나눔스퀘어
@import url('https://cdn.rawgit.com/singihae/Webfonts/master/nanumsquare.css');
```

##적용하기
폰트를 적용 방법 - CSS에 다음과 같이 추가.
```
font-family: 'NanumBarunGothic', '나눔바른고딕', sans-serif;
font-family:'BM JUA','배달의민족 주아',sans-serif;
font-family:'BM HANNA','배달의민족 한나', sans-serif;
font-family: 'Nanum Square', sans-serif;

```

