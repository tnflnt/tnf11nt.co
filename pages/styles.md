---
title: Styles
metaDescription: 
date: 2023-01-01T00:00:00.000Z
permalink: /styles/index.html
---
This is a simple demo/test page for styles and components while I fiddle with things.

## Block Elements

### Paragraphs and Line Breaks

**Magnam enim explicabo est commodi** odio ullam eius illo sint unde ut omnis quia. Provident *magni eveniet* veniam recusandae ut et ea tempora aut quaerat alias corrupti quo. Aperiam iure error dolores et omnis quia nemo nam. Consequatur rerum vel qui vero voluptatem at [error laudantium]() quam et adipisci rem modi. Beatae quae non aliquam mollitia rerum labore rerum maiores et et aut maiores. Mollitia doloribus expedita commodi aliquid ratione nesciunt officia ab doloribus provident.

Aut quis aliquid corporis commodi architecto fugit provident. Magnam omnis nulla eum et ab inventore beatae.

### Headers

# Header 1

Sit non occaecati officia quis et excepturi corporis et explicabo dignissimos sed itaque eos quas quia. Dolor consectetur voluptas nihil consequatur velit maiores. Vero delectus blanditiis consequatur aspernatur sit possimus.

## Header 2

Placeat labore consectetur nobis illum consequatur quis ea laborum voluptatem occaecati incidunt dolores eum quidem. Aut ut dolore sed et tempora deserunt maxime molestias excepturi ut laudantium et quisquam reiciendis quia. Odit unde tempore voluptas vel doloremque ipsum rem velit maxime magni est explicabo consectetur magni.

### Header 3

Ut quia omnis delectus nam non magnam explicabo unde rem unde tenetur accusantium quo culpa. Fugit possimus deleniti itaque nostrum voluptatem veniam et. Unde est rem quo ut autem aut necessitatibus quia ut beatae quidem sapiente.

#### Header 4

Fugiat neque rerum et ut repellat dolorem a. Voluptatem sunt suscipit reprehenderit sit. Ea velit consequatur ut ut temporibus corporis et id aliquam dolores beatae eum.

##### Header 5

Non et qui voluptatem nostrum totam sunt repudiandae et est commodi velit. Voluptatum similique ut non fugiat error ut maiores ut voluptatibus odio maxime voluptatem voluptas. Totam sit itaque est minima adipisci at sed itaque ut odit et consequatur perferendis velit nam.

###### Header 6

Eum minima quo nulla. Blanditiis distinctio nobis suscipit quis doloremque laudantium at qui enim fugit nihil fugit. Nostrum ad necessitatibus laudantium.

### Blockquotes

Cum ut culpa nostrum quibusdam et.

> Architecto est iste accusamus modi voluptatibus ea nulla quam. Nisi minima vel enim aliquid fuga impedit rerum maiores blanditiis beatae. Sunt consequuntur perspiciatis omnis.

> Sunt nihil eveniet sequi dolorem atque vero officiis fugit deleniti est pariatur et. 
> 
> > Maiores sapiente voluptate nobis quam. 
> 
> Quo nisi omnis animi modi qui autem tempora hic omnis corrupti laudantium aspernatur porro eaque.

### Lists

Markdown supports ordered (numbered) and unordered (bulleted) lists.

Unordered lists use asterisks, pluses, and hyphens -- interchangably -- as list markers:

*   Red
*   Green
*   Blue

is equivalent to:

+   Red
+   Green
+   Blue

and:

-   Red
-   Green
-   Blue

Ordered lists use numbers followed by periods:

1.  Bird
2.  McHale
3.  Parish

It's important to note that the actual numbers you use to mark the list have no effect on the HTML output Markdown produces. If you instead wrote the list in Markdown like this:

1.  Bird
1.  McHale
1.  Parish

or even:

3. Bird
1. McHale
8. Parish

you'd get the exact same HTML output. The point is, if you want to, you can use ordinal numbers in your ordered Markdown lists, so that the numbers in your source match the numbers in your published HTML. But if you want to be lazy, you don't have to.

List items may consist of multiple paragraphs. Each subsequent paragraph in a list item must be indented by either 4 spaces or one tab:

1.  This is a list item with two paragraphs. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.

	Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus. Donec sit amet nisl. Aliquam semper ipsum sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.

To put a blockquote within a list item, the blockquote's `>` delimiters need to be indented:

*   A list item with a blockquote:

	> This is a blockquote inside a list item.

To put a code block within a list item, the code block needs to be indented *twice* -- 8 spaces or two tabs:

*   A list item with a code block:

		<code goes here>

### Code Blocks

Pre-formatted code blocks are used for writing about programming or markup source code. Rather than forming normal paragraphs, the lines of a code block are interpreted literally. Markdown wraps a code block in both `<pre>` and `<code>` tags.

To produce a code block in Markdown, simply indent every line of the block by at least 4 spaces or 1 tab.

This is a normal paragraph:

	This is a code block.

Here is an example of AppleScript:

	tell application "Foo"
		beep
	end tell

A code block continues until it reaches a line that is not indented (or the end of the article).

Within a code block, ampersands (`&`) and angle brackets (`<` and `>`) are automatically converted into HTML entities. This makes it very easy to include example HTML source code using Markdown -- just paste it and indent it, and Markdown will handle the hassle of encoding the ampersands and angle brackets. For example, this:

	<div class="footer">
		&copy; 2004 Foo Corporation
	</div>

Regular Markdown syntax is not processed within code blocks. E.g., asterisks are just literal asterisks within a code block. This means it's also easy to use Markdown to write about Markdown's own syntax.

```
tell application "Foo"
	beep
end tell
```

## Span Elements

### Links

Markdown supports two style of links: *inline* and *reference*.

In both styles, the link text is delimited by [square brackets].

To create an inline link, use a set of regular parentheses immediately after the link text's closing square bracket. Inside the parentheses, put the URL where you want the link to point, along with an *optional* title for the link, surrounded in quotes. For example:

This is [an example](http://example.com/) inline link.

[This link](http://example.net/) has no title attribute.

### Emphasis

Markdown treats asterisks (`*`) and underscores (`_`) as indicators of emphasis. Text wrapped with one `*` or `_` will be wrapped with an HTML `<em>` tag; double `*`'s or `_`'s will be wrapped with an HTML `<strong>` tag. E.g., this input:

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

### Code

To indicate a span of code, wrap it with backtick quotes (`` ` ``). Unlike a pre-formatted code block, a code span indicates code within a normal paragraph. For example:

Use the `printf()` function.
