<p align="center">
  <h1>GitHub Markdown Guide</h1>
</p>

<p>
This repository is about markdown and examples for it ,

<br>

<img align="center" src="Img/The Markdown Guide.png" width="300" heght="300"/>

<br><br>

I summarize the book for The Markdown Guide to Matt Cone and take the examples from this book to me which i can remember this examples in my work on github projects and to who want to study markdown to be good in write `README.md` file on projects on github, Enjoys 😉.

</p>

<hr>

### Headings :

`Markdown :`

```markdown
# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6
```

`html :`
```html
<h1>Heading level 1</h1>
<h2>Heading level 2</h2>
<h3>Heading level 3</h3>
<h4>Heading level 4</h4>
<h5>Heading level 5</h5>
<h6>Heading level 6</h6>
```

The output :

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

<br>
<hr>
<br>

### Paragraphs :

`Markdown :`
```markdown
I really like using Markdown.

I think I'll use it from now on.
```

`html :`
```html
<p>I really like using Markdown.</p>

<p>I think I'll use it from now on.</p>
```

The output :

I really like using Markdown.

I think I’ll use it from now on.

<br>
<hr>
<br>

### Line Breaks :

To create a line break (`<br>`).

`Markdown :`
```markdown
This is the first line.
And this is the second line.
```

`html :`
```html
<p>
  This is the first line.<br />
  And this is the second line.
</p>
```

The output :

This is the first line.

And this is the second line.

<br>
<hr>
<br>

### Emphasis :

You can add emphasis by making text bold or italic.

- #### Bold :

`Markdown :`
```markdown
I love **bold text**.

I love **bold text**.

Love**is**bold
```

`html :`
```html
I love <strong>bold text</strong>. Love <strong>is</strong> bold
```

The output :

I love **bold text**.

Love **is** bold.

<br>
<hr>
<br>

- #### Italic :

`Markdown :`
```markdown
The _cat's meow_.

The _cat's meow_.

A*cat*meow
```

`html :`
```html
The <em>cat's meow</em>. A <em>cat</em> meow
```

The output :

The _cat’s meow_.

A _cat_ meow

<br>
<hr>
<br>

- #### Bold and Italic :

`Markdown :`
```markdown
**_Important_** text.

**_Important_** text.

**_Important_** text.

**_Important_** text.
```

`html :`
```html
<strong><em>Important</em></strong> text.
```

The output :

**_Important_** text.

<br>
<hr>
<br>

### Blockquotes :

`Markdown :`
```markdown
> Dorothy followed her through many rooms.
```

`html :`
```html
<blockquote>
  <p>Dorothy followed her through many rooms.</p>
</blockquote>
```

The output :

<blockquote>
  <p>Dorothy followed her through many rooms.</p>
</blockquote>

- #### Blockquotes with Multiple Paragraphs

`Markdown :`
```markdown
> This the first paragraph.
>
> And this is the second paragraph.
```

`html :`
```html
<blockquote>
  <p>This the first paragraph.</p>
  <p>And this is the second paragraph.</p>
</blockquote>
```

The output :

> This the first paragraph.
>
> And this is the second paragraph.

<br>
<hr>
<br>

- #### Nested Blockquotes :

`Markdown :`
```markdown
> This the first paragraph.
>
> > And this is the nested paragraph.
```

`html :`
```html
<blockquote>
  <p>This the first paragraph.</p>
  <blockquote>
    <p>And this is the nested paragraph.</p>
  </blockquote>
</blockquote>
```

The output :

> This the first paragraph.
>
> > And this is the nested paragraph.

<br>
<hr>
<br>

- #### Blockquotes with Other Elements :

`Markdown :`
```markdown
> ##### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
> _Everything_ is going **well**.
```

`html :`
```html
<blockquote>
  <h5>The quarterly results look great!</h5>
  <ul>
    <li>Revenue was off the chart.</li>
    <li>Profits were higher than ever.</li>
  </ul>
  <p><em>Everything</em> is going <strong>well</strong>.</p>
</blockquote>
```

The output :

