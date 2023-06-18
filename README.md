# Exp04-webdev
# Gridbox 
develop a  Gridbox using CSS.
## Algorithm:
1. Code all the necessary Css elements.
2. And connect it with the HTML page.
3. Then execute it.
4. Display the results.
## Code:
```
 <!doctype html>
<title>Example</title>
<style>
body { 
  display: grid;
  grid-template-areas: 
    "header header header"
    "nav article ads"
    "footer footer footer";
  grid-template-rows: 60px 1fr 60px;
  grid-template-columns: 20% 1fr 15%;
  grid-gap: 10px;
  height: 100vh;
  margin: 0;
  }
header, footer, article, nav, div {
  padding: 20px;
  background: rgb(59, 226, 92);
}
#pageHeader {
  grid-area: header;
}
#pageFooter {
  grid-area: footer;
}
#mainArticle { 
  grid-area: article;      
  }
#mainNav { 
  grid-area: nav; 
  }
#siteAds { 
  grid-area: ads; 
  }
</style>
<body>
  <header id="pageHeader">Header</header>
  <article id="mainArticle">Article</article>
  <nav id="mainNav">Nav</nav>
  <div id="siteAds">Ads</div>
  <footer id="pageFooter">Footer</footer>
</body>

```
## Output:
![image](https://github.com/Archana2003-Jkumar/Exp04-webdev/assets/93427594/58863a64-cbe0-4496-9c36-4de14d5cda0c)
## Result:
Thus the code has been implemented successfully.
