<template>
 <div id="app">
 <div class="container">
 <header class="blog-header py-3">
 <div class="row flex-nowrap justify-content-between align-items-center ">
 <div class="col-4 pt-1">
 <a class="text-muted" href="content">content</a>
 </div>
 <div class="col-4 d-flex justify-content-end align-items-center">
 <a class="btn btn-sm btn-outline-secondary button4" href="signin">Sign 
in</a>
 </div>
 </div>
 </header>
 <div class="nav-scroller py-1 mb-2">
 <nav class="nav d-flex justify-content-between">
 <a class="p-2 text-muted" href="#">Technology</a>
 <a class="p-2 text-muted" href="#">Business</a>
 <a class="p-2 text-muted" href="#">Politics</a>
 <a class="p-2 text-muted" href="#">Science</a>
 </nav>
 </div>
 <div class="row mb-2">
 <div class="col-md-6">
 <div class="row no-gutters border rounded overflow-hidden flex-md-row mb-4 
shadow-sm h-md-250 position-relative">
 <div class="col p-4 d-flex flex-column position-static">
 <strong class="d-inline-block mb-2 text-primary">Politics</strong>
 <h3 class="mb-0">Biden/Trump </h3>
 <div class="mb-1 text-muted">Nov 12</div>
 <p class="card-text mb-auto"> info </p>
 <a href="#" class="stretched-link">Continue reading</a>
 </div>
 </div>
 </div>
 </div>
 </div>
 <main role="main" class="container">
 <router-view/>
 <div class="row">
 <div class="col-md-8 blog-main">
 <h3 class="pb-4 mb-4 font-italic border-bottom">
 News feed
 </h3>
 <div class="blog-post">
 <h2 class="blog-post-title">Sample blog post</h2>
 <p class="blog-post-meta">January 1, 2014 by <a href="#">Mark</a></p>
 <p><strong>Китай </strong> начал скупать нефть и газ</p>
 <hr>
 <p>Китай начал скупать нефть и газ на фоне резкого обрушения цен на
энергоносители</p>
 </div><!-- /.blog-post -->
 <div class="blog-post">
 <h2 class="blog-post-title">post1</h2>
 <p class="blog-post-meta">December 23, 2013 by <a href="#">Jacob</a></p>
 <p> <em>Мошенники придумали новый способ кражи денег с банковских карт
россиян</em> </p>
 </div><!-- /.blog-post -->
 <div class="blog-post">
 <h2 class="blog-post-title">post2</h2>
 <p class="blog-post-meta">November 7, 2020 by <a href="#">Chris</a></p>
 <p>За последние сутки в России выявили 20 396 новых случаев заболевания
коронавирусной инфекцией COVID-19</p>
 </div><!-- /.blog-post -->
 </div><!-- /.blog-main -->
 </div><!-- /.row -->
 </main><!-- /.container -->
 </div>
</template>