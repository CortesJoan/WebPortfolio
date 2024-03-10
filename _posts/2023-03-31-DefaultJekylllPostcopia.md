---
layout: post
title: "MarkdownPost"
date: 2023-12-03 12:37:13 +0600
categories: [Technology]
author: ecuelass_chapman
post_image: "/assets/images/blog/blog-13.jpg"
author: "Themefishern't"
featured: true
---
-

# h1 Heading 8-)
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


## Horizontal Rules

___

---

***


## Typographic replacements

Enable typographer option to see result.

(c) (C) (r) (R) (tm) (TM) (p) (P) +-

test.. test... test..... test?..... test!....

!!!!!! ???? ,,  -- ---

"Smartypants, double quotes" and 'single quotes'


## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes


> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.


## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)


## Images

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

Like links, Images also have a footnote style syntax

![Alt text][id]

With a reference later in the document defining the URL location:

[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"


## Plugins

The killer feature of `markdown-it` is very effective support of
[syntax plugins](https://www.npmjs.org/browse/keyword/markdown-it-plugin).


### [Emojies](https://github.com/markdown-it/markdown-it-emoji)

> Classic markup: :wink: :cry: :laughing: :yum:
>
> Shortcuts (emoticons): :-) :-( 8-) ;)

see [how to change output](https://github.com/markdown-it/markdown-it-emoji#change-output) with twemoji.


### [Subscript](https://github.com/markdown-it/markdown-it-sub) / [Superscript](https://github.com/markdown-it/markdown-it-sup)

- 19^th^
- H~2~O


### [\<ins>](https://github.com/markdown-it/markdown-it-ins)

++Inserted text++


### [\<mark>](https://github.com/markdown-it/markdown-it-mark)

==Marked text==


### [Footnotes](https://github.com/markdown-it/markdown-it-footnote)

Footnote 1 link[^first].

Footnote 2 link[^second].

Inline footnote^[Text of inline footnote] definition.

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^second]: Footnote text.


### [Definition lists](https://github.com/markdown-it/markdown-it-deflist)

Term 1

:   Definition 1
with lazy continuation.

Term 2 with *inline markup*

:   Definition 2

        { some code, part of Definition 2 }

    Third paragraph of definition 2.

_Compact style:_

Term 1
  ~ Definition 1

Term 2
  ~ Definition 2a
  ~ Definition 2b


### [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

*[HTML]: Hyper Text Markup Language

### [Custom containers](https://github.com/markdown-it/markdown-it-container)

::: warning
*here be dragons*
:::
#11 time-saving pro tips for web designers working in Webflow11
##fgdsgfgg
*fff*
<blockquote class="blockquote single-quote">
  <p> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quo non labore totam tempora sed neque repellat numquam eaque inventore! Iusto saepe ipsum, ex, commodi asperiores iure dolores amet dolorem eos voluptatum, aliquid incidunt non perferendis earum dignissimos quod iste accusantium deleniti.Risus sociis urna elementum ultricies justo quisque, mattis in eros facilisis mauris vestibulum sed, luctus proin nibh nonummy integer, nullam sit eget cum duis. Et sodales blandit, libero pede suscipit, tincidunt amet </p>
</blockquote>
<h4>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</h4>
<p>eleifend hac porta faucibus aliquam eros, massa facilisis, sed pede maecenas porttitor id magnis. Ac sed aliquam in felis amet, adipiscing pede a amet faucibus sit, quis in et ullamcorper vel commodo. Volutpat ut pede sem ipsum non, sapien adipiscing, suspendisse neque, quis dolor donec dolor. Sit voluptatibus, scelerisque in semper lacus nostra, ac integer dolor mauris tempus eget</p>

 
<b>augue ullamcorper eros viverra neque,  feugiat tellus neque dui pellentesque, libero Lorem ipsum dolor sit amet, consectetur adipisicing elit. Suscipit est velit similique laborum, cumque aliquam porro dicta debitis repellat, tempore dignissimos, neque ab fuga voluptatibus. Earum numquam repellat sed perspiciatis ratione explicabo, odit! Repellendus voluptatibus nemo praesentiumaugue ullamcorper eros viverra neque, libero est metus libero. Lacinia wisi feugiat tellus neque dui pellentesque, libero Lorem ipsum dolor sit amet, consectetur adipisicing elit. Suscipit est velit similique laborum, cumque aliquam porro dicta debitis repellat, tempore dignissimos, neque ab fuga voluptatibus. Earum numquam repellat sed perspiciatis ratione explicabo, odit! Repellendus voluptatibus nemo praesentium  </b>