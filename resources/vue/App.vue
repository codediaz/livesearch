<template lang="">
    <div id="appWrapper">
       <div class="contanier">
        <div class="search-box">
            <input type="text" class="search-input" name="q" placeholder="Escribe una palabra...">
            <ul class="result-list-show">
                <li
                v-for="x in 10" class="result-item">
                    <a href="#" class="result-link">
                        <div class="result-tittle">Nombre del post</div>
                        <div class="result-content">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        </div>
                    </a>
                </li>
            </ul>
        </div>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Similique nobis architecto dolorem non maiores perspiciatis eligendi, explicabo assumenda ullam sapiente soluta, impedit ipsa quaerat unde asperiores fugit velit cumque atque.
        Ab magni voluptatibus est eius provident atque, facere recusandae! Commodi eos vitae ex quisquam quidem eligendi tempora, quam, veritatis tempore nulla ratione sit itaque reprehenderit suscipit, voluptates pariatur voluptatem quod!</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Similique nobis architecto dolorem non maiores perspiciatis eligendi, explicabo assumenda ullam sapiente soluta, impedit ipsa quaerat unde asperiores fugit velit cumque atque.
        Ab magni voluptatibus est eius provident atque, facere recusandae! Commodi eos vitae ex quisquam quidem eligendi tempora, quam, veritatis tempore nulla ratione sit itaque reprehenderit suscipit, voluptates pariatur voluptatem quod!</p>
       </div>
    </div>
</template>
<script>
export default {

    data(){
        return{
            
        }
    }

    
}
</script>
<style lang="">
    
</style>