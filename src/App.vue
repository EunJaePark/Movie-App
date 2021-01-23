<template>
  <div>
    <AppHeader></AppHeader>
    <router-view></router-view>
  </div>
</template>

<!--<script src="https://kit.fontawesome.com/aa7a88800a.js" crossorigin="anonymous"></script>-->

<script>
<<<<<<< HEAD
import AppHeader from './components/common/AppHeader'; // 원래의 app header.
// import AppHeader from './views/AppHeader'; // 좋아요 버튼 만들기 위해 생성한 views폴더 속의 app header.
=======
// import AppHeader from './components/common/AppHeader'; // 원래의 app header.
import AppHeader from './views/AppHeader'; // 좋아요 버튼 만들기 위해 생성한 views폴더 속의 app header.
>>>>>>> d2b8d71f843016244b06d4f7811fa33c5c94fa9d
// import MainPage from './views/MainPage';
// import MoviePage from './views/MoviePage';

export default {
  components: {
      AppHeader,
      // MainPage,
      // MoviePage,
  }
}
</script>

<style>
@import '../src/css/common.css';
@import '../src/css/reset.css';
</style>