<div dir="rtl">

# Learn Markdown (English)

Learn **Markdown** so easy in here.

- ## Heading

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

Output:

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

Output:

# Heading
## Heading
### Heading
#### Heading
##### Heading
###### Heading

As you can see, we use `#`. If your heading is `<h2>`, use `##`. Hope you got the point!

---

- ## Text style

The meaning of text styles is the same as **bolding** and **italicizing** the text.

In **HTML** we use `<b></b>` tags. In **md** we just use `**` in start and end of the text. Look at examples.

HTML:

<div dir="ltr">

```html
This is <b>Amir</b>. Nice to meet <b>you</b>.
```

</div>

Output:

This is **Amir**. Nice to meet **you**.

In **MD** there is no differences.

Markdown:

<div dir="ltr">

```markdown
This is **Amir**. Nice to meet **you**.
```

</div>

Output:

This is **Amir**. Nice to meet **you**.

Ok, Now how to make a text **italic**? Just use one star `*`.

HTML:

<div dir="ltr">

```html
He said <i>I love to use Git in my projects</i>.
```

</div>

Output:

He said *I love to use Git in my projects*.

Again, in **MD** there is no differences.

Markdown:

<div dir="ltr">

```markdown
He said *I love to use Git in my projects*.
```

</div>

Output:

He said *I love to use Git in my projects*.

---

- ## Links

You may wanted to add a link in your text. You wanna use **HTML** tag!? Stop doing that!

You can easily do that in **MD** syntax. Let's take a look to **HTML**.

HTML:

<div dir="ltr">

```html
Open <a href="https://google.com">Google</a>
```

</div>

Output:

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

- ## Images

I love puting images in **Markdown**. Simple, Fast and easy syntax. As always, how is **HTML** way?

HTML:

<div dir="ltr">

```html
<img alt="Tree" src="https://wallpapercave.com/wp/wp3385761.jpg">
```

</div>

Output:

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

- ## Lists

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

Output:

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

- ## Highlights

Time to say the part that is really good. The reason that we use **Markdown**. that is **Highlight**ing codes or inline text.

First lets speak about **inline**. Well we have nothing like this in **HTML**. Let's go to **markdown** code right now.

<div dir="ltr">

```markdown
This is an `inline highlighted` text.
```

</div>

Output:

This is an `inline highlighted` text.

Ok, now we know about inline highlights. But how to create something like this? :

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

Simple! Look at the code below:

[![Image of highlights](md-highlight.png)](https://github.com/BlackIQ/markdown)

What is `name`? Name is the name of the language that are you writing code in. That block was Python. So I used `python` front of ` ``` `.

Done with **Highlight**s.

---

- ## TODO

You can use **TODO** in **markdown**.

- [x] Go school
- [ ] Buy some LEDs
- [x] Wash my hands :)

<div dir="ltr">

```markdown
- [x] Go school
- [ ] Buy some LEDs
- [x] Wash my hands :)
```

</div>

Use **TODO**s. They are funny!

---

- ## Quote

Think you want to add a **quote**. Like this:

> I'm gonna make him an offer he can't refuse.

So, use this structure:

<div dir="ltr">

```markdown
> I'm gonna make him an offer he can't refuse
```

</div>

</div>