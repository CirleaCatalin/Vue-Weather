<template>
  <div class="control">
    <div class="wrap">
      <div class="search">
        <input type="text" class="searchTerm" placeholder="Add a city">
        <button type="submit" class="addButton">+</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
    }
  }

}
</script>

<style>
.search {
  width: 100%;
  position: relative;
  display: flex;
}
.search.error{
  margin-top:43px
}
.searchTerm {
  width: 100%;
  border: 3px solid black;
  border-right: none;
  padding: 5px;
  height: 20px;
  border-radius: 5px 0 0 5px;
  outline: none;
}
/*.error {*/
/*  font-size: 11px;*/
/*  text-align: center;*/
/*  margin-top: 5px;*/
/*  color: #FF9494;*/
/*  font-weight: bold;*/
/*  height: 37px;*/
/*}*/
/*.searchTerm.not-found {*/
/*  border: 3px solid red;*/
/*  animation: shake 0.82s cubic-bezier(.36,.07,.19,.97) both;*/
/*}*/
/*::placeholder {*/
/*  color: var(--c, gray);*/
/*}*/
.addButton {
  width: 40px;
  height: 36px;
  border: 1px solid black;
  background: black;
  text-align: center;
  color: #fff;
  border-radius: 0 6px 5px 0;
  cursor: pointer;
  font-size: 20px;
}
</style>