<blockquote>
  <h5>The quarterly results look great!</h5>
  <ul>
    <li>Revenue was off the chart.</li>
    <li>Profits were higher than ever.</li>
  </ul>
  <p><em>Everything</em> is going <strong>well</strong>.</p>
</blockquote>

<br>
<hr>
<br>

### Lists :

- #### Ordered Lists :

`Markdown :`
```markdown
1. First item
2. Second item
3. Third item
4. Fourth item

5. First item
6. Second item
7. Third item
8. Fourth item

9. First item
10. Second item
11. Third item
12. Fourth item
```

`html :`
```html
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
  <li>Fourth item</li>
</ol>
```

The output :

1. First item
2. Second item
3. Third item
4. Fourth item

<br>
<hr>
<br>

- #### Nesting Ordered List Items :

`Markdown :`
```markdown
1. First item
2. Second item
3. Third item
4. Indented item
5. Indented item
6. Fourth item
```

`html :`
```html
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>
    Third item
    <ol>
      <li>Indented item</li>
      <li>Indented item</li>
    </ol>
  </li>
  <li>Fourth item</li>
</ol>
```

The output :

<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item
    <ol>
      <li>Indented item</li>
      <li>Indented item</li>
    </ol>
  </li>
  <li>Fourth item</li>
</ol>

<br>
<hr>
<br>

- #### Unordered Lists :

`Markdown :`
```markdown
- First item
- Second item
- Third item
- Fourth item

* First item
* Second item
* Third item
* Fourth item

- First item

* Second item

- Third item

* Fourth item
```

`html :`
```html
<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
  <li>Fourth item</li>
</ul>
```

The output :

- First item
- Second item
- Third item
- Fourth item

<br>
<hr>
<br>

- #### Nesting Unordered List Items :

`Markdown :`
```markdown
- First item
- Second item
- Third item
  - Indented item
  - Indented item
- Fourth item
```

`html :`
```html
<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>
    Third item
    <ul>
      <li>Indented item</li>
      <li>Indented item</li>
    </ul>
  </li>
  <li>Fourth item</li>
</ul>
```

The output :

<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item
    <ul>
      <li>Indented item</li>
      <li>Indented item</li>
    </ul>
    </li>
     <li>Fourth item</li>
</ul>

<br>
<hr>
<br>

- #### Adding Elements in Lists :

- ##### Paragraphs

`Markdown :`
```markdown
- This is the first list item.
- Here's the second list item.

  I need to add another paragraph below the second list item.

- And here's the third list item.
```

`html :`
```html
<ul>
  <li><p>This is the first list item.</p></li>
  <li>
    <p>Here's the second list item.</p>
    <p>I need to add another paragraph below the second list item.</p>
  </li>
  <li><p>And here's the third list item.</p></li>
</ul>
```

The output :

<ul>
  <li><p>This is the first list item.</p></li>
  <li><p>Here's the second list item.</p>
    <p>I need to add another paragraph below the second list item.</p>
  </li>
  <li><p>And here's the third list item.</p></li>
</ul>

<br>
<hr>
<br>

- ##### Blockquotes

`Markdown :`
```markdown
- This is the first list item.
- Here's the second list item.

> A blockquote would look great here.

- And here's the third list item.
```

`html :`
```html
<ul>
  <li><p>This is the first list item.</p></li>
  <li>
    <p>Here's the second list item.</p>
    <blockquote>
      <p>A blockquote would look great here.</p>
    </blockquote>
  </li>
  <li><p>And here's the third list item.</p></li>
</ul>
```

The output :

<ul>
  <li><p>This is the first list item.</p></li>
  <li><p>Here's the second list item.</p>
    <blockquote>
      <p>A blockquote would look great here.</p>
    </blockquote>
  </li>
  <li><p>And here's the third list item.</p>
  </li>
</ul>

- ##### Code Blocks

`Markdown :`
```markdown
1. Open the file.
2. Find the following code block on line 21:

  <html>
    <head>
      <title>Test</title>
  </head>

3. Update the title to match the name of your website.
```

