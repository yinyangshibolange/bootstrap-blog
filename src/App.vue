<template>
  <div id="app">
    <b-container fluid>
      <b-row>
        <b-col cols="12" md="3" class="header">
          <header>
            <h1 class="font-weight-bold">A SAMPLE BLOG</h1>
            <h2>Creating a blog layout using Bootstrap</h2>
            <button type="button" class="btn btn-outline-primary" style="color: #fff; border-color: #B0CADB;">Primary</button>
            <button type="button" class="btn btn-outline-primary ml-3" style="color: #fff; border-color: #B0CADB;">Primary</button>
          </header>
        </b-col>
        <b-col cols="12" md="9">
          <div class="content">
            <div class="posts">
              <h1 class="content-subhead">PINNED POST</h1>
              <section>
                <header>
                  <h2 class="font-weight-bold mb-1 mt-4">Introducing Pure</h2>
                  <p class="text-muted">
                    <small>
                      By
                      <a href="#">Tilo Mitra</a>
                      under
                      <a href="#" class="tag bg-success text-white">css</a>
                      <a href="#" class="tag bg-primary text-white">bootstrap</a>
                    </small>
                  </p>
                </header>
                <div class="post-description">
                  <p>
                    Yesterday at CSSConf, we launched Pure – a new CSS library. Phew! Here are the slides from the presentation. Although it looks pretty minimalist, we’ve been working on Pure for several months. After many iterations, we have released Pure as a set of small, responsive, CSS modules that you can use in every web project.
                  </p>
                </div>
              </section>
            </div>
            <div class="posts">
              <h1 class="content-subhead">RECENT POSTS</h1>
              <section>
                <header>
                  <h2 class="font-weight-bold mb-1 mt-4">Everything You Need to Know About Grunt</h2>
                  <p class="text-muted">
                    <small>
                      By
                      <a href="#">Eric Ferraiuolo</a>
                      under
                      <a href="#" class="tag bg-success text-white">JavaScript</a>
                    </small>
                  </p>
                </header>
                <div class="post-description">
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
                  </p>
                </div>
              </section>

              <section>
                <header>
                  <h2 class="font-weight-bold mb-1 mt-4">YUI 3.10.2 Released</h2>
                  <p class="text-muted">
                    <small>
                      By
                      <a href="#">Andrew Wooldridge</a>
                      under
                      <a href="#" class="tag bg-success text-white">YUI</a>
                    </small>
                  </p>
                </header>
                <div class="post-description">
                  <p>
                    We are happy to announce the release of YUI 3.10.2! You can find it now on the Yahoo! CDN, download it directly, or pull it in via npm. We’ve also updated the YUI Library website with the latest documentation.
                  </p>
                </div>
              </section>
            </div>
            <div class="footer text-center">
              <div class="mt-5">
                <ul class="highlighter-rouge clearfix">
                  <li class="d-inline-block"><a href="#" class="text-muted text-decoration-none"><small>About</small></a></li>
                  <li class="d-inline-block ml-4"><a href="#" class="text-muted text-decoration-none"><small>Twitter</small></a></li>
                  <li class="d-inline-block ml-4"><a href="#" class="text-muted text-decoration-none"><small>Github</small></a></li>
                </ul>
              </div>
            </div>
          </div>
        </b-col>

      </b-row>
    </b-container>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
@import "assets/css/index.css";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  //text-align: center;
}
</style>
