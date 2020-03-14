## Bootstrablogger Ui and Xml
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
(https://luckmoshy.github.io/bootstrablogger/) .

BootstraBlogger gives you a full solution for all your Blogger Portfolio,Landing and E-commerce product catalogs make up your design workflow with ready-to-use beautifully designed sample blogger components for your daily projects. 
### Bootstrablogger

The main purpose of this Booststrablogger Components (Css Framework) is to give a full solution to designers and developers in the categories of all type of blogger Themes, online marketplaces, Portfolio platforms and product landing blogger. This kit provides multiple combinations of examples and sample section and widgets for you to work on including numerous components and element styles. 

<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;b:comment&gt;</span>=== Homepage ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isHomepage'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Item page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isPost'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com/&lt;year&gt;/&lt;month&gt;/&lt;permalink&gt;.html --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Static page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isPage'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com/p/&lt;permalink&gt;.html --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Search (label) page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.search.label'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com/search/label/&lt;name&gt; --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Search (query) page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.search.query'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com/search?q=&lt;query&gt; --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Search (default) page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.search and !data:view.search.label and !data:view.search.query'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com/search --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Archive page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isArchive'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- 1. https://example.blogspot.com/&lt;year&gt; --&gt;</span>
  <span class="c">&lt;!-- 2. https://example.blogspot.com/&lt;year&gt;/&lt;month&gt; --&gt;</span>
  <span class="c">&lt;!-- 3. https://example.blogspot.com/&lt;year&gt;_&lt;month&gt;_&lt;day&gt;_archive.html --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Error page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isError'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com/404 --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Preview page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isPreview'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- Preview page --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Layout mode ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isLayoutMode'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://www.blogger.com/blogger.g?blogID=&lt;blogID&gt;#pageelements --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span></code></pre></figure>
<br/>
<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;body&gt;</span>
  <span class="nt">&lt;b:class</span> <span class="na">cond=</span><span class="s">'data:view.isHomepage'</span> <span class="na">name=</span><span class="s">'blog-view-home'</span><span class="nt">/&gt;</span>
  <span class="nt">&lt;b:class</span> <span class="na">cond=</span><span class="s">'data:view.isPost'</span> <span class="na">name=</span><span class="s">'blog-view-item'</span><span class="nt">/&gt;</span>
  <span class="nt">&lt;b:class</span> <span class="na">cond=</span><span class="s">'data:view.isPage'</span> <span class="na">name=</span><span class="s">'blog-view-static'</span><span class="nt">/&gt;</span>
  <span class="nt">&lt;b:class</span> <span class="na">cond=</span><span class="s">'data:view.search.label'</span> <span class="na">name=</span><span class="s">'blog-view-search-label'</span><span class="nt">/&gt;</span>
  <span class="nt">&lt;b:class</span> <span class="na">cond=</span><span class="s">'data:view.search.query'</span> <span class="na">name=</span><span class="s">'blog-view-search-query'</span><span class="nt">/&gt;</span>
  <span class="nt">&lt;b:class</span> <span class="na">cond=</span><span class="s">'data:view.search and !data:view.search.label and !data:view.search.query'</span> <span class="na">name=</span><span class="s">'blog-view-search-default'</span><span class="nt">/&gt;</span>
  <span class="nt">&lt;b:class</span> <span class="na">cond=</span><span class="s">'data:view.isArchive'</span> <span class="na">name=</span><span class="s">'blog-view-archive'</span><span class="nt">/&gt;</span>
  <span class="nt">&lt;b:class</span> <span class="na">cond=</span><span class="s">'data:view.isError'</span> <span class="na">name=</span><span class="s">'blog-view-error'</span><span class="nt">/&gt;</span>
  <span class="nt">&lt;b:class</span> <span class="na">cond=</span><span class="s">'data:view.isPreview'</span> <span class="na">name=</span><span class="s">'blog-view-preview'</span><span class="nt">/&gt;</span>
<span class="nt">&lt;/body&gt;</span></code></pre></figure>
<br/>
<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="c">&lt;!-- Homepage --&gt;</span>
<span class="nt">&lt;body</span> <span class="na">class=</span><span class="s">"blog-view-home"</span><span class="nt">&gt;</span>...<span class="nt">&lt;/body&gt;</span>

<span class="c">&lt;!-- Item page --&gt;</span>
<span class="nt">&lt;body</span> <span class="na">class=</span><span class="s">"blog-view-item"</span><span class="nt">&gt;</span>...<span class="nt">&lt;/body&gt;</span>

<span class="c">&lt;!-- Static page --&gt;</span>
<span class="nt">&lt;body</span> <span class="na">class=</span><span class="s">"blog-view-static"</span><span class="nt">&gt;</span>...<span class="nt">&lt;/body&gt;</span>

<span class="c">&lt;!-- Search (label) page --&gt;</span>
<span class="nt">&lt;body</span> <span class="na">class=</span><span class="s">"blog-view-search-label"</span><span class="nt">&gt;</span>...<span class="nt">&lt;/body&gt;</span>

<span class="c">&lt;!-- Search (query) page --&gt;</span>
<span class="nt">&lt;body</span> <span class="na">class=</span><span class="s">"blog-view-search-query"</span><span class="nt">&gt;</span>...<span class="nt">&lt;/body&gt;</span>

<span class="c">&lt;!-- Search (default) page --&gt;</span>
<span class="nt">&lt;body</span> <span class="na">class=</span><span class="s">"blog-view-search-default"</span><span class="nt">&gt;</span>...<span class="nt">&lt;/body&gt;</span>

<span class="c">&lt;!-- Archive page --&gt;</span>
<span class="nt">&lt;body</span> <span class="na">class=</span><span class="s">"blog-view-archive"</span><span class="nt">&gt;</span>...<span class="nt">&lt;/body&gt;</span>

<span class="c">&lt;!-- Error page --&gt;</span>
<span class="nt">&lt;body</span> <span class="na">class=</span><span class="s">"blog-view-error"</span><span class="nt">&gt;</span>...<span class="nt">&lt;/body&gt;</span>

<span class="c">&lt;!-- Preview page --&gt;</span>
<span class="nt">&lt;body</span> <span class="na">class=</span><span class="s">"blog-view-preview"</span><span class="nt">&gt;</span>...<span class="nt">&lt;/body&gt;</span></code></pre></figure>
For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### 



### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
