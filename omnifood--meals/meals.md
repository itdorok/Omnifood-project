# Featured-in section

<img src="featured-in.png">

```
display publication's logo
```

## ๐ก filter

```css
.feature {
  filter: brightness(0);
}
```

```
๋ก๊ณ ์ ๋ค์ํ ์์ "๊ท ์ผ"ํ๊ฒ ํ์์ผ๋ก ๋ฐ๊ฟ์ค๋ค

์ด์ธ์๋
โblur()
โhue-rotate() ๋ฑ์ด ์์
```

# How it works section

```
โ z pattern ์ด์ฉ
โ img, text ๋ฑ์ด ํฌํจ
โ product, sevice ์ ์์ธํ ์ ๋ณด ์ ๋ฌ
```

## ๐ก :: before / :: after

```
element๋ฅผ html์ ์ง์  ๋ง๋ค์ง ์๊ณ  pseudo class ๋ก ๋ง๋๋ ๋ฐฉ๋ฒ

์ฃผ๋ก position์ ํตํด ์์น ์กฐ์ 
```

```css
.step-img-box::before,
.step-img-box::after {
  display: block;
  content: "";
}
```

```
content๊ฐ ๋น์ด์๋ค๋ฉด padding, margin ์ ์ฉ์ ์ํด์ display: block ์ ์ธ ํ์
```

# Meals section

## **_translate_**

## **_transition_**

## **_box-shadow_**

```
โ float card when it's hovered
โ make effect natural using transition
โ add details using box-shadow
```

```css
.meal {
  box-shadow: 0 2.4rem 4.8rem rgba(0, 0, 0, 0.075);
  transition: all 0.4s;
}

.meal:hover {
  transform: translateY(-1.2rem);
  box-shadow: 0 3.2rem 6.4rem rgba(0, 0, 0, 0.06);
}
```

**_๐จ ์นด๋๊ฐ ์๋ก ์์ง์ด๋ฉด_**
<br>

- ๊ทธ๋ฆผ์๋ ์ฐํ๊ณ  ๋ ๋ฒ์ง๊ฒ
- translateY()๋ก Y์ถ๋ง ์์ง์ด๊ฒ
- transition์ผ๋ก ์์ฐ์ค๋ฝ๊ฒ

---

## ๐ก Underline vs Border-bottom

๊ธฐ๋ณธ text-decoration: underline์ text์ ๋ฐ์ค ๊ฐ๊ฒฉ์ ๋ฐ๊ฟ ์ ์์

```css
span {
  border-bottom: 1px solid #333;
  padding-bottom: 0.4rem;
}
```

#### + currentColor

```
ํ์คํธ ์์ ๋ฐ๊ฟ ๋๋ง๋ค border์ ์๋ ์์ ํ๋ ๋ฌธ์  ํด๊ฒฐ
```

```css
link:link,
link:visited {
  border: 1px solid currentColor;
}
```

#### + transparent

```
:hover ํ์ ๋ border: none ์ด๋ฉด border-width ์์ค๋ก ํ์ด์ง ์ ์ฒด๊ฐ ์์ง์ด๋ ๋ฌธ์  ํด๊ฒฐ
```

```css
link:hover,
link:active {
  border: 1px solid transparent;
}
```

# Testimonials section

```
* figure
* blockquote
* grid template fr unit
* overflow: hidden
```

## ๐ก figure

```
self-contained content, like illustrations, diagrams, photos, code listings, etc
```

figure tag์ img์ blockquote๋ฅผ ๋ฃ์ด
๊ฐ์ธ๋ง๋ค ๊ฐ๊ฐ์ figure์ ๊ฐ๋๋ก ํจ

## ๐ก fr unit

```css
grid-template-columns: 40fr 60fr;
```

```
์ซ์์ ํฌ๊ธฐ๋ฅผ ํค์์ ๋ค์ํ๊ฒ ํฌ๊ธฐ์กฐ์  ๊ฐ๋ฅ
```

## ๐ก overflow: hidden

```
transform: scale(1.2)๋ก ํฌ๊ธฐ๊ฐ ์ปค์ง element๋ ์ฃผ๋ณ์ ์ํฅ์ ๋ผ์น๊ณ  ์ง์ ๋ถํด ๋ณด์

img container์ overflow: hidden ์ค์ 

์ฌ์ง์ด ์ ํด์ง ๋ฒ์์์ ๊ฐ๊น์ด ๋ค๊ฐ์ค๋ ํจ๊ณผ
```
