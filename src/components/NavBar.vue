<template>
<nav class="menu">
    <ul class="menu-list">
      <nav class="navbar navbar-expand-lg navbar navbar-light bg-black static-top">
        <div class="container-fluid">
          <img class="logo" src="https://i.postimg.cc/bwMSp4tp/BLACK-M1-I0-B-LOGO.jpg" alt="logo">
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon bg-light"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarSupportedContent">
                      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                          <a class="nav-link" id="home_" href="/">Home</a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" id="about_" href="/about">About</a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" id="skills_" href="/projects">Projects</a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" id="testimonial_" href="/testimonials">Testimonials</a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" id="contact_" href="/contact">Contact</a>
                        </li>
                      </ul>
                    </div>
                  </div>
                </nav>
            </ul>
        </nav>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
</style>
