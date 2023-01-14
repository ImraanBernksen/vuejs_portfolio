<template>
  <div id="projects">
    <h2><ins>Projects</ins></h2>
    <div class="lead" id="projectlinks">
      <div class="row">
      <div class="card h-100" id="cards_" v-for="item in arr" :key="item" style="width: 30rem; margin: auto; background-color: transparent;">
        <img :src="item.imgSrc" loading="lazy" class="card-img-top" alt="...">
        <div class="card-body">
          <h4 class="card-title">{{item.projectName}}</h4>
          <a :href="item.linkOne" target="_blank" class="btn btn text-white" id="btn_">GitHub</a>
          <a :href="item.linkTwo" target="_blank" class="btn btn text-white" id="btn_">Netlify</a>
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
          linkOne: "https://github.com/ImraanBernksen/PortfolioPage",
          linkTwo: "https://imraanbernksenportfoliopage.netlify.app/",
        },
        {
          imgSrc: "https://i.postimg.cc/ZRj3M6zy/project2.png",
          projectName: "JavaScript Calculator",
          linkOne: "https://github.com/ImraanBernksen/JS_Calculator",
          linkTwo: "https://imraanbernksen-jscalculator.netlify.app/",
        },
        {
          imgSrc: "https://i.postimg.cc/YCk25yNG/project3.png",
          projectName: "JavaScript EOMP",
          linkOne: "https://github.com/ImraanBernksen/JS_EOMP",
          linkTwo: "https://imraanbernksen-js-eomp.netlify.app/",
        },
        {
          imgSrc: "https://i.postimg.cc/T17jzWFh/project4.png",
          projectName: "Grid Layout",
          linkOne: "https://github.com/ImraanBernksen/gridlayout",
          linkTwo: "https://imraanbernksengridlayout.netlify.app/",
        },
        {
          imgSrc: "https://i.postimg.cc/bYmvtjnz/project5.png",
          projectName: "Media Query",
          linkOne: "https://github.com/ImraanBernksen/MediaQuery",
          linkTwo: "https://imraanbernksenmediaquery.netlify.app/",
        },
        {
          imgSrc: "https://i.postimg.cc/gjxr0MNy/project6.png",
          projectName: "Mini Project",
          linkOne: "https://github.com/ImraanBernksen/miniproject",
          linkTwo: "https://imraanbernksenminiproject.netlify.app/",
        },
      ],
    };
  },
};
</script>
<style scoped>

</style>
