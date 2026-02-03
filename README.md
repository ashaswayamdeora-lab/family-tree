
&lt;!DOCTYPE html&gt;
&lt;html lang=&quot;en&quot;&gt;
&lt;head&gt;
&lt;meta charset=&quot;UTF-8&quot;&gt;
&lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1.0&quot;&gt;
&lt;title&gt;Family Tree - All Visible&lt;/title&gt;
&lt;style&gt;
body {
font-family: &#39;Segoe UI&#39;, Arial, sans-serif;
background-color: #f8f9fa;
text-align: center;
padding: 20px;
}

h1 { color: #2c3e50; }

/* The Tree Container */
.tree ul {
padding-top: 20px;
position: relative;
display: flex;
justify-content: center;
list-style-type: none;
padding-left: 0;
}

.tree li {
float: left; text-align: center;
list-style-type: none;
position: relative;
padding: 20px 10px 0 10px;
}

/* Connecting Lines (Horizontal) */
.tree li::before, .tree li::after {
content: &#39;&#39;;
position: absolute; top: 0; right: 50%;
border-top: 2px solid #adb5bd;
width: 50%; height: 20px;
}
.tree li::after {
right: auto; left: 50%;
border-left: 2px solid #adb5bd;
}

/* Remove lines for single children or edges */
.tree li:only-child::after, .tree li:only-child::before { display: none; }
.tree li:only-child { padding-top: 0; }
.tree li:first-child::before, .tree li:last-child::after { border: 0 none; }
.tree li:last-child::before { border-right: 2px solid #adb5bd; border-radius: 0 5px 0 0; }
.tree li:first-child::after { border-radius: 5px 0 0 0; }

/* Vertical Connector to Parents */
.tree ul ul::before {
content: &#39;&#39;;
position: absolute; top: 0; left: 50%;
border-left: 2px solid #adb5bd;
width: 0; height: 20px;
}

/* The Person Card/Tile */
.person {
background: white;
border: 2px solid #457b9d;
border-radius: 8px;
padding: 15px;
display: inline-block;
min-width: 140px;
box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.person img {
width: 70px;
height: 70px;
border-radius: 50%;
object-fit: cover;
border: 3px solid #e9ecef;
margin-bottom: 10px;

}

.person span {
display: block;
font-weight: bold;
color: #1d3557;
}

.person small {
display: block;
color: #6c757d;
font-size: 0.8em;
margin-top: 5px;
}
&lt;/style&gt;
&lt;/head&gt;
&lt;body&gt;

&lt;h1&gt;Our Family Tree&lt;/h1&gt;

&lt;div class=&quot;tree&quot;&gt;
&lt;ul&gt;
&lt;li&gt;
&lt;div class=&quot;person&quot;&gt;
&lt;img src=&quot;C:\Users\ankit\OneDrive\Desktop\person.png&quot; alt=&quot;Grandpa&quot;&gt;
&lt;span&gt;Grandfather&lt;/span&gt;

&lt;small&gt;1945 - 2010&lt;/small&gt;
&lt;/div&gt;

&lt;ul&gt;
&lt;li&gt;
&lt;div class=&quot;person&quot;&gt;
&lt;img src=&quot;C:\Users\ankit\OneDrive\Desktop\person.png&quot; alt=&quot;Father&quot;&gt;
&lt;span&gt;Father&lt;/span&gt;
&lt;small&gt;Engineer&lt;/small&gt;
&lt;/div&gt;
&lt;ul&gt;
&lt;li&gt;
&lt;div class=&quot;person&quot;&gt;
&lt;img src=&quot;C:\Users\ankit\OneDrive\Desktop\person.png&quot; alt=&quot;Me&quot;&gt;
&lt;span&gt;Me (Student)&lt;/span&gt;
&lt;/div&gt;
&lt;/li&gt;
&lt;li&gt;
&lt;div class=&quot;person&quot;&gt;
&lt;img src=&quot;C:\Users\ankit\OneDrive\Desktop\person.png&quot; alt=&quot;Sister&quot;&gt;
&lt;span&gt;Sister&lt;/span&gt;
&lt;/div&gt;
&lt;/li&gt;
&lt;/ul&gt;
&lt;/li&gt;

&lt;li&gt;
&lt;div class=&quot;person&quot;&gt;
&lt;img src=&quot;C:\Users\ankit\OneDrive\Desktop\person.png&quot; alt=&quot;Uncle&quot;&gt;
&lt;span&gt;Uncle&lt;/span&gt;
&lt;small&gt;Chef&lt;/small&gt;
&lt;/div&gt;
&lt;ul&gt;
&lt;li&gt;
&lt;div class=&quot;person&quot;&gt;
&lt;img src=&quot;C:\Users\ankit\OneDrive\Desktop\person.png&quot; alt=&quot;Cousin&quot;&gt;
&lt;span&gt;Cousin &lt;/span&gt;
&lt;/div&gt;
&lt;/li&gt;
&lt;/ul&gt;
&lt;/li&gt;
&lt;/ul&gt;
&lt;/li&gt;
&lt;/ul&gt;
&lt;/div&gt;

&lt;/body&gt;
&lt;/html&gt;
