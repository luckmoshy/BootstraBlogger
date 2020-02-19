<!doctype html>
<html lang="en">
  <head>
    <style>
    .s {
    color: 
    #d44950!mportant;
}
.na {
    color: 
    #4f9fcf!mportant;
}
      .nt {
    color: 
    #2f6f9f!mportant;
}
      .s {
    color: 
    #d44950!mportant;
}
      .na {
    color: 
    #4f9fcf!mportant;
}
    </style>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>

<div class="container">
<main class="col-12 col-md-9 col-xl-8 py-md-3 pl-md-5 order-2 bd-content" role="main">
          <h1 class="bd-title" id="content">Overview</h1>
          <p class="bd-lead">Kiolezo cha msingi cha bootblogger kimeundwa kutoa urahisi kwa kugeuza sifa mbadala za Blogger na kuongeza huduma mpya

.</p>
          <h2 id="blogger-version"><div>Blogger version<a class="anchorjs-link " href="#blogger-version" aria-label="Anchor link for: blogger version" data-anchorjs-icon="#" style="padding-left: 0.375em;"></a></div></h2>

<p>Tumia toleo templeti 

 <code class="highlighter-rouge">3</code>:</p>

<div class="bd-clipboard"><button class="btn-clipboard" title="" data-original-title="Copy to clipboard">Copy</button></div><figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;html</span> <span class="na">b:layoutsVersion=</span><span class="s">'3'</span><span class="nt">&gt;</span>...<span class="nt">&lt;/html&gt;</span></code></pre></figure>

<p>Kutumia toleo la gadget <code class="highlighter-rouge">2</code>:</p>

<div class="bd-clipboard"><button class="btn-clipboard" title="" data-original-title="Copy to clipboard">Copy</button></div><figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;html</span> <span class="na">b:defaultwidgetversion=</span><span class="s">'2'</span><span class="nt">&gt;</span>...<span class="nt">&lt;/html&gt;</span></code></pre></figure>

<div class="bd-clipboard"><button class="btn-clipboard" title="" data-original-title="Copy to clipboard">Copy</button></div><figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;b:widget</span> <span class="na">version=</span><span class="s">'2'</span><span class="nt">&gt;</span>...<span class="nt">&lt;/b:widget&gt;</span></code></pre></figure>

<h2 id="page-types"><div>Page types<a class="anchorjs-link " href="#page-types" aria-label="Anchor link for: page types" data-anchorjs-icon="#" style="padding-left: 0.375em;"></a></div></h2>

<p>Unaweza kuweka muonekano wa blogi, machapisho ya kuonyesha, madarasa, na wengine kuwa tofauti katika kila aina ya ukurasa.</p>

<p>Chini ni uteuzi wa aina za kurasa za kutumia

<code class="highlighter-rouge">data:view</code>.</p>

<div class="bd-clipboard"><button class="btn-clipboard" title="" data-original-title="Copy to clipboard">Copy</button></div><figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;b:comment&gt;</span>=== Homepage ===<span class="nt">&lt;/b:comment&gt;</span>
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

<h2 id="body-class"><div>Body class<a class="anchorjs-link " href="#body-class" aria-label="Anchor link for: body class" data-anchorjs-icon="#" style="padding-left: 0.375em;"></a></div></h2>

<p>Kwenye lebo ya HTML ya mwili, kuna madarasa tofauti katika kila aina ya ukurasa.

</p>

<p>Chini ya hii ndio jina la darasa la kila aina ya ukurasa.

</p>

<div class="bd-clipboard"><button class="btn-clipboard" title="" data-original-title="Copy to clipboard">Copy</button></div><figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;body&gt;</span>
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

<div class="bd-clipboard"><button class="btn-clipboard" title="" data-original-title="Copy to clipboard">Copy</button></div><figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="c">&lt;!-- Homepage --&gt;</span>
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

<p>Mfano wa matumizi

:</p>

<div class="bd-clipboard"><button class="btn-clipboard" title="" data-original-title="Copy to clipboard">Copy</button></div><figure class="highlight"><pre><code class="language-css" data-lang="css"><span class="nc">.blog-view-item</span> <span class="p">{</span>
  <span class="err">...</span>
<span class="p">}</span>



  </div>
        </main>
        </div>
        
        
