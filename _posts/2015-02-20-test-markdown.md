---
layout: post
title: Test markdown
subtitle: Each post also has a subtitle
---

You can write regular [markdown](http://markdowntutorial.com/) here and Jekyll will automatically convert it to a nice webpage.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](http://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:
 
| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |
 

How about a yummy crepe?

![Crepe](http://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}


# MarkDown 语法

Day One Markdown Syntax


### Basics

	*italic* or _italic_  /  **bold** or __bold__
*italic* or _italic_  /  **bold** or __bold__

	An inline link: [example](http://dayoneapp.com/markdown).
	 
An inline link: [example](http://dayoneapp.com/markdown). 

	An id link [example][id].
 	  [id]: http://dayoneapp.com/markdown
 	  
An id link [example][id].

   [id]: http://dayoneapp.com/markdown
   
An auto-linked URL: http://dayoneapp.com/markdown


### Headers

	# Header 1
	## Header 2
	### Header 3
	#### Header 4
	##### Header 5
	###### Header 6


# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6


### Lists

	1. Numbered 
	2. List
1. Numbered 
2. List

	- Bulleted
	- List
- Bulleted
- List


### Images

	![alt text](https://s3.amazonaws.com/dayoneappcom/images/dayone-folder.png)
	
![Alt Text](https://s3.amazonaws.com/dayoneappcom/images/dayone-folder.png)


### Blockquotes

	> Angle brackets are used for blockquotes.
	
> Angle brackets are used for blockquotes.


### Tables

	One | Two | Three

	--- | --- | ---
	Blue | White | Gray
	Green | Yellow | Red

One | Two | Three
--- | --- | ---
Blue | White | Gray
Green | Yellow | Red

### Horizontal Rules

	Three or more dashes or asterisks --- ***
	
---

### Code & Preformatted Text

`<code>` spans are delimited by backticks. You can include literal backticks like `` `this` ``.

	[TAB]Preformatted text block using a tab.

	Preformatted text block using a tab.

