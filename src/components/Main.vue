<template>
  <div>
    <Header/>

    <section class="container">
      <div id="game-container">
        <Board/>

        <Scores/>

        <ThemeLinks/>

      </div>
    </section>
  </div>
</template>

<script>
import Header from './Header';
import Board from './Board';
import Scores from './Scores';
import ThemeLinks from './ThemeLinks';

export default {
  components: {
    Header,
    Board,
    Scores,
    ThemeLinks,
  },
};
</script>
