# header

## ๐ก nav

<img src="./img/header.png" width="50%">
<br>

```css
<nav>
  <ul>
    <li><a href="#">1</a></li>
     <li><a href="#">2</a></li>
  </ul>
</nav>
```

```
display: flex๋ก ์ ๋ ฌ
```

#### **_+ Trend_**

```
โ hero ํ์ด์ง์ call-to-action button
โ nav์ ๋ง์ง๋ง link

๊ฐ์ action์ ํ๋๋ก ํ๋ ๊ฒ์ด ํธ๋ ํธ
```

# section & div

<img src="./img/section.png" width="40%">
<img src="./img/div.png" width="40%">

<br>

```
โ section์ ํด๋น ํ์ด์ง์์ ๊ธด๋ฐํ๊ฒ ์ฐ๊ฒฐ๋์ด ์์ ๋ชฉ์ผ๋ก ๋๋  ์ ์๋ ๋ถ๋ถ
โ section์ ๋ค๋ฅธ section๊ณผ์ ๊ด๊ณ์ฑ layout
โ section > div๋ ํด๋น section์ content์ layout
```

---

main page

- hero section

  - div

    - hero-text-box
    - hero-img-box

    .
    <br>
    .
    <br>
    .
    <br>

- other section

---

## ๐ก section

```
โ background-color
โ padding-top/bottom
```

> ๋ค๋ฅธ section๊ณผ ๊ตฌ๋ถ ๋๋๋ก ํฐ layout ์ง์ 

<br>

## ๐ก div(container)

```css
.hero {
  max-width: 130rem;    (์ ๋์  ๋๋น)
  margin: 0 auto;       (์ปจํ์ธ  ๊ฐ์ด๋ฐ ์ ๋ ฌ)
  padding: 0 3.2rem;    (๋ทฐํฌํธ์ ์ปจํ์ธ  ๊ฐ๊ฒฉ)

์ปจํ์ธ  ๋ ์ด์์

  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  gap: 9.6rem;
}
```

> section์์ content ํฌ๊ธฐ์ ์ ๋ ฌ์ ๋ด๋น

<br>

# Reusable components

```
โ margin: 0 auto (๊ฐ์ด๋ฐ ์ ๋ ฌ)
โ display: grid
โ grid-template-columns
โ align-items: center

๊ณ์ ์ฌ์ฉํ๋ ์ค์ 
```

>

```html
<div class="container grid grid--2-cols grid--center-v"></div>
```

<img src="./img/reusable.png" width="50%">

```
reusable component๋ณ๋ก class๋ฅผ ๋ง๋ค์ด ์ฌ์ฉ,
CSS ํ์ผ์ ๋ฐ๋ก ๋ง๋ค์ด ์ ์ฅ
```

<br>

# border & box-shadow

```css
a:hover,
a:active {
  /* border: 3px solid #fff; */
  box-shadow: inset 0 0 0 3px #fff;
}
```

```
hover ํ์ ๋ border๊ฐ ์ถ๊ฐ๋ก ์๊ฒจ์ ํ๋ฉด์ด ์์ง์ด๋ ํ์ ํด๊ฒฐ
```
