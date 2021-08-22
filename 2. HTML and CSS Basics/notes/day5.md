# Modern HTML 5 Tags # 
This is how we should divide our page in HTML.
![Structure of HTML Page](../image/html5_tags.png)

- <Header>Tag for showing header content</Header>
- <nav>These are like <li> of list, generally used inside **Header** to render list of elements/links </nav>
- <article>Tag for page main content</article>
- <section> Generally used inside article tag to divide our content in various sections logically. </section>
- <aside>Tag for page side content</aside>
- <footer>Tag for page footer content</footer>

Using the above tags we can divide our page in various sections and it is very easy for us to create and manage a page. It is also very convenient for a browser to understand this code.

```
 <body>
    <!-- Header of page -->
    <header>
      <nav><a href="#">Home</a></nav>
      <nav><a href="#">Product</a></nav>
      <nav><a href="#">Docs</a></nav>
      <nav><a href="#">About us</a></nav>
    </header>

    <!-- Main content of page -->
    <article>
      <section>First section</section>
      <section>Second section</section>
      <section>Third section</section>
      <section>Fourth section</section>
    </article>

    <!-- Side bar of page -->
    <aside>This is side bar content</aside>

    <!-- Footer of page -->
    <footer>
      <section>Footer section 1</section>
      <section>Footer section 2</section>
      <section>Footer section 3</section>
    </footer>
  </body>
```