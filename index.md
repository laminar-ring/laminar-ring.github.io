

 


<!DOCTYPE html>

<html>
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
    <meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0" name="viewport" />

    
  



  




  


<title>Blog — Development Seed</title>
<meta name="description" content="The latest blog posts about our work." />

<!-- Twiter Cards -->
<meta name="twitter:card" content="summary" />
<meta name="twitter:site" content="@developmentseed" />
<meta name="twitter:title" content="Blog — Development Seed">
<meta name="twitter:description" content="The latest blog posts about our work." />
<meta name="twitter:image:src" content="https://developmentseed.org/assets/graphics/meta/default-meta-image.png" />


  


<!--/ Twiter Cards -->

<!-- Open Graph -->
<meta property="og:site_name" content="Development Seed" />
<meta property="og:type" content="website" />
<meta property="og:title" content="Blog — Development Seed" />
<meta property="og:url" content="https://developmentseed.org/blog/" />
<meta property="og:description" content="The latest blog posts about our work." />
<meta property="og:image" content="https://developmentseed.org/assets/graphics/meta/default-meta-image.png" />
<!--/ Open Graph -->

    <link rel="shortcut icon" href="https://developmentseed.org/assets/graphics/meta/favicon.ico" type="image/x-icon" />
    <link rel="apple-touch-icon" href="https://developmentseed.org/assets/graphics/meta/apple-touch-icon.png" />
    <link rel="apple-touch-icon" sizes="57x57" href="https://developmentseed.org/assets/graphics/meta/apple-touch-icon-57x57.png" />
    <link rel="apple-touch-icon" sizes="72x72" href="https://developmentseed.org/assets/graphics/meta/apple-touch-icon-72x72.png" />
    <link rel="apple-touch-icon" sizes="76x76" href="https://developmentseed.org/assets/graphics/meta/apple-touch-icon-76x76.png" />
    <link rel="apple-touch-icon" sizes="114x114" href="https://developmentseed.org/assets/graphics/meta/apple-touch-icon-114x114.png" />
    <link rel="apple-touch-icon" sizes="120x120" href="https://developmentseed.org/assets/graphics/meta/apple-touch-icon-120x120.png" />
    <link rel="apple-touch-icon" sizes="144x144" href="https://developmentseed.org/assets/graphics/meta/apple-touch-icon-144x144.png" />
    <link rel="apple-touch-icon" sizes="152x152" href="https://developmentseed.org/assets/graphics/meta/apple-touch-icon-152x152.png" />

    <link rel="stylesheet" href="//fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,700italic,400,300,700" type="text/css" />

    <link rel="stylesheet" href="https://developmentseed.org/assets/styles/main.css" type="text/css" />
    <link rel="alternate" href="https://developmentseed.org/rss.xml" type="application/rss+xml" />
    <link rel="author" href="https://developmentseed.org/humans.txt" type="text/plain" />

    <script>
      var DSO = window.DSO = {}; DSO.baseUrl = 'https://developmentseed.org';
    </script>

    <script src="https://developmentseed.org/assets/scripts/deps.min.js" type="text/javascript"></script>
    <script src="https://developmentseed.org/assets/scripts/templates.js" type="text/javascript"></script>
    <script src="https://developmentseed.org/assets/scripts/main.min.js" type="text/javascript"></script>

  </head>
  
    
  

  
  <body class="theme-pos">
  
    <div id="site-canvas">

      <header id="site-header" role="banner">
        <div class="row inner-row">
          <h1 id="site-title">
            <a href="/" title="Development Seed">
              
              <img src="/assets/graphics/layout/ds-logo-pos.svg" alt="Development Seed logotype" width="188" height="32" />
              
              <span>Development Seed</span>
            </a>
          </h1>
          <nav id="site-prime-nav" role="navigation" class="drop">
            <h2 class="toggle-menu"><a href="#global-menu" title="Show menu" data-toggle="drop"><span>Browse</span></a></h2>
            <div class="menu-wrapper">
              <ul class="global-menu" id="global-menu">
                <li class="">
                  <a href="/projects" title="View the projects"><span>Projects</span></a>
                </li>
                <li class="active">
                  <a href="/blog" title="View the blog"><span>Blog</span></a>
                </li>
                <li class="">
                  <a href="/team" title="View the team"><span>Team</span></a>
                </li>
                <li class="">
                  <a href="/careers/jobs" title="Join the team"><span>Careers</span></a>
                </li>
                <li class="">
                  <a href="/about" title="Read about us"><span>About</span></a>
                </li>
                <li class="">
                  <a href="/contacts" title="Get in touch"><span>Contacts</span></a>
                </li>
                <li class="search"><a href="#search" title="Search content" data-search-open><span>Search</span></a></li>
              </ul>
            </div>
          </nav>
        </div>
      </header>

      <main id="site-body" role="main">
        

<script>
  $(document).ready(function() {
    new DSO.Views.BlogList({container: $('[data-view-blog-list]'), filtersContainer: $('[data-view-blog-filters]')});
  });
</script>
<section id="blog" class="page hub">
  <header class="page-header">
    <div class="page-header-inner">
      <div class="page-headline">
        <h1 class="page-title">Blog</h1>
      </div>
      
    </div>
    

    <nav class="page-nav">
      <div class="page-nav-inner" data-view-blog-filters>
        <!-- Content via javascript: See blog-filters.ejs -->
      </div>
    </nav>
  </header>
  <div data-view-blog-list>
    <!-- Content via javascript: See card-list.ejs -->
  </div>
</section>

        
        <section class="fold fold--dark fold--cta">
  <div class="inner">
    <div class="fold__body">
      <div class="fold__prose prose">
        <p>We're a team of engineers and designers working on big projects. We believe in open source and in building for lasting impact.</p>
        <p class="btn-wrapper"><a class="bttn-more" href="https://developmentseed.org/careers/jobs/" title="Learn more"><span>Learn more</span></a></p>
      </div>
    </div>
  </div>
</section>

        
        <section id="site-search" data-search-container><!-- Search via javascript --></section>
      </main>

      <footer id="site-footer" role="contentinfo">
        <div class="row inner-row">
          <nav id="site-elsewhere-nav" role="navigation">
            <h2 class="hd-suptitle">Let's connect</h2>
            <ul class="connect-menu">
              <li class="feed"><a href="/rss.xml" title="Subscribe to our RSS feed"><span>RSS feed</span></a></li>
              <li class="twitter"><a href="https://twitter.com/developmentseed" title="Follow us on Twitter"><span>Twitter</span></a></li>
              <li class="github"><a href="https://github.com/developmentseed" title="Follow us on GitHub"><span>GitHub</span></a></li>
              <li class="flickr"><a href="https://www.flickr.com/photos/developmentseed/" title="Follow us on Flickr"><span>Flickr</span></a></li>
            </ul>
          </nav>
          <p class="credits">Development Seed • 2003-2018</p>
        </div>
      </footer>

    </div>
  <!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-65674-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-65674-1');
</script>

  </body>

</html>
