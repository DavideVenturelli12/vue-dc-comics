<template>
  <header>
    <div>
      <img src="../assets/dc-logo.png" alt="" />
    </div>
    <div>
      <ul>
        <li v-for="item in menu" :key="item">{{ item }}</li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
  data() {
    return {
      menu: [
        "CHARACTERS",
        "COMICS",
        "MOVIES",
        "TV",
        "GAMES",
        "COLLECTIBLES",
        "VIEDOS",
        "FANS",
        "NEWS",
        "SHOP",
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 10%;

  img {
    width: 50px;
    margin: 15px 0;
  }

  li {
    display: inline-block;
    margin: 12px;
    font-size: 14px;
    font-weight: 600;
    cursor: pointer;

    &:hover {
      border-bottom: 2px solid #0282f9;
    }
  }
}
</style>