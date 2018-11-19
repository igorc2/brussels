<template>
  <div class='bill-group-list'>
    <ul>
        <li><router-link to="/billgroup/1">Outubro</router-link></li>
        <li>Novembro</li>
        <li>Dezembro</li>
    </ul>
  </div>
</template>

<script>

export default {
  name: 'home'
}
</script>

<style scoped>

.bill-group-list{
  text-align: left;
  color: azure;
}

.bill-group-list li{
  border-radius: 5px; 
  list-style: none;
  padding: 12px 10px;
  margin: 25px 0;
  border: 1px solid rgb(34, 80, 117);
}

</style>
