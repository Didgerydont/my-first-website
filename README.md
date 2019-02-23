# _My First Website_
The goal of this project is to create a website that contains three pages, each containing logo's of different programming languages with hyperlinks to their corresponding Wiki pages. 
### Give a look...
The site is published @ https://didgerydont.github.io/my-first-website/ 

### *Files list*
* style.css
* index.html
* stream-two.html
* stream-three.html

### Snippets of the code used

<div class="card">
			<a href="https://en.wikipedia.org/wiki/Python_(programming_language)" />
			<img src="https://upload.wikimedia.org/wikipedia/commons/f/f8/Python_logo_and_wordmark.svg?download" />
			<h2>Python</h2>
			</a>
		</div>

#### *The nav bar*


		<ul>
			<li><a href="index.html">Stream One</a></li>
			<li><a href="stream-two.html">Stream Two</a></li>
			<li><a href="stream-three.html">Stream Three</a></li>
		</ul>

#### *Hyperlinked inline blocks*

			<a href="https://en.wikipedia.org/wiki/Python_(programming_language)" />
			<img src="https://upload.wikimedia.org/wikipedia/commons/f/f8/Python_logo_and_wordmark.svg?download" />
			<h2>Python</h2>
			</a>
			
#### *CSS*

nav ul{

    list-style: none;
    background-color: #4a4a4f;
    text-align: center;
    margin: 0;
    padding: 0;
}

nav li{

    font-size: 1.2em;
    line-height: 40px;
    height: 40px;
    display: inline-block;
    margin-left: 2.5%;

    
}

nav a{

    text-decoration: none;
    color: #ffffff;
    display: block;
}

nav a:hover{

    background-color: #ffffff;
    color: #4a4a4f;
}

.row{

    display: inline-block;
}

### Sources

* `wikipedia.com`
* `https://www.google.com/imghp?hl=EN`
* `Code Institute`

