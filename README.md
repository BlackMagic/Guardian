## Formatting your Guardian comments
This is a short guide to the art of adding selected HTML tags to your Guardian comments to make them appear more professional.

HTML tags are used for a variety of functions on a web page. The functions include: making text **bold** so that it stands out from surrounding text, underlining <ins>selected text</ins> for emphasis, putting text *in italics* when quoting a source, and providing external links to an article that you want your comment to reference for additional or supporting information.

Some of this functionality is already available in Guardian-provided functions, but generally the Guardian functions result in lack of control and inferior representation of the intended end-result. This is particularly true when inserting external links into Guardian comments.

### Let us begin...

HTML tags come in matching pairs: an opening tag and a closing tag. Text of your choosing is inserted between the tags, and will be formatted accordingly by the browser that renders the comment on the Guardian website.  

This article considers a limited subset of all HTML tags. Why is the subset limited? One reason is that you will only need to use a handful of HTML tags to get superior Guardian comments; the other reason is that the Guardian web browser will ignore HTML tags that might cause unpredictable or unsupported results.

Opening HTML tags consist of the character '<', a single-character tag identifier, and the terminating character '>'. Examples are: `<i>, <b>, <a>,`etc. 
  
Closing HTML tags consist of the character '<' followed by the character '/', a single-character tag identifier, and the terminating character '>'. Examples are: `</i>, </b>, </a>,`etc. 

Opening and closing HTML tags must be matching pairs, ie, every opening tag must be matched by a closing tag following it somewhere in the user-supplied text. For example: `<i>Hello World!</i>`is a matching pair that the browser will display as <i>Hello World!</i>.

#### Underlining text
`<u>Jack and Jill went up the hill</u>`will display as <ins>Jack and Jill went up the hill</ins>. Underlining text is discouraged as it may lead to confusion with HTML links, but it is an acceptable way to draw attention to certain text passages, such as the names of publications or authors.

#### Making text bold for emphasis
`<b>Jack and Jill went up the hill</b>`will display as <b>Jack and Jill went up the hill</b>. This is an ideal way to make words or passages of text stand out from the surrounding material.

#### Setting text in italics for emphasis
`<i>Jack and Jill went up the hill</i>`will display as <i>Jack and Jill went up the hill</i>. This format is usually used for direct quotations, such as: The President said, "<i>Ask not what your country can do for you...</i>"

#### Using bold and italics
`<b><i>Jack and Jill went up the hill</i></b>`will display as <b><i>Jack and Jill went up the hill</b></i>. This format is ideal for setting off a quotation or a topic to attract maximum attention to it. The order of the closing HTML tags is not important so long as they are evenly matched with the opening tags.

#### Creating external links in your comments
This operation is slightly more complex and involves interaction with the Guardian's link function, which can be found below the dialog box that your comment is entered into.

Assume you want to create a link in your comment to this article: https://en.wikipedia.org/wiki/Ontological_argument, and your comment looks like this: Please refer to <b>St Anselm's ontological argument</b> for further details. The bolded text, when clicked, will link to the article.

How do we begin? First locate the article or item you want to link to, in this case the Wikipedia article about the ontological argument. Copy its URL onto the clipboard. This can be done with a mouseclick if you're using a PC or a laptop, and is slightly more complicated when using a smartphone or tablet.

Place the cursor directly in front of the text in your comment that you want to serve as the link, in this case the word <i>St</i>. Now click on the link box below the comment box. A dialogue box opens and the characters <i>http://www.</i> are highlighted. Replace the highlighted characters with the URL that you copied to the clipboard and press the OK button.

The URL reference now appears in your comment, but it has to be edited before it will do exactly what you want it to do. The full URL will look like this: `<a href="https://en.wikipedia.org/wiki/Ontological_argument"> https://en.wikipedia.org/wiki/Ontological_argument</a>` 

Delete all the characters from the second <i>`https`</i>up to but not including the final <i>`</a>`.</i> Change the <i>`</a>`</i> to <i>`<b>`</i> and place these characters after the word <i>argument</i>.
