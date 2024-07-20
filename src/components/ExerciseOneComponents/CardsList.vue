<template>
    <div class="card-list  wrapper">
        <div class="spacer xxx-large"></div>
        <div class="card-list-container">
            <div class="card">
                <img src="https://via.placeholder.com/400x300" alt="">
                <div class="spacer small"></div>
                <div class="card-desc">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. In bibendum gravida interdum. Quisque nec leo dapibus, luctus lorem a, sagittis augue. Cras volutpat magna eu odio fringilla, eu dictum lacus fringilla. 
                </div>
                <div class="spacer small"></div>
                <button>Read More</button>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/400x300" alt="">
                <div class="spacer"></div>
                <div class="card-desc">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. In bibendum gravida interdum. Quisque nec leo dapibus, luctus lorem a, sagittis augue. Cras volutpat magna eu odio fringilla, eu dictum lacus fringilla. 
                </div>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/400x300" alt="">
                    <div class="spacer"></div>
                   <div class="card-desc">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. In bibendum gravida interdum. Quisque nec leo dapibus, luctus lorem a, sagittis augue. Cras volutpat magna eu odio fringilla, eu dictum lacus fringilla. 
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
     name: 'CardsList',
}
</script>

<style scoped>
.card {
    border: 1px solid #ddd;
    padding: 18px;
    width: 25%;
    border-radius: 5px;
}
.card-list-container {
    display: flex;
    justify-content: space-between;
}
img {
   width: 100%;
}
.card-desc {
    text-align: center;
}

.card button {
    border: 1px solid #000;
    padding: 10px 20px;
    text-transform: uppercase;
    cursor: pointer;
    background: none;
}

</style>