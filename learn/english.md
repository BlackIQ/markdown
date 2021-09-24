# Learn Markdown (English)

Learn **Markdown** so easy in here.

- ## Heading

What are **Heading**s? The title or the name of a document or even an chapter of a book is a **Heading**. Now, let's learn how to use them!

In **HTML** we use `<h1></h1>` tag. These are **Heading**s. But not **md**. We use `#` instead of `<h1></h1>` tags. Fitst I will show you **HTML** way and next, **Markdown**!

HTML:

```html
<h1>Heading</h1>
<h2>Heading</h2>
<h3>Heading</h3>
<h4>Heading</h4>
<h5>Heading</h5>
<h6>Heading</h6>
```

Output:

# Heading
## Heading
### Heading
#### Heading
##### Heading
###### Heading

Ok, But how to use these in **Markdown**?

Markdown:

```markdown
# Heading
## Heading
### Heading
#### Heading
##### Heading
###### Heading
````

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
```html
This is <b>Amir</b>. Nice to meet <b>you</b>.
```

Output:

This is **Amir**. Nice to meet **you**.

In **MD** there is no differences.

Markdown:

```markdown
This is **Amir**. Nice to meet **you**.
```

Output:

This is **Amir**. Nice to meet **you**.

Ok, Now how to make a text **italic**? Just use one star `*`.

HTML:
```html
He said <i>I love to use Git in my projects</i>.
```

Output:

He said *I love to use Git in my projects*.

Again, in **MD** there is no differences.

Markdown:

```markdown
He said *I love to use Git in my projects*.
```

Output:

He said *I love to use Git in my projects*.

---

- ## Links

You may wanted to add a link in your text. You wanna use **HTML** tag!? Stop doing that!

You can easily do that in **MD** syntax. Let's take a look to **HTML**.

HTML:

```html
Open <a href="https://google.com">Google</a>
```

Output:

Open [Google](https://google.com)

Markdown:

```markdown
Open [Google](https://google.com)
```

Open [Google](https://google.com)

Simple, We created links! Fitst part in `[]`, Put the text and in `()` put the link.

---

- ## Images

I love puting images in **Markdown**. Simple, Fast and easy syntax. As always, how is **HTML** way?

HTML:

```html
<img alt="Tree" src="https://wallpapercave.com/wp/wp3385761.jpg">
```

Output:

[![Tree](https://wallpapercave.com/wp/wp3385761.jpg)](https://wallpapercave.com/wp/wp3385761.jpg)

In **MD** this is more easiler. Just pay attention.

Markdown:

```markdown
[![Image Alt](image url)](link of picture)
```

Ok, In first sight, what did you remember? Linking. Right. kind of same. But in Link text we use `![image alt](image url)`. Image url is the image `src` and image alt is a text that if pictue couldn't load, text will be appear. And `link of picture` is a link that will be for picture. I mean when people click on it, will go to that link.

That was how we use images!

---