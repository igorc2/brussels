<template>
  <div class='bill-group'>
    <h1>{{name}}</h1>
    <BillBox name="Eletricidade" value='152.15' date='31/10'/>
    <BillBox name="Água" value='42.63' date='12/10'/>
    <BillBox name="Internet" value='109.00' date='08/10'/>
    <BillBox name="Aluguel" value='912.00' date='20/10'/>
  </div>
</template>


<script>
import BillBox from './BillBox.vue';
export default {
  name: 'BillGroup',
  props: {
    name: String
  },
  components: {
      BillBox
  }
}
</script>


<style scoped>

.bill-group{
  /*background: rgb(76,57,88);
  background: linear-gradient(159deg, rgba(76,57,88,1) 0%, rgba(59,40,88,1) 35%, rgba(37,27,55,1) 100%);*/
  
  text-align: right;
}



h1{
  color: azure;
  font-size: 18px;
  margin-bottom: 8px;
  margin-right:24px; 
}

</style>
