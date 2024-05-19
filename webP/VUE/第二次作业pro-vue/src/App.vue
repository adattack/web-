<template>
  <div id="app">
    <Header/>
    <CourseFeatures />
    <LearningWays />
    <LearningExperience />
  </div>
</template>
<style>
  body{     
            max-width: 100%; 
            overflow-x: hidden;
            }
            #head{
               background-image: url(https://img2.imgtp.com/2024/03/21/MtgVGTD9.jpg) ;
               /* background-repeat:no-repeat; */
               /* background-size:contain; */
               height: 100%;
               width: 100%; 
            }
            #banner{
                z-index: -1;
            }
            #startwords1{
                z-index: 1;
                color: white;
                font-size: 50px;
                /* top:30% */
            }
            #loginbtn{
                background: rgba(255, 255, 255, 0);
                border: white 1px solid;
                color: white;
                border-radius: 10%;
                /* top:5px; */
                /* width: 20%; */
                }
            #registerbtn{
                background: rgba(255, 255, 255, 0);
                border: white 1px solid;
                color: white;
                border-radius: 10%;
                /* top:5px; */
                /* width: 20%; */
            }
            #studybtn{
                z-index: 1;
                background-color: white;
                border: white;
                color: rgb(0, 128, 255);
                border-radius: 10px;
            }
            #startwords2{
                z-index: 1;
                /* left: 30%; */
                /* top: 50%; */
                color: white;
                font-size: 20px;
            }
            #svg{
                position: absolute;
                height: auto;
                left:8%;
                scale: 0.8;
            }
            #-lab{
               background-color: whitesmoke;
            }
            #lab-text{
               background-color: whitesmoke;
               width: 100%;
               height: max-content;
               padding-left: 20px;
            }
            #lab-text-title{
                margin-top: 10px;
                left: 5%;
                font: bold 50px Arial;
               }
            #lab-text-content{
               /* top:180%; */
               margin-top: 10px;
               left:5%;
               font: 20px Arial;
            }
            #learnmore{
               margin-top: 20px;
               border: gray 1px solid;
               align-self:center;
               column-gap: 6;
               background-color: whitesmoke;
               color: gray;
               width: max-width;
               
            }
            #twostudy-title{
                margin-top: 10px;
                left: 5%;
                font: bold 50px Arial;
               }
            #twostudy-content{
               /* top:180%; */
               margin-top: 10px;
               left:5%;
               font: 20px Arial;
            }
            #course-title{
               font:bold 40px Arial;
            }
            #icon1-backgroud{
                background-color: rgb(98, 169, 245);
                width:4.5em; 
                height:4.5em;
                border-radius: 10px;
                left: 30%;
            }
            #icon1{
               /* position: absolute; */
               padding-left: 10px;
               padding-top: 13px;
               stroke: white;
               fill:white;
               background: transparent;
               stroke-width: 0.4;
               
            }
            #icon1-text{
                /* position: absolute; 
                left: 20%; */
                font:bold 20px Arial;
            }
            #icon1-content{
                /* position: absolute; 
                left: 20%; */
                font: 15px Arial;
                margin-top: 60px;
            }
            #learn{
               margin-left: 8%;
               text-decoration-line: underline;
            }
            #learn2{
               /* margin-left: 8%; */
               text-decoration-line: underline;
            }
            #icon2{
               position: absolute;
               padding-left: 10px;
               padding-top: 13px;
            }
            #footer{
                background-color: whitesmoke;
                height: 100px;
            }

</style>
<script>
import Header from './components/Header.vue';
import CourseFeatures from './components/CourseFeatures.vue';
import LearningWays from './components/LearningWays.vue';
import LearningExperience from './components/LearningExperience.vue';

export default {
  name: 'App',
  components: {
    Header,
    CourseFeatures,
    LearningWays,
    LearningExperience
  }
};
</script>