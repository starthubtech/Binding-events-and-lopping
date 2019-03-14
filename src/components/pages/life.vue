<template>
    <div id="life">
        <h5 class="text-center pt-3">A LifeStyle Blog</h5>
        <p>And if your lifestyle blog gets really big, and starts to draw a lot of attention, people will start to pay you to come and see them! 
            Isn’t that an amazing goal to reach for?
        Honestly, the steps to start monetizing a lifestyle blog are 
        the same steps that any type of blog would take. What a blog needs to start earning money is traffic, good content, and a knowledge for marketing. If you can get those three aspects down, you’re well on your way to start earning some 
        money from your lifestyle blog (or any type of blog, honestly).</p>
        <button><router-link to="/addBlog">Add New Blog </router-link></button>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
#life{
    background-color: #dfddcd;
}
h5 {
    color: #363336;
}
p {
    padding: 5% 10%;
    text-align: center;
    margin-bottom: 0px !important;
}
button {
  border-radius: 3px !important;
  border: 2px solid #3e4353;
  width: 130px;
  height: 40px;
  background-color: #ffffff;
  margin-left: 45%;
  margin-bottom: 20px;
}
button:hover {
  cursor: pointer;
  background: #3e4353;
  color: #ffffff;
  transition: ease-in 1s;
}

</style>
