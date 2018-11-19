<template>
  <div class='bill-box'>
    <h1>{{name}}</h1>
    <h2>{{value}}</h2>
    <div class='bill-box-bottom'>
      <h3>{{date}}</h3>
    </div>
  </div>
</template>


<script>
export default {
  name: 'BillBox',
  props: {
    name: String,
    value: String,
    date: String
  }
}
</script>


<style scoped>

.bill-box{
  width: 90px;
  height: 90px;
  border-radius: 12%;
  background: rgba(24, 157, 197, 0.123);
  padding: 30px;
  float: left;
  margin: 20px;
  text-align: left;
  color: azure;
  position: relative;
}

.bill-box-bottom{
  position: absolute;
  bottom: 22px;
}


h1{
  color: azure;
  font-size: 15px;
  margin-bottom: 8px; 
}

h2{
  font-size: 20px;
}
h3{
  font-size: 12px;
}

</style>
