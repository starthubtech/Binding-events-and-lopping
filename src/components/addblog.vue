<template>
    <div>
        <h3 class="text-center">Add a New Blog </h3>
        <form>
            <label>Blog Title :</label>
            <input type="text" required>
            <label>Blog Content :</label>
            <textarea />
        </form>
        <div id="newBlog">
            <h4>Preview Blog</h4>
            <p>Blog Title :</p>
            <p>Blog Content :</p>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
form {
    text-align: center;
    background-color: rgb(150, 137, 137);
    padding: 20px;
}
#newBlog {
    text-align: center;
    background-color: rgb(150, 137, 137);
    padding: 20px;
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
</style>
