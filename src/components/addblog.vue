<template>
    <div>
        <h3 class="text-center">Add a New Blog </h3>
        <form>
            <label>Blog Title :</label>
            <input type="text" v-model.lazy="blog.title" required>
            <label>Blog Content : </label>
            <textarea v-model.lazy="blog.content" />
        </form>
         <div class="boxes">
            <label>Technology</label>
            <input type="checkbox" value="Technology" v-model="blog.categories" />
            <label>Lifestye</label>
            <input type="checkbox" value="Lifestye" v-model="blog.categories" />
            <label>Travel</label>
            <input type="checkbox" value="Travel" v-model="blog.categories" />
        </div>
        <div id="newBlog">
            <h4>Preview Blog</h4>
            <p>Blog Title : {{blog.title}}</p>
            <p>Blog Content :</p>
            <p>{{blog.content}}</p>
            <p>Blog Categories: </p>
            <ul>
                <li v-for="category in categories">{{blog.category}}</li>
            </ul>
        </div>
       
    </div>
</template>

<script>
export default {
    data(){
        return{
            blog: {
            title:"",
            content: "",
            categories: []
        }
        }
    }

}
</script>

<style scoped>
form {
    text-align: center;
    background-color: rgb(150, 137, 137);
    padding: 20px;
}
#newBlog {
    background-color: rgb(150, 137, 137);
    padding: 20px 50px;
}
input, textarea {
    display: block;
    width: 100%;
    padding: 10px;
}
label {
    display: block;
    margin:20px 0;
}
.boxes{
    background-color: rgb(150, 137, 137);
}
.boxes input{
    display: inline;
}
.boxes label {
    display: inline;
}
</style>
