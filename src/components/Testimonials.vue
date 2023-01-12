<template>
    <div id="testimonial">
        <h2><ins>Testimonials</ins></h2>
        <div class="row">
            <div class="card" id="cards_" v-for="item in arr" :key="item" style="height: 36rem; width: 30rem; margin: auto;">
              <img :src="item.imgSrc" loading="lazy" class="card-img-top" alt="pic1">
              <div class="card-body">
                <h4 class="card-title text-dark">{{item.personName}}</h4>
                <p class="card-text">{{item.infoText}}</p>
              </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'Testimonials',
    
    data (){
    return {
  arr : [
  {
    personName: 'Meezaan Davids',
    infoText: 'Imraan seems like chill guy who likes to keep to himself. He is a smart person who likes to be challenged and very passionate about soccer. He is a good judge of character, determined and hardworking. Engage conversions and topics with an innovate mindset to things.',
    imgSrc: 'https://i.postimg.cc/pTFspNgf/t1.jpg',
  },
  {
    personName: 'Brogan Gys',
    infoText: 'He has five star skills when it come to soccer. Imraan is a very punctual person,  always on time. He is a very passionate person on the things he loves to do. He is very experienced with CSS, HTML and thus he always understands his code and work that he is busy with.',
    imgSrc: 'https://i.postimg.cc/KjQBYJv7/t2.jpg',
  },
  {
    personName: 'Lindokuhle Mgoqi',
    infoText: 'Imo has a huge amount of dedication. He is always on time and he make sure that his job is done. He has a humble personality and a good approach.',
    imgSrc: 'https://i.postimg.cc/SQtcH13q/t3.jpg',
  },
  {
    personName: 'Konke Makubalo',
    infoText: 'He has displayed extraordinary potential of being a very talented full stack developer. Imraan ideas are unique, seems impossible but are amazing when executed.',
    imgSrc: 'https://i.postimg.cc/QN5WnNQg/t4.jpg',
  },
  {
    personName: 'Kauthar Brandt',
    infoText: 'Imraan is a friendly individual and a pleasure to work with because of his supporting attributes. He encourages his peers to do their best, which allows him to work with any social group, which proves effective in group projects. His very knowledgeable on any topic, so its always lovely to engage in conversion with him.',
    imgSrc: 'https://i.postimg.cc/9f6FFBY4/t5.jpg',
  },
  {
    personName: 'Aliyah Du Toit',
    infoText: 'Imraan is a hard-working and compassionate individual. He never hesitates to assist others in need and is committed to achieving his goals. His determined attitude and welcoming personality allows him to prosper when collaborating with all types of personalities, making him an asset in group projects, as well as individual work.',
    imgSrc: 'https://i.postimg.cc/mkwdYYVV/t6.jpg',
  }
]
}
  }
}
</script>
<style scoped>
    
</style>