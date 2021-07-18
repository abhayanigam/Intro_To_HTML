<img src="" align="right" width="200" align="right" />

# <abbr title = "Hypertext Markup Language">HTML</abbr> CheatSheet

<div>

## Structure

This is the basic template or barebone structure of HTML.

### Boilerplate

<div class="code-toolbar">

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <title>Document</title>
    </head>
    <body>
    </body>
    </html>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

## Headings

There are six headings available in HTML, H1 is the largest among all, and H6 is the smallest.

### h1 Tag

<div class="code-toolbar">

    <h1>Heading 1</h1>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### h2 Tag

<div class="code-toolbar">

    <h2>Heading 2</h2>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### h3 Tag

<div class="code-toolbar">

    <h3>Heading 3</h3>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### h4 Tag

<div class="code-toolbar">

    <h4>Heading 4</h4>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### h5 Tag

<div class="code-toolbar">

    <h5>Heading 5</h5>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### h6 Tag

<div class="code-toolbar">

    <h6>Heading 6</h6>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

## Container

Container tags are the tags that contain some data such as text, image, etc. There are several container tags in HTML.

### div tag

div tag or division tag is used to make blocks or divisions in the document.

<div class="code-toolbar">

    <div> This is div block </div>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### span tag

span is a container for inline content

<div class="code-toolbar">

    <span> This is span block </span>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### p tag

Paragraph

<div class="code-toolbar">

    <p> This is a paragraph </p>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### pre tag

pre tag represents pre-formatted text

<div class="code-toolbar">

    <pre> Hello World </pre>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### code tag

code tag is used to represent source codes

<div class="code-toolbar">

    <code>
    import python
    </code>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

## Text Formatting

Text formatting tags are used to format text or data of HTML documents. You can do certain things like creating italic, bold, strong text to make your document look more attractive and understandable.

### &lt;b&gt; tag

<div class="code-toolbar">

    <b>I'm bold text</b>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### &lt;strong&gt; tag

<div class="code-toolbar">

    <strong>I'm important text</strong>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### &lt;i&gt; tag

<div class="code-toolbar">

    <i>I'm italic text</i>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### &lt;em&gt; tag

<div class="code-toolbar">

    <em>Emphasized text</em>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### &lt;sub&gt; tag

<div class="code-toolbar">

    <sub>Subscript</sub>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### &lt;sub&gt; tag

<div class="code-toolbar">

    <sup>Superscript</sup>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

## Lists

Lists can be either numerical, alphabetic, bullet, or other symbols. You can specify list type and list items in HTML for the clean document.

### &lt;ol&gt; tag

Ordered list starts with &lt;ol&gt; tag and each list item starts with &lt;li&gt; tag

<div class="code-toolbar">

    <ol>
    <li>Data 1</li>
    <li>Data 2</li>
    <li>Data 3</li>
    </ol>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### &lt;ul&gt; tag

<div class="code-toolbar">

    <ul>
    <li>Your Data</li>
    <li>Your Data</li>
    </ul>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

## Media

Media is anything that is present in digital form such as image, video, audio, etc.

### &lt;audio&gt; tag

It is used to embed sound content in the document.

<div class="code-toolbar">

    <audio controls>
    <source src="demo.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
    </audio>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### &lt;img&gt; tag

It is used to embed or import image in a webpage.

<div class="code-toolbar">

    <img src="Source_of_image" alt="Alternate text">

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### &lt;video&gt; tag

It is used to embed video in the webpage.

<div class="code-toolbar">

    <video width="480" height="320" controls>
    <source src="demo_move.mp4" type="video/mp4">
    Your browser does not support the video tag.
    </video>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

## Table

A table is a collection of rows and columns. It is used to represent data in tabular form.

### Table Structure

<div class="code-toolbar">

    <table>
    <caption>Demo Table</caption>
    <thead>
    <tr>
    <th>Column1</th>
    <th colspan="2">Column2</th>
    </tr>
    </thead>
    <tbody>
    <tr>
    <td>Data1</td>
    <td>Data2</td>
    <td>Data2</td>
    </tr>
    <tr>
    <td>Data1</td>
    <td>Data2</td>
    <td>Data2</td>
    </tr>
    </tbody>
    <tfoot>
    <tr>
    <td>&nbsp;</td>
    <td>Data</td>
    <td>Data</td>
    </tr>
    </tfoot>
    </table>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

## Links

Links are clickable text that can redirect you to some other page.

### &lt;a&gt; tag

&lt;a&gt; or anchor tag defines a hyperlink.

<div class="code-toolbar">

    <a href="https://www.google.com/">Visit Google!</a>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

## Form

### Sample Form

Form is used to collect user's input, generally user's data is sent to server for further processing.

<div class="code-toolbar">

    <form action="/action.php" method="post">
    Name: <input name="name" type="text" /> <br />
    Age: <input max="90" min="1" name="age" step="1" type="number" value="18" /> <br />
    <select name="gender">
    <option selected="selected" value="male">Male</option>
    <option value="female">Female</option>
    </select><br />
    <input checked="checked" name="newsletter" type="radio" value="daily" /> Daily <input name="newsletter"type="radio" value="weekly" /> Weekly<br />
    <textarea cols="20" name="comments"rows="5">Comment</textarea><br />
    <label><input name="terms" type="checkbox" value="tandc" />Accept terms</label> <br />
    <input type="submit" value="Submit" />
    </form>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

## Characters & Symbols

Some symbols are not directly present on the keyboard, but there are some ways to use them in HTML documents. We can display them either by entity name, decimal, or hexadecimal value.

### Copyright Symbol (©)

<div class="code-toolbar">

    &copy;

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### Less than (<)

<div class="code-toolbar">

    &lt;

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### Greater than (>)

<div class="code-toolbar">

    &gt;

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### Ampersand (&)

<div class="code-toolbar">

    &amp;

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### Dollar ($)

<div class="code-toolbar">

    &dollar;

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### Abbreviation element &lt;abbr&gt;&lt;/abbr&gt;
 Abbreviation element that allows you to identify an addreviation in your
 document and provide the text of what that addreviation stants for.
 <p>(So someone who look at your document who may not be fimiliar with it can
 mouse over that Abbreviation and get the full text that it stand for).</p>

<div class="code-toolbar">

    <abbr title = "Hypertext Markup Language">HTML</abbr>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

## Random Text

### Elon Musk

<div class="code-toolbar">

    Elon Reeve Musk FRS is an entrepreneur and business magnate. He is the founder, CEO, and Chief Engineer at SpaceX; early stage investor, CEO, and Product Architect of Tesla, Inc.; founder of The Boring Company; and co-founder of Neuralink and OpenAI. A centibillionaire, Musk is one of the richest people in the world.

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

## Semantic Elements

Semantic elements are those elements that are self describable, i.e., from their name itself, you can understand their meaning.

### &lt;section&gt; tag

It defines a section in the document

<div class="code-toolbar">

    <section>This is a section</section>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### &lt;article&gt; tag

It represents self-contained content

<div class="code-toolbar">

    <article> Enter your data here </article>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

### &lt;aside&gt; tag

It is used to place content in the sidebar

<div class="code-toolbar">

    <aside> Your data </aside>

<div class="toolbar">

<div class="toolbar-item"><button type="button">Copy</button></div>

</div>

</div>

</div>
