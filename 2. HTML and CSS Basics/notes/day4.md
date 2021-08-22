## Comments ## 
```
<!-- This is how we write comments in HTML. -->
```
## Tags in HTML ## 
HTML tags tells browser, how to behave and render text in the UI.
1. <title>Renders Title of Page</title>
2. <body>Where content of page is written</body>
3. <p>Paragraph tag</p>
4. <pre>Paragraph tag</pre>
5. <br/> Breaks line tag
6. <h1>Heading tag</h1>
7. <div>Block tag, creating division</div>
8. <a>Anchor tag to work with links</a>
9. <img src="" alt=""/> Image tag to put image in the page
10. <button>Button tag to work with button</button>

> ## Inline vs Block Tag ## 
- In Inline next content starts from same line. Example: span, a, em, strong etc.
- In Block next content starts from new line. Example: div, p, h1, h2, h3, h4, h5, h6, section,    article, aside, nav, footer, header, main, aside, nav, footer, header, main
```
Block Tag🥇: 

<h1>Hey</h1>
<p>There</p>
<p>Taslim</p>

Output: 
Hey
There
Taslim

Inline Tag🥇: 

<span>Hey there</span>
<a href=""> This is good</>

Output: 
Hey there This is good
```
--- 
<form>Form tag</form> tag is used to create forms to take input from users.
- method : method attribute is used to tell browser what type of form is it. (POST, GET etc.)

<table></table> tag is used to create tables.
- border : border attribute is used to set border of table.
- <tr> : table row tag
- <td> : table data tag
- <th> : table heading tag
- <tbody> : table body tag 

| **Hostname**       | **IP address IPv4 / IPv6**      | **Organization**                        |
| ------------------ | ------------------------------- | --------------------------------------- |
| a.root-servers.net | 198.41.0.4, 2001:503:ba3e::2:30 | VeriSign, Inc.                          |
| b.root-servers.net | 199.9.14.201, 2001:500:200::b   | University of Southern California (ISI) |

```
<thead>
    <tr>
        <th>Hostname</th>
        <th>IP address IPv4 / IPv6</th>
        <th>Organization</th>
    </tr>
</thead>

<tbody>
    <tr>
        <td>a.root-servers.net</td>
        <td>198.41.0.4, 2001:503:ba3e::2:30</td>
        <td>VeriSign, Inc.</td>
    </tr>
    <tr>
        <td>b.root-servers.net</td>
        <td>199.9.14.201, 2001:500:200::b</td>
        <td>University of Southern California (ISI)</td>
    </tr>
</tbody>
```

> ## List ## 
1. <ul>Unordered List</ul>
2. <ol start=1>Ordered List</ol>
```
<ul>
  <li>x</li>
  <li>y</li>
  <li>z</li>
</ul>

<ol start=1>
  <li>x</li>
  <li>y</li>
  <li>z</li>
</ol>
```
