---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<!-- Intro -->
  <div id="intro">
    <h1>To je<br />
    Gajina vadnica</h1>
    <p>Dobrodošli v Gajin svet programiranja, <br />
    kjer vas čakajo zabavne lekcije digitalne pismenosti.</p>
    <ul class="actions">
      <li><a href="#header" class="button icon solo fa-arrow-down scrolly">Nadaljuj</a></li>
    </ul>
  </div>

<!-- Header -->
  <header id="header">
    <a href="index.html" class="logo">Gajin svet programiranja</a>
  </header>

<!-- Nav -->
  <nav id="nav">
    <ul class="links">
      <li class="active"><a href="index.html">Gajina vadnica</a></li>
      <li><a href="gajin-svet.html">Gajin svet</a></li>
    </ul>
    <ul class="icons">
      <li><a href="https://www.facebook.com/codeweek.si/" class="icon fa-facebook"><span class="label">Facebook</span></a></li>
      <li><a href="mailto:info@codeweek.si" class="icon fa-envelope"><span class="label">Email</span></a></li>
    </ul>
  </nav>

<!-- Main -->
  <div id="main">

    <!-- Featured Post -->
    {% include partial_featured_post.html %}

    <!-- Posts -->
    <section class="posts">
    {% include partial_posts.html %}
    </section>
  </div>