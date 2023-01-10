<template>
  <div id="projects">
    <h2><ins>Projects</ins></h2>
    <div class="lead" id="projectlinks">
      <div id="carouselExampleCaptions" class="carousel slide mx-5" data-bs-ride="false">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3" aria-label="Slide 4"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="4" aria-label="Slide 5"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="5" aria-label="Slide 6"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://i.postimg.cc/B6PMWhN1/project1.png" class="d-block w-100" alt="picture1">
            <div class="carousel-caption d-none d-md-block">
              <h4 class="text-dark">Portfolio Page</h4>
              <p><a class="project-tile" target="_blank" href="https://github.com/ImraanBernksen/Ecommerce_website">GitHub</a><a class="project-tile" target="_blank" href="https://imraanbernksenecommercewebsite.netlify.app/">Netify</a></p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="https://i.postimg.cc/ZRj3M6zy/project2.png" class="d-block w-100" alt="picture2">
            <div class="carousel-caption d-none d-md-block">
              <h4 class="text-dark">JavaScript Calculator</h4>
              <p><a class="project-tile" target="_blank" href="https://github.com/ImraanBernksen/miniproject">GitHub</a><a class="project-tile" target="_blank" href="https://imraanbernksenminiproject.netlify.app/">Netify</a></p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="https://i.postimg.cc/YCk25yNG/project3.png" class="d-block w-100" alt="picture3">
            <div class="carousel-caption d-none d-md-block">
              <h4 class="text-dark">JavaScript EOMP"</h4>
              <p><a class="project-tile" target="_blank" href="https://github.com/ImraanBernksen/Bootstrap-ContainerExample-">GitHub</a><a class="project-tile" target="_blank" href="https://imraanbernksenbootstrapcontainer.netlify.app/">Netify</a></p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="https://i.postimg.cc/T17jzWFh/project4.png" class="d-block w-100" alt="picture4">
            <div class="carousel-caption d-none d-md-block">
              <h4 class="text-dark">Grid Layout</h4>
              <p><a class="project-tile" target="_blank" href="https://github.com/ImraanBernksen/MediaQuery">GitHub</a><a class="project-tile" target="_blank" href="https://imraanbernksenmediaquery.netlify.app/">Netify</a></p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="https://i.postimg.cc/bYmvtjnz/project5.png" class="d-block w-100" alt="picture5">
            <div class="carousel-caption d-none d-md-block">
              <h4 class="text-dark">Media Query</h4>
              <p><a class="project-tile" target="_blank" href="https://github.com/ImraanBernksen/gridlayout">GitHub</a><a class="project-tile" target="_blank" href="https://imraanbernksengridlayout.netlify.app/">Netify</a></p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="https://i.postimg.cc/gjxr0MNy/project6.png" class="d-block w-100" alt="picture6">
            <div class="carousel-caption d-none d-md-block">
              <h4 class="text-dark">Mini Project</h4>
              <p><a class="project-tile" target="_blank" href="https://github.com/ImraanBernksen/flexbox-">GitHub</a><a class="project-tile" target="_blank" href="https://imraanbernksenflexbox.netlify.app/">Netify</a></p>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev bg-dark" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next bg-dark" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
    <div class="lead" id="viewprojects">
      <ul>
        <li>
          <a
            id="M1I0B_"
            target="_blank"
            href="https://github.com/ImraanBernksen"
            class="fa-brands fa-github"
          ></a>
        </li>
        <li>
          <a
            id="M1I0B_"
            target="_blank"
            href="https://app.netlify.com/teams/imraanbernksen/overview"
            class="fa-solid fa-n"
          ></a>
        </li>
        <li>
          <a
            id="M1I0B_"
            target="_blank"
            href="https://codepen.io/IMRAANBERNKSEN"
            class="fa-brands fa-codepen"
          ></a>
        </li>
      </ul>
    </div>
  </div>
</template>
<script>
export default {
  name: "Projects",

  data() {
    return {
      arr: [
        {
          imgSrc: "https://i.postimg.cc/B6PMWhN1/project1.png",
          projectName: "Portfolio Page",
          linkOne: "https://github.com/ImraanBernksen/Ecommerce_website",
          linkTwo: "https://imraanbernksenecommercewebsite.netlify.app/",
        },
        {
          imgSrc: "https://i.postimg.cc/ZRj3M6zy/project2.png",
          ProjectName: "JavaScript Calculator",
          linkOne: "https://github.com/ImraanBernksen/Ecommerce_website",
          linkTwo: "https://imraanbernksenecommercewebsite.netlify.app/",
        },
        {
          imgSrc: "https://i.postimg.cc/YCk25yNG/project3.png",
          ProjectName: "JavaScript EOMP",
          linkOne: "https://github.com/ImraanBernksen/Ecommerce_website",
          linkTwo: "https://imraanbernksenecommercewebsite.netlify.app/",
        },
        {
          imgSrc: "https://i.postimg.cc/T17jzWFh/project4.png",
          ProjectName: "Grid Layout",
          linkOne: "https://github.com/ImraanBernksen/Ecommerce_website",
          linkTwo: "https://imraanbernksenecommercewebsite.netlify.app/",
        },
        {
          imgSrc: "https://i.postimg.cc/bYmvtjnz/project5.png",
          ProjectName: "Media Query",
          linkOne: "https://github.com/ImraanBernksen/Ecommerce_website",
          linkTwo: "https://imraanbernksenecommercewebsite.netlify.app/",
        },
        {
          imgSrc: "https://i.postimg.cc/gjxr0MNy/project6.png",
          ProjectName: "Mini Project",
          linkOne: "https://github.com/ImraanBernksen/Ecommerce_website",
          linkTwo: "https://imraanbernksenecommercewebsite.netlify.app/",
        },
      ],
    };
  },
};
</script>
<style></style>
