<div dir="rtl">

# آموزش زبان Markdown (فارسی)

اینجا زبان **markdown** را یادبگیرید.

- ## هدینگ یا سربرگ

What are **Heading**s? The title or the name of a document or even an chapter of a book is a **Heading**. Now, let's learn how to use them!

In **HTML** we use `<h1></h1>` tag. These are **Heading**s. But not **md**. We use `#` instead of `<h1></h1>` tags. Fitst I will show you **HTML** way and next, **Markdown**!

HTML:

<div dir="ltr">

```html
<h1>Heading</h1>
<h2>Heading</h2>
<h3>Heading</h3>
<h4>Heading</h4>
<h5>Heading</h5>
<h6>Heading</h6>
```

</div>

خروجی:

# Heading
## Heading
### Heading
#### Heading
##### Heading
###### Heading

Ok, But how to use these in **Markdown**?

Markdown:

<div dir="ltr">

```markdown
# Heading
## Heading
### Heading
#### Heading
##### Heading
###### Heading
```

</div>

خروجی:

# Heading
## Heading
### Heading
#### Heading
##### Heading
###### Heading

As you can see, we use `#`. If your heading is `<h2>`, use `##`. Hope you got the point!

---

- ## استایل متن

The meaning of text styles is the same as **bolding** and **italicizing** the text.

In **HTML** we use `<b></b>` tags. In **md** we just use `**` in start and end of the text. Look at examples.

HTML:

<div dir="ltr">

```html
This is <b>Amir</b>. Nice to meet <b>you</b>.
```

</div>

خروجی:

This is **Amir**. Nice to meet **you**.

In **MD** there is no differences.

Markdown:

<div dir="ltr">

```markdown
This is **Amir**. Nice to meet **you**.
```

</div>

خروجی:

This is **Amir**. Nice to meet **you**.

Ok, Now how to make a text **italic**? Just use one star `*`.

HTML:

<div dir="ltr">

```html
He said <i>I love to use Git in my projects</i>.
```

</div>

خروجی:

He said *I love to use Git in my projects*.

Again, in **MD** there is no differences.

Markdown:

<div dir="ltr">

```markdown
He said *I love to use Git in my projects*.
```

</div>

خروجی:

He said *I love to use Git in my projects*.

---

- ## لینک ها

You may wanted to add a link in your text. You wanna use **HTML** tag!? Stop doing that!

You can easily do that in **MD** syntax. Let's take a look to **HTML**.

HTML:

<div dir="ltr">

```html
Open <a href="https://google.com">Google</a>
```

</div>

خروجی:

Open [Google](https://google.com)

Markdown:

<div dir="ltr">

```markdown
Open [Google](https://google.com)
```

</div>

Open [Google](https://google.com)

Simple, We created links! Fitst part in `[]`, Put the text and in `()` put the link.

---

- ## عکس ها

I love puting images in **Markdown**. Simple, Fast and easy syntax. As always, how is **HTML** way?

HTML:

<div dir="ltr">

```html
<img alt="Tree" src="https://wallpapercave.com/wp/wp3385761.jpg">
```

</div>

خروجی:

[![Tree](https://wallpapercave.com/wp/wp3385761.jpg)](https://wallpapercave.com/wp/wp3385761.jpg)

In **MD** this is more easiler. Just pay attention.

Markdown:

<div dir="ltr">

```markdown
[![Image Alt](image url)](link of picture)
```

</div>

Ok, In first sight, what did you remember? Linking. Right. kind of same. But in Link text we use `![image alt](image url)`. Image url is the image `src` and image alt is a text that if pictue couldn't load, text will be appear. And `link of picture` is a link that will be for picture. I mean when people click on it, will go to that link.

That was how we use images!

---

- ## لیست ها

We use 2 kind of lists. Ordinary and Unordinary. `ol` and `ul`. But this is just for **HTML**. We can use unordinary list in **Markdown**.

HTML:

<div dir="ltr">

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

</div>

خروجی:

- Item 1
- Item 2
- Item 3

And in **MD** we just use `-`!

Markdown:

<div dir="ltr">

```markdown
- Item 1
- Item 2
- Item 3
```

</div>

How easy was that!? So much :)

---

- ## هایلایت ها

وقتشه که بخشی رو توضیح بدیم که خیلی خوشم میاد ازش. اون هم **هایلایت** ها میباشد. هایلایت های بلاکی و حتی هایلایت های خطی.

ابتدا در باره هایلایت **خطی** صحبت میکنیم. همچین چیزی داخل **HTML** وجود ندارد. پس مستقیم میریم سراغ کد **Markdown**.

<div dir="rtl">

```markdown
این یک `متن هایلایت شده` مباشد.
```

</div>

خروجی:

این یک `متن هایلایت شده` مباشد.

خب ما هایلایت خطی را یادگرفتیم. پس چطوری همچین چیزی رو میتونیم بسازیم؟ :

<div dir="ltr">

```python
from platform import system as pltfrm
from os import system as sstm

if pltfrm().lower() == "windows":
    sstm("cls")
elif pltfrm().lower() == "linux":
    sstm("clear")
else:
    sstm("clear")
```

</div>

خیلی ساده. به نمونه کد زیر دقت کنید.

<div dir="ltr">

[![Image of highlights](md-highlight.png)](https://github.com/BlackIQ/markdown)

</div>

خب، `name` چیست؟‌نام همان اسم زبان میباشد که ما کد آن را مینویسیم. آن بلاک، یک بلاک پایتون بود. پس از پایتون رو به روی ` ``` ` استفاده شد.

اتمام هایلایت ها!

---

- ## تودو ها

از تودو ها در **markdown** استفاده کنید.

- [x] رفتن به مدرسه
- [ ] خرید لامپ
- [x] شستن دست ها

<div dir="ltr">

```markdown
- [x] رفتن به مدرسه
- [ ] خرید لامپ
- [x] شستن دست ها
```

</div>

استفاده از تودو ها واقعا جالبه.

---

- ## نقل قول

فکر کنید میخواهید همچین نقل قولی را قرار دهید:

<div dir="ltr">

> I'm gonna make him an offer he can't refuse.

</div>

ساختار به این صورت میباشد.

<div dir="ltr">

```markdown
> I'm gonna make him an offer he can't refuse
```

</div>

</div>