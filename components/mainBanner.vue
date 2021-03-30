<template>
    <div class="container-fluid bg-warning d-flex justify-content-center align-items-center">
        <span>
            <h1>Get Personal Learning Recommendation</h1>
            <p class="qtz-text">Answer a few questions for your top picks</p>
            <button class="btn btn-outline-info">
                Get Started
            </button>
        </span>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
button{
    margin-left: 40%;
}

.qtz-text{
    margin-left: 30%;
}

.bg-warning{
    height: 300px;
    
}

h1,p{
    color: #002333;
}

.btn-outline-info {
  color: #002333 !important;
  border-color: #002333 !important;
}

.btn-outline-info:hover {
  color: #fff !important;
  background: #002333!important;
}

@media (max-width:575px){
    h1{
        font-size: 20px;
        text-align: center;
    }

    button{
    margin-left: 35%;
}

.qtz-text{
    margin-left: 0%;
    text-align: center;
}
}


</style>