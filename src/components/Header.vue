<template>
  <header>
    <div>
      <img src="../assets/dc-logo.png" alt="" />
    </div>
    <div>
      <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIEDOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>

<style lang="scss">
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