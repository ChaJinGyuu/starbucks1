## Favicon(파비콘, favorites icon)
웹페이지를 나타내는 아이콘, 웹페이지의 로고를 설정합니다.
대부분의 경우 루트 경로에 'favicon.ico' 파일을 위치하면 자동으로
로딩하기 때문에 '<link />' 를 작정할 필요가 없습니다.
'favicon.png' 파일을 사용하려면 다음과 같이 '<link />'를 작성하세요.
```html
<link rel="shorcut icon" href="favicon.ico" />
<link rel="icon" href="./favicon.png" />
```
favicon.ico 64 x 64 (px) 또는 32 x 32 또는 16 x 16
favicon.png 500 x 500 (px)

## Reset.css
> 각 브라우저의 기본 스타일을 초기화합니다.
[jsdelivr이동](https://www.jsdelivr.com/package/npm/the-new-css-reset)
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.1/reset.min.css" />
```
## 오픈 그래프(The Open Graph protocol)
웹페이지가 소셜 미디어(페이스북 등)로 공유될 때 우선적으로 활용되는 정보를 지정합니다.
[더 많은 오픈그래프 속성보기](https://ogp.me/)
```
og:type: 페이지의 유형(E.g, website, video.movie)
og:site_name: 속한 사이트의 이름
og:title: 페이지의 이름(제목)
og:description: 페이지의 간단한 설명
og:image: 페이지의 대표 이미지 주소(URL)
og:rel: 페이지 주소(URL)
```

## Youtube ARI
IFrame Player API를 통해 YouTube 동영상을 제어할 수 있습니다.
