<template>
  <div id="projects">
    <h2><ins>Projects</ins></h2>
    <div class="lead" id="projectlinks">
      <div style="display: grid; grid-template-columns: repeat(3, 1fr); margin: auto;">
      <div class="card h-100" v-for="item in arr" :key="item" style="width: 30rem; grid-column: span 1; margin: auto;">
        <img :src="item.imgSrc" loading="lazy" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">{{item.projectName}}</h5>
          <a :href="item.linkOne" class="btn btn-primary text-white">GitHub</a>
          <a :href="item.linkTwo" class="btn btn-primary text-white">Netlify</a>
        </div>
      </div>
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
