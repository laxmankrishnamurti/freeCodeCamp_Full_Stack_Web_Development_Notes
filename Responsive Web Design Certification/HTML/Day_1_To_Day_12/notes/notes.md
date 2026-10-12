# **`KEY TAKEAWAYS`**

- HTML Boilerplate Code
```html
<!DOCTYPE html>
<html lang="en">
      <head>
            <meta charset="UTF-8"/>
            <title>Welcome to home</title>
      </head>
      <body>
            <!-- content of the webpage -->
      </body>
</html>
```
- Heading Tag, Paragraph Tag, Anchor Tag, Image Tag, Figure and Figcaption, section, header, nav, main, footer

```html
<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
<h6></h6>
<p></p>
<a href="#destination_url">
      <!-- text/other html elements -->
</a>
<img src="image_link" alt="alternate text"/>
<figure>
      <img src="image_link" alt="alternate text"/>
      <figcaption>
            Figure 1 : Tajmahal
      </figcaption>
</figure>

<section class="section_1">
      <header>
            <nav>
                  <!-- Navigation Links -->
            </nav>
            <!-- Other Header Contents -->
      </header>
</section>

<section class="section_1">
      <main>
            <!-- contents except header and the footer -->
      </main>
</section>

<section class="section_1">
      <footer>
            <!-- contents except header and the footer -->
      </footer>
</section>

```

- div : Container used to wrap other HTML tags. 
```html
<div>
      <!-- header section -->

      <section class="section_1">
            <header>
                  <nav>
                        <!-- Navigation Links -->
                  </nav>
                  <!-- Other Header Contents -->
            </header>
      </section>

      <!-- main section -->

      <section class="section_1">
            <main>
                  <!-- contents except header and the footer -->
            </main>
      </section>

      <!-- footer section -->

      <section class="section_1">
            <footer>
                  <!-- contents except header and the footer -->
            </footer>
      </section>
</div>
```

- ID  : Unique Identifier - We should avoid to add a whitespace in an ID. Mostly used for JavaScript.
- Classes   :     It is also a way to identify HTML tags used for mainly CSS purpose. A single html element can have multiple classes. 

```html
<button id="sign_up_btn" class="btn">Sign Up</button>
```

- &lt<tag_name>&gt;     :     Reserved Keyword in HTML.
- <script src="file_relative_path"></script> :  This is the SCRIPT tag used to link a JavaScript file into HTML document. 

```html
<script src="file_relative_path"></script>
```

- Meta Description that affects SEO

```html
<!DOCTYPE html>
<html lang="en">
      <head>
            <meta charset="UTF-8"/>
            <title>Welcome to home</title>

            <!-- meta tag that affects SEO -->

            <meta
                  name="description"
                  content="Discover expert tips and techniques for gardening in small spaces, choosing the right plants, and maintaining a thriving garden."
            />

            <!-- Open Graph Tags -->

            <meta content="freeCodeCamp.org" property="og:title" />
            <meta property="og:type" content="website" />
            <meta
                  content="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png"
                  property="og:image"
            />
            <meta property="og:url" content="https://www.freecodecamp.org" />

      </head>
      <body>
            <!-- content of the webpage -->
      </body>
</html>
```

- Lists

```html
<!-- Unordered Lists -->

<ul>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
</ul>

<!-- Ordered Lists -->

<ol>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
</ol>
```