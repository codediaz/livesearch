<template lang="">
    <div id="appWrapper">
       <div class="contanier">
        <div class="search-box">
            <input type="text" class="search-input" name="q" placeholder="Escribe una palabra...">
            <ul class="result-list show">
                <li
                v-for="x in 10" class="result-item">
                    <a href="#" class="result-link">
                        <div class="result-title">Nombre del post</div>
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
<style>
    body{
        font-family: sans-serif;
    }

    ::-webkit-scrollbar{
        width: 10px;
    }

    ::-webkit-scrollbar-track{
        background: #f1f1f1;
    }

    ::-webkit-scrollbar-thumb{
        background: #888;
    }

    ::-webkit-scrollbar-thumb:hover{
        background: #555;
    }

    .container{
        padding: 30px;
    }

    .search-box{
        position: relative;
        display: flex;
        align-items: center;
        flex-direction: column;
    }

    .search-input{
        width: 600px;
        height: 30px;
        border-radius: 10px;
        border: 0;
        background: #eeeeee;
        padding: 10px 20px;
        font-size: 18px;
        outline: none;
    }

    .result-list.show{
        position: absolute;
        width: 640px;
        max-height: 250px;
        overflow-y:auto;
        list-style: none;
        background: #fff;
        padding: 0;
        top: 40px;
        border-radius: 10px;
        box-shadow: 1px 2px 8px 0px #b5b5b5;
    }

    .result-list.hide{
        display: none;
    }

    .result-item{
        border-bottom: 1px solid #ececec;
    }

    .result-link{
        text-decoration: none;
        color: #333;
        display: block;
        padding: 10px 15px;
    }

    .result-link{
        background: #f9f9f9;
    }

    .result-title{
        font-size: 20px;
        font-weight: 600;
    }

    .result-content{
        font-size: 18px;
    }

</style>