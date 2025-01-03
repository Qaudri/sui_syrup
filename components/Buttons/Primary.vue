<template>
  <button 
    @click="$emit('clicked')"
    class="btn-grad heading text-2xl h-fit items-center">
    <slot  />
  </button>
</template>

<style>

.btn-grad {background-image: linear-gradient(to right, #e52d27 0%, #700400  51%, #700400  100%)}
.btn-grad {
  padding: 5px 30px 10px 30px;
  text-align: center;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;            
  box-shadow: 0 0 10px #e52d27;
  border-radius: 10px;
  display: block;
}

.btn-grad:hover {
  background-position: right center; /* change the direction of the change here */
  color: #fff;
  text-decoration: none;
}
         
</style>