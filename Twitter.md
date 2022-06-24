In the generated page 'public/index.html'

Replace:
```
<meta property="og:image" content="/featured-background.jpg"/>
```
```
<meta name="twitter:card" content="summary_large_image"/>
```
```
<meta name="twitter:image" content="/featured-background.jpg"/>
```

With:
```
<meta property="og:image" content="https://www.federizer.org/featured-background.jpg"/>
```
```
<meta name="twitter:card" content="summary"/>
```
```
<meta name="twitter:image" content="https://www.federizer.org/featured-background.jpg"/>
```

Test on:
```
https://cards-dev.twitter.com/validator
```
