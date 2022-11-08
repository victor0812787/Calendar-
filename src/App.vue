<template>
  <AppHeader/>
  <div class="w-full flex">
    <!-- <DcHeros/> -->
    <MyCalendar/>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader';
import MyCalendar from './components/MyCalender.vue';
// import DcHeros from './components/DcHeros';


export default {
      components:{AppHeader, MyCalendar},
}
</script>

<style>

</style>
