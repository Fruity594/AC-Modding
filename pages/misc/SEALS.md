<html>
 <head>
  <meta name="description" content="Just a documentation page for myself where I write stuff down for later use.">
  <title>SEALS</title>
</head> 
</html>

Page for my own sort of *documentation*, and just to test a bit of things. You aren't gonna find anything interesting here (unless you do, and in such case your welcome for the free knowledge)


# me own md doc

Text? It's very special. It can be **bold**, *italic*, ~~strikethrough~~ or even `inline`!

Text can be **bold** by wrapping it in double **asterisks** or __underscores__. 

![MD_Bold](../../assets/images/misc/MD_Bold.png)

Text can be *italic* by wrapping it in single *asterisks* or _underscores_.

![MD_Italic](../../assets/images/misc/MD_Italic.png)

Text can be ~~strikethrough~~ by wrapping it in double tildes.

![MD_Strikethrough](../../assets/images/misc/MD_Strikethrough.png)

Text can be `inline` by wrapping it in single `backticks`.

![MD_Inline](../../assets/images/misc/MD_Inline.png)

Text can be shown normally, \*without formatting*, by using backslashes.

![MD_Backslash](../../assets/images/misc/MD_Backslash.png)

On the topic of text hiding its formatting, any text within inline won't have any formatting! `**Pretty Pog Man!**`

[Linking to another page is easy!](https://www.youtube.com/c/inconsistent_dg/)

![MD_PageLink](../../assets/images/misc/MD_PageLink.png)

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. Otherwise, text would end up on the same line!
Like in this example!

# Header 1

This is a very normal paragraph header. Inconsistent_dg is one of the nicest guys you'll meet on the internet! [I heard he makes great youtube videos too!](https://www.youtube.com/watch?v=i6CVfUjJchE)

Headers start off with a hashtag `#`, adding more hashtags means "less-important" headers, ones that will just be smaller than the others.

This is Header 1, the largest (and most important!) a header can get. The lowest one can be is a level 6 header.

![MD_Header](../../assets/images/misc/MD_Header.png)

## Header 2

Blockquotes are pretty Poggers! They are used by adding a greater than sign before your text.

> Look Mom look! I'm a blockquote!
>
> You're looking different... new haircut? Either way you're still cute <3

![MD_Blockquote](../../assets/images/misc/MD_Blockquote.png)

### Header 3

While we're here, might as well talk about code blocks! You make them by wrapping all of your text within three backticks ```.

```
Animal Crossing™: New Horizons for Nintendo Switch and Nintendo Switch Lite handheld consoles, owned by and licenced by Nintendo©
```

![MD_Codeblock](../../assets/images/misc/MD_Codeblock.png)

That's just text, but these indeed can be used for code! If you're interested in sprucing the code up a bit, you can specify a language for **syntax highlighting**! Simply type the name of the language after the first trio of backticks.

```js
// I'm JavaScript code! Poggers!
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```
![MD_Syntax-Codeblock-JS](../../assets/images/misc/MD_Syntax-Codeblock-JS.png)

```ruby
# I'm Ruby code! Poggers!
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```
![MD_Syntax-Codeblock-Ruby](../../assets/images/misc/MD_Syntax-Codeblock-Ruby.png)

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

I am totally fine.

Below is a <span data-audio-url="../../assets/misc/TABLE.mp3">table.</span>

<script>
$("[data-audio-url]").each(
    function(){
        $(this).on('click', function() {
            var mp3Url = $(this).attr('data-audio-url');
            var a = new Audio(mp3Url);
            a.play();
        });
    }
);
</script>

| **SUBSCRIBE**               | **TO**                                 | **twitch.tv/inconsistent_dg** |
|:----------------------------|:---------------------------------------|:------------------------------|
| One in 3 people are lazy... |                                        | Neither am I...               |
| I'm not lazy.               |                                        | That only leaves...           |
|                             | ![me](../../assets/images/misc/me.png) |                               |

![MD_TABLE](../../assets/images/misc/MD_TABLE.png)

### Ever heard of a thematic break?

There's multiple ways to show them. A sequence of 3 asterisks `*`, underscores `_`, or hyphens `-` can result in this!

***
---
___

![MD_Thematic_Break](../../assets/images/misc/MD_Thematic_Break.png)

### Here's a list:

Normal lists can start off with either an asterisk `*` or a hyphen `-`.

* Yo
* Waddup
* Gamer
* Girl :)
  * You smell
    * Poggers!!

- What's
- The
- Difference?

![MD_List](../../assets/images/misc/MD_List.png)

### But now an ordered list!:

Ordered lists have to start with numbers. ANY numbers! Whether or not they start off with what's considered "the first number". It will just go from the starting number. So if instead of 1 you wanted to start the list off with 6, go ahead!

6.  Yo
4.  Waddup
9.  Gamer
    1. boy?
10. Girl! :)
    1.  Yes indeed these can be multi level!
    2.  Hi mom!

![MD_List-ORDERED](../../assets/images/misc/MD_List-ORDERED.png)

### Images!

Images are basically just like links, except they'll have ! before them. You'll see!

![PKBae](../../assets/images/misc/PKBae.png)

![MD_PK](../../assets/images/misc/MD_PK.png)

### Best of all: HTML!

HTML works just fine in Markdown, allowing people to still do more advanced techniques that aren't taught in school.

```
Wanna know something cool? Long, single lined paragraphs in a code block actually won't wrap around! Instead, there will be a scroll bar. At some point, this text right here will be long enough to prove that! And if not, oh well! Sorry for disappointing you again Mom!
```
# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

####### Oops! No 7+ headers!