`html :`
```html
<ol>
  <li><p>Open the file.</p></li>
  <li>
    <p>Find the following code block on line 21:</p>
    <pre><code>&lt;html&gt;
     &lt;head&gt;
      &lt;title&gt;Test&lt;/title&gt;
     &lt;/head&gt;
    </code></pre>
  </li>
  <li><p>Update the title to match the name of your website.</p></li>
</ol>
```

The output :

<ol>
  <li><p>Open the file.</p></li>
  <li><p>Find the following code block on line 21:</p>
    <pre><code>&lt;html&gt;
     &lt;head&gt;
      &lt;title&gt;Test&lt;/title&gt;
     &lt;/head&gt;
    </code></pre>
  </li>
 <li><p>Update the title to match the name of your website.</p></li>
 </ol>

<br>
<hr>
<br>

- ##### Images

`Markdown :`
```markdown
1. Open the file containing Tux, the Linux mascot.
2. Marvel at its beauty.

![Tux](https://github.com/ahmedbadawihosny/GitHub-Markdown-Guide/blob/main/Img/Linux.png)

3. Close the file.
```

`html :`
```html
<ol>
  <li><p>Open the file containing Tux, the Linux mascot.</p></li>
  <li>
    <p>Marvel at its beauty.</p>
    <p><img src="https://github.com/ahmedbadawihosny/GitHub-Markdown-Guide/blob/main/Img/Linux.png" alt="Tux" /></p>
  </li>
  <li><p>Close the file.</p></li>
</ol>
```

The output :

<ol>
  <li><p>Open the file containing Tux, the Linux mascot.</p></li>
  <li>
    <p>Marvel at its beauty.</p>
    <p><img src="https://github.com/ahmedbadawihosny/GitHub-Markdown-Guide/blob/main/Img/Linux.png" alt="Linux" /></p>
  </li>
  <li><p>Close the file.</p></li>
</ol>

<br>
<hr>
<br>

### Code

`Markdown :`
```markdown
At the command prompt, type `nano`.
```

`html :`
```html
At the command prompt, type <code>nano</code>.
```

The output :

At the command prompt, type `nano`.

- #### Escaping Tick Marks :

`Markdown :`
```markdown
`` Use `code` in your Markdown file. ``
```

`html :`
```html
<code>Use `code` in your Markdown file.</code>
```

The output :

`` Use `code` in your Markdown file. ``

- #### Code Blocks :

In `Markdown :`

`Markdown :`
```markdown
<html>
  <head>
  </head>
</html>
```

In `HTML :`

`html :`
```html
<pre>
  <code>
    &lt;html&gt;
    &lt;head&gt;
    &lt;/head&gt;
    &lt;/html&gt;
  </code>
</pre>
```

<br>
<hr>
<br>

### Horizontal Rules :

`Markdown :`
```markdown
---
---

---
```

`html :`
```html
<hr />

<hr />

<hr />
```

The output :

---

<br>
<hr>
<br>

### Links :

`Markdown :`
```markdown
Use [Github Docs](https://docs.github.com/en).
```

`html :`
```html
<p>Use <a href="https://docs.github.com/en">Github Docs</a>.</p>
```

The output :

