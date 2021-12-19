<template>
  <div>
    <popular-movies/>
    <upcoming-movies/>
  </div>
</template>

<script>
  import PopularMovies from "@/components/PopularMovies";
  import UpcomingMovies from "@/components/UpcomingMovies";
  export default {
    name: 'Home',
    components: {
      UpcomingMovies,
      PopularMovies
    },
  }
</script>
