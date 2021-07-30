<h1>HTML Tutorials</h1>

<h2>What will you learn in this tutorial</h2>

<h2>Tools Needed</h2>


<h2>Basics</h2>

<h2> Getting Started </h2>

<p> Write about what is HTML about </p>

<p> HTML page layout</p>

<p> Doctype </p>
<img src="https://github.com/bharath9788/HTML-tutorial/blob/5cb843d3a5925d2eea464877b6acc27fa700c9e6/1.gif" alt="basics" />


<h2> Deep Dive into basic stucture of HTML </h2>

<pre>
&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
  &lt;meta charset="UTF-8"&gt;
   &lt;meta http-equiv="X-UA-Compatible" content="IE=edge"&gt;
 &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
  &lt;title>Document&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;/body&gt;
&lt;/html&gt;
</pre>

<p> The first line is called the DOCTYPE declaration. This tells the browser that the document is of type HTML. The most important thing to know is that the &lt;head&gt; section, which has   &lt;meta"&gt; tags. the <strong>charset</strong> in the meta tag tells the brower the character set used in our HTML document. We are using the UTF-8 character set. As you know, machines dont understand characters and they can only understand 1's and 0's. And the only way to tell the machine about hte chacters in our browser is to map the chacters to the numbers. This mapping is called character set. The first character set developed was ASCII, but they are only limited to English characters. Hence, we are now using UTF-8 character set, which represents most of the languages. </p>


<h2>Text in HTML</h2>

<h3> &lt;p&gt; &lt;/p&gt; tag</h3>
<p>To insert text in the HTML page, we can use &lt;p&gt; &lt;/p&gt; tags as shown in the below video. This tag is used to define a paragraph. 

<h4>&lt;em&gt; &lt;/em&gt;</h4>
We can wrap text in the &lt;em&gt; &lt;/em&gt; tag. These are used to mark up a emphasized text in the document. This will make the text italic. However, the usecase of this tag is not to make the text look italic. We have to use CSS if we need to change the font. But, teh emphasized tag is used to increase the emphasis of the text. This will help the search engines to better better results for our page. 


<h4>&lt;strong&gt; &lt;/strong&gt;</h4>

Similar to emphasized tag, we have strong tag. This is used mark the important text in the document. Again this is used by searcg engines for better optimization.

    
    <h3>Headings tag</h3>
    Apart from this, we also have heading tags -  &lt;h1&gt; &lt;/h1&gt; ... &lt;h6&gt; &lt;/h6&gt;
tags. These are used to add headings to the HTML page. Please check the style of these heading tags in the video.
You may be under impression that these tags are used based on these fonts. But you will be wrong if you would think that way.
You should always follow the structure of the HTML: H1 is followed by H2 and so on.. this will help search engines for optmzation. Additionally, HTML page should have ONE H1 tag. Again, please check below video on how the structure should look.     </p>

The below video will provide a detailed demo of these tags.






<h2>Entities in HTML</h2>

A few characters in HTML are reserved, such as < and >. if we use these in HTML, browser will consider these as tags. There are many such reserved characters. To solve this problem, 
we use entites. Entities start with & and end with ;. Between these, we use entity name. Hence, < can be show as <b>&amp;lt;</b> and > can be shown as <b>&amp;gt;</b>.

