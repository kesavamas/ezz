<script>
export default {
  data() {
    return {
      yearNow: new Date().getFullYear()
    }
  }
}
</script>
<template>
  <footer class="footer">
    <div class="py-5 bg-dark">
      <div class="container px-4">
        <div class="row gy-4">
          <div class="col-lg-4 col-12">
            <div class="contact">
              <h2 class="text-white text-uppercase">Contact</h2>
              <ul class="text-white list-unstyled">
                <li class="d-flex align-items-center">
                  <i class="icons bi bi-geo-alt fs-4 p-2 ps-0"></i>Jln. Hayam Wuruk No. 199 Denpasar
                  Bali
                </li>
                <li class="d-flex align-items-center">
                  <i class="bi bi-telephone-plus fs-4 p-2 ps-0"></i>(0361) 474 8590
                </li>
                <li class="d-flex align-items-center">
                  <i class="bi bi-envelope-at fs-4 p-2 ps-0"></i>Ezzyhotel@gmail.com
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-4 col-12 open">
            <h2 class="text-white text-uppercase">Opening Times</h2>
            <p class="text-light font-monospace">
              Open at 09.00 Am - 19.00 Pm <br />Every Days except Sunday
            </p>
          </div>
          <div class="col-lg-4 col-12">
            <div class="maps">
              <h2 class="text-white"><i class="bi bi-geo-alt pe-2 py-1"></i>Maps</h2>
              <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d504870.73627706285!2d114.6302318572998!3d-8.662742094336052!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2dd24063dbb521f7%3A0xf841c6383a113418!2sElizabeth%20International%20Denpasar%20-%20Ezzy%20City!5e0!3m2!1sid!2sid!4v1707555892777!5m2!1sid!2sid"
                width="500" height="300" style="border: 0" async allowfullscreen loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="sec-footer bg-green">
      <div class="container-fluid ps-5">
        <div class="row ">
          <div
            class="social-icon mb-3 mb-lg-0 col-lg-4 col-12 d-flex flex-wrap justify-content-center justify-content-lg-start">
            <div class="fb">
              <a href="/facebook.com"><i class="bi bi-facebook fs-4"></i></a>
            </div>
            <div class="int">
              <a href="http://instagram.com/ezzyhotel"><i class="int bi bi-instagram fs-4"></i></a>
            </div>
            <div class="yt">
              <a href="https://www.youtube.com/results?search_query=ezzy+tv"><i class="yt bi bi-youtube fs-4"></i></a>
            </div>
          </div>
          <div class="col-lg-7 col-12">
            <div class="copyright d-flex mx-auto justify-content-center justify-content-lg-end">
              <span> &#169; copyright {{ yearNow }}.Made with ❤️ by Group 5</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.anchor {
  text-decoration: none;
  color: #117fb4;
}

ul li {
  font-size: 14px;
}

.footer {
  width: 100%;
  background-color: #222222;
}

.footer>div {
  /* max-width: 1200px; */
  width: 100%;
  margin-inline: auto;
}

.footer h2 {
  font-size: 1.4rem;
}

.footer iframe {
  max-width: 100%;
}

.sec-footer {
  background-color: #111111;
  padding-top: 1.5rem;
  padding-bottom: 1.5rem;
}

.social-icon a {
  margin-right: 1rem;
  color: white;
}

.fb {
  cursor: pointer;
  transition: all 300ms ease-in-out;
}

.fb:hover {
  transform: translateY(-5px);
}

.int {
  cursor: pointer;
  transition: all 300ms ease-in-out;
}

.int:hover {
  transform: translateY(-5px);
}

.yt {
  cursor: pointer;
  transition: all 300ms ease-in-out;
}

.yt:hover {
  transform: translateY(-5px);
}

.copyright {
  font-size: 0.8rem;
  color: white;
}
</style>
