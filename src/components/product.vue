<template>
  <div class="row justify-content-around">
    <div v-for="bmw in cars" keys="bmw" class="card " style="width: 18rem;">
  <img :src="bmw.image" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">{{bmw.name}}</h5>
    <p class="card-text">Price: R {{bmw.price}}</p>
    <button class="btn btn-secondary">Buy</button>
  </div>
</div>
</div>
    
</template>
<script>

export default {
    name: 'bmw',
    data(){
        return{
            cars : [
                {
                    id: 1,
                    name:'4 Series 420d Gran Coupe M Sport',
                    price:939900 ,
                    image:'https://i.postimg.cc/7ZvXYzRV/21791775-1024x596.jpg'
                },
                {
                    id: 2,
                    name:'1 Series 120i 5-Door Automatic',
                    price:389999 ,
                    image:'https://i.postimg.cc/N0N2zqqn/21578298-1024x537.jpg'
                },
                {
                    id: 3,
                    name:'X3 xDrive20d Luxury Line',
                    price:589900 ,
                    image:'https://i.postimg.cc/ZnqWPwMS/21631676-1024x635.jpg'
                },
                {
                    id: 4,
                    name:'2 Series 220i Coupe M Sport',
                    price:819900 ,
                    image:'https://i.postimg.cc/8PQ5zP1G/21541068-1024x615.jpg'
                },
                

            ]
        }
    }
}
</script>
<style>
.row{
  margin-top: 7%;
}

.btn{
  margin-left: 40%;
}
</style>