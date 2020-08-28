<template>
  <div >
   <Layout>
  <Slider></Slider>
  <Course></Course>
  <about></about>
  <Service></Service>
   <Student></Student>
  <Contact></Contact> 
  </Layout>
  </div>
</template>

<script>
import Layout from '../components/Layout/Layout'
import Slider from '../components/Slider'
import Course from '../components/Course'
import About from '../components/About'
import Service from '../components/Service'
import Contact from '../components/Contact'
import Student from '../components/Student'
export default {
  name: 'HelloWorld',
  components:{
    Layout,
    Slider,
    Course,
    About,
    Service,
    Contact,
    Student
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


</style>
