<template>
       <div id="skills">
       <h2><ins>Resume</ins></h2>
<div class="row">
        <div class="col-lg-4 p-4">
            <div class="card" id="cards_" v-for="item in resume" :key="item" style="height: 25rem; width: 25rem; margin: auto;">
              <div class="card-body">
                <h4 class="card-title text-dark">{{item.headingText1}}</h4>
                        <p class="card-text lead bg-white text-dark-dark about-par">
                          Name: {{item.Name}}<br>
                          Surname: {{item.Surname}}<br>
                          Birth: {{item.Birth}}<br>
                          Cellphone: {{item.Cellphone}}<br>
                          Email: {{item.Email}}<br>
                          Location: {{item.Location}}<br>
                        </p>
              </div>
            </div>
        </div>
        <div class="col-lg-4 p-4">
            <div class="card" id="cards_" v-for="item in resume" :key="item" style="height: 25rem; width: 25rem; margin: auto;">
              <div class="card-body">
                <h4 class="card-title text-dark">{{item.headingText2}}</h4>
                <p class="card-text lead bg-white text-dark-dark about-par">
                  {{item.resumeText1}}<br><br>
                  {{item.resumeText2}}<br>
                </p>
              </div>
            </div>
        </div>
        <div class="col-lg-4 p-4">
            <div class="card" id="cards_" v-for="item in resume" :key="item" style="height: 25rem; width: 25rem; margin: auto;">
              <div class="card-body">
                <h4 class="card-title text-dark">{{item.headingText3}}</h4>
                <p class="card-text lead bg-white text-dark-dark about-par">
                  {{item.resumeText3}}<br>
                  {{item.resumeText4}}<br>
                  {{item.resumeText5}}<br>
                  {{item.resumeText6}}<br>
                </p>
              </div>
            </div>
        </div>
</div>
       </div>
</template>
<script>
export default {
    name: 'Resume',

    data() {
    return {
      resume: [
        {
          headingText1: "Details",
          headingText2: "Education",
          headingText3: "Experience",
          resumeText1: "Oaklands High School, Chukker Rd, Lansdowne - Matriculated (2016 - 2020)",
          resumeText2: "Life Choices Academy, 314 Imam Harom Rd, Lansdowne - Student (2022 - Currently)",
          resumeText3: "Grasshopper Coding Fundamentals I & II Certifications - 2022 (Completed)",
          resumeText4: "Responsive Web Design Developer Certification - 2022 (Completed)",
          resumeText5: "JavaScript  Algorithms and Data Structures Certification - 2022 (Completed)",
          resumeText6: "Life Choices Coding Academy Student - 2022 (Currently)",
          Name: "Mogamad Imraan",
          Surname: "Bernksen",
          Birth: "04/07/2002",
          Cellphone: "0681278921",
          Email: "imraanbernksen@gmail.com",
          Location: "Cape Town, South Africa",
        },
      ],
    };
  },
}
</script>
<style scoped>
    
</style>