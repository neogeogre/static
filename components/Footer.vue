<template>
  <footer>
    <div class="container-fluid">
      <div class="row middle-xs">
        <div class="col-xs-4 center-xs middle-xs">
          <div class="box">
            <!-- Update your Site -->
            <span class="copyright-text">&#169; nuxt static skeleton</span>
          </div>
        </div>
        <div class="col-xs-4 center-xs middle-xs">
          <div class="box">
                <span class="footer-link">
                  <!-- Update your Git Profile Link -->
                  <a aria-label="Github" href="https://github.com/gms64/nuxt-static-skeleton" target="_blank">
                    <img alt="Github" class="icon-filter" height="24"
                         src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" style="color:#fff;"
                         width="24"/>
                  </a>
                </span>
          </div>
        </div>
        <!-- Links to pages -->
        <div class="col-xs-4 center-xs middle-xs">
          <div class="box">
            <span class="footer-link"><nuxt-link to="/about">about</nuxt-link></span>&nbsp;&nbsp;
            <span class="footer-link"><nuxt-link to="/contact">contact</nuxt-link></span>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>