Use [Github Docs](https://docs.github.com/en).

- #### Adding Titles :

`Markdown :`
```markdown
Use [Github Docs](https://docs.github.com/en "Github Docs").
```

`html :`
```html
<p>
  Use
  <a href="https://docs.github.com/en" title="Github Docs">Github Docs</a>.
</p>
```

The output :

Use [Github Docs](https://docs.github.com/en "Github Docs").

- #### URLs and Email Addresses :

`Markdown :`
```markdown
<https://eff.org>

<fake@example.com>
```

`html :`
```html
<a href="https://eff.org">https://eff.org</a>
<a href="mailto:fake@example.com">fake@example.com</a>
```

The output :

<a href="https://eff.org">https://eff.org</a>
<a href="mailto:fake@example.com">fake@example.com</a>

- #### Formatting Links :

`Markdown :`
```markdown
I love supporting **[EFF](https://eff.org)**.
This is the _[EFF](https://eff.org)_.
```

`html :`
```html
<p>
  I love supporting <strong><a href="https://eff.org">EFF</a></strong
  >. This is the <em><a href="https://eff.org">EFF</a></em
  >.
</p>
```

The output :

I love supporting **[EFF](https://eff.org)**.
This is the _[EFF](https://eff.org)_.

<br>
<hr>
<br>

### Images

`Markdown :`
```markdown
![Computer Science map](https://github.com/ahmedbadawihosny/GitHub-Markdown-Guide/blob/main/Img/Computer%20Science%20map.png "Computer Science map")
```

`html :`
```html
<img src="https://github.com/ahmedbadawihosny/GitHub-Markdown-Guide/blob/main/Img/Computer%20Science%20map.png" alt="Computer Science map" title="Computer Science map"
/>
```

The output :

![Computer Science map](https://github.com/ahmedbadawihosny/GitHub-Markdown-Guide/blob/main/Img/Computer%20Science%20map.png "Computer Science map")

<br>
<hr>
<br>

- #### Image With link

`Markdown :`
```markdown
[![image alt text](https://i.imgur.com/sw215.jpeg)](https://imgur.com/gallery/sw215)
```

`html :`
```html
<a href="https://imgur.com/gallery/sw215">
  <img src="https://i.imgur.com/sw215.jpeg" />
</a>
```

[![image alt text](https://i.imgur.com/sw215.jpeg)](https://imgur.com/gallery/sw215)

<br>
<hr>
<br>

### Escaping Characters :

`Markdown :`
```markdown
\* Without the backslash, this would be a bullet in an unordered list.
```

`html :`
```html
<p>* Without the backslash, this would be a bullet in an unordered list\.</p>
```

The output :

<p>* Without the backslash, this would be a bullet in an unordered list\. </p>

<br>
<hr>
<br>

#### Characters You Can Escape :

|        Name         | Character |
| :-----------------: | :-------: |
|      backslash      |    `\`    |
|      tickmark       |     `     |
|      tickmark       |    `*`    |
|      tickmark       |    `_`    |
|    curly braces     |   `{}`    |
|      brackets       |   `[]`    |
|     parentheses     |   `()`    |
|     pound sign      |    `#`    |
|      plus sign      |    `+`    |
| minus sign (hyphen) |    `-`    |
|         dot         |    `.`    |
|  exclamation mark   |    `!`    |

<br>
<hr>
<br>

### Tables :

`Markdown :`
```markdown
| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |
```

`html :`
```html
<table>
  <thead>
    <tr class="header">
      <th>Syntax</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td>Header</td>
      <td>Title</td>
    </tr>
    <tr class="even">
      <td>Paragraph</td>
      <td>Text</td>
    </tr>
  </tbody>
</table>
```

The output :

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

<br>
<hr>
<br>

- #### Alignment Tables:

`Markdown :`
```markdown
| Syntax    | Description |   Test Text |
| :-------- | :---------: | ----------: |
| Header    |    Title    | Here's this |
| Paragraph |    Text     |    And more |
```

`html :`
```html
<table>
  <thead>
    <tr class="header">
      <th style="text-align: left;">Syntax</th>
      <th style="text-align: center;">Description</th>
      <th style="text-align: right;">Test Text</th>
    </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td style="text-align: left;">Header</td>
      <td style="text-align: center;">Title</td>
      <td style="text-align: right;">Here’s this</td>
    </tr>
    <tr class="even">
      <td style="text-align: left;">Paragraph</td>
      <td style="text-align: center;">Text</td>
      <td style="text-align: right;">And more</td>
    </tr>
  </tbody>
</table>
```

The output :

| Syntax    | Description |   Test Text |
| :-------- | :---------: | ----------: |
| Header    |    Title    | Here's this |
| Paragraph |    Text     |    And more |

<br>
<hr>
<br>

### Fenced Code Blocks

`Markdown :`
```markdown
{
"firstName": "John",
"lastName": "Smith",
"age": 25
}
```

`html :`
```html
<pre>
  <code>
    {
      &quot;firstName&quot;: &quot;John&quot;,
      &quot;lastName&quot;: &quot;Smith&quot;,
      &quot;age&quot;: 25
    }
  </code>
</pre>
```

The output :

<pre>
  <code>
    {
      &quot;firstName&quot;: &quot;John&quot;,
      &quot;lastName&quot;: &quot;Smith&quot;,
      &quot;age&quot;: 25
    }
  </code>
</pre>

<br>
<hr>
<br>

- #### Syntax Highlighting

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

`html :`
```html
<pre>
  <code class="language-json">
    {
      &quot;firstName&quot;: &quot;John&quot;,
      &quot;lastName&quot;: &quot;Smith&quot;,
      &quot;age&quot;: 25
    }
  </code>
</pre>
```

The output :

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

<br>
<hr>
<br>

### Footnotes

`Markdown :`
```markdown
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.
[^bignote]: Here's one with multiple paragraphs and code.

Indent paragraphs to include them in the footnote.

`{ my code }`

Add as many paragraphs as you like.
```

`html :`
```html
<p>
  Here’s a simple footnote,<a href="#fn1" class="footnote-ref" id="fnre\f1"><sup>1</sup></a>
  and here’s a longer one.<a href="#fn2" class="foot\
note-ref" id="fnref2"><sup>2</sup></a>
</p>
<section class="footnotes">
  <ol>
    <li id="fn1">
      <p>
        This is the first footnote.<a href="#fnref1" class="footnote-back"></a>
      </p>
    </li>
    <li id="fn2">
      <p>Here’s one with multiple paragraphs and code.</p>
      <p>Indent paragraphs to include them in the footnote.</p>
      <p><code>{ my code }</code></p>
      <p>
        Add as many paragraphs as you like.<a href="#fnref2" class="fo\otnote-back"></a>
      </p>
    </li>
  </ol>
</section>
```

The output :

<p>
  Here’s a simple footnote,<a href="#fn1" class="footnote-ref" id="fnre\f1"><sup>1</sup></a>
  and here’s a longer one.<a href="#fn2" class="foot\
note-ref" id="fnref2"><sup>2</sup></a>
</p>
<section class="footnotes">
  <ol>
    <li id="fn1">
      <p>
        This is the first footnote.<a href="#fnref1" class="footnote-back"></a>
      </p>
    </li>
    <li id="fn2">
      <p>Here’s one with multiple paragraphs and code.</p>
      <p>Indent paragraphs to include them in the footnote.</p>
      <p><code>{ my code }</code></p>
      <p>
        Add as many paragraphs as you like.<a href="#fnref2" class="fo\otnote-back"></a>
      </p>
    </li>
  </ol>
</section>

<br>
<hr>
<br>

### Heading IDs

`Markdown :`
```markdown
### My Great Heading {#custom-id}
```

`html :`
```html
<h3 id="custom-id">My Great Heading</h3>
```

The output :

<h3 id="custom-id">My Great Heading</h3>

<br>
<hr>
<br>

- #### Linking to Heading IDs

`Markdown :`
```markdown
[Heading IDs](#heading-ids)
```

`html :`
```html
<a href="#heading-ids">Heading IDs</a>
```

The output :

<a href="#heading-ids">Heading IDs</a>

<br>
<hr>
<br>

### Definition Lists

`Markdown :`
```markdown
First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.
```

`html :`
```html
<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>
```

The output :

<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>

<br>
<hr>
<br>

### Strikethrough

`Markdown :`
```markdown
The world is ~~flat~~ round.
```

`html :`
```html
<p>The world is <del>flat</del> round.</p>
```

The output :

<p>The world is <del>flat</del> round.</p>

<br>
<hr>
<br>

### Task (TODO) Lists

`Markdown :`
```markdown
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```

The output :

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

<br>
<hr>
<br>

### Automatic URL Linking

`Markdown :`
```markdown
http://example.com
```

`html :`
```html
<a href="http://example.com">http://example.com</a>
```

The output :

<a href="http://example.com">http://example.com</a>

<br>
<hr>
<br>

#### Disabling Automatic URL Linking

`Markdown :`
```markdown
`http://www.example.com`
```

`html :`
```html
<code>http://www.example.com</code>
```

The output :

<code>http://www.example.com</code>