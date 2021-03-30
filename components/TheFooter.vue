<template>
    <footer class="page-footer bg-dark">
        <div class="container text-center text-white text-md-left">
            <div class="row pt-5">
                <div class="col-md-3 mx-auto mb-4 ">
                    <h5 class="text-uppercase font-weight-bold">Company</h5>

                    <ul class="list-unstyled">
                        <li class="my-2"><a href="#">About</a></li>
                        <li class="my-2"><a href="#">Careers</a></li>
                        <li class="my-2"><a href="#">Press</a></li>
                        <li class="my-2"><a href="#">Blog</a></li>
                    </ul>
                </div>

                <div class="col-md-3 mx-auto mb-4">
                    <h5 class="text-uppercase font-weight-bold">Community</h5>

                    <ul class="list-unstyled">
                        <li class="my-2"><a href="#">Scholarship</a></li>
                        <li class="my-2"><a href="#">Free Classes</a></li>
                        <li class="my-2"><a href="#">Refer a Friend</a></li>
                    </ul>
                </div>

                <div class="col-md-3 mx-auto mb-4">
                    <h5 class="text-uppercase font-weight-bold">Teaching</h5>

                    <ul class="list-unstyled">
                        <li class="my-2"><a  href="#">Become a Teacher</a></li>
                        <li class="my-2"><a href="#">Teaching Academy</a></li>
                        <li class="my-2"><a href="#">Teaching HandBook</a></li>
                    </ul>
                </div>

                <div class="col-md-3 mx-auto mb-4">
                    <h5 class="text-uppercase font-weight-bold">Mobile</h5>

                    
                </div>


            </div>
            <hr>
            <div class="main">
                <div class="logo">
                    <!-- codeBooth logo here -->
                    <!-- <img src="@/assets/logo.svg" height="30px" alt=""> -->
                </div>
                <div class="footer-menu">
                    <ul>
                        <li>Help</li>
                        <li>Privacy</li>
                        <li>Terms</li>
                    </ul>
                </div>

                <div class="copy-right">
                    codeBooth, GH 2021
                </div>

                <div class="social-media">
                    <ul>
                        <li><span class="iconify" data-icon="ic:baseline-facebook" data-inline="false"></span></li>
                        <li><span class="iconify" data-icon="mdi:twitter-circle" data-inline="false"></span></li>
                        <li><span class="iconify" data-icon="mdi:instagram" data-inline="false"></span></li>
                    </ul>
                </div>
            </div>
        </div>

    </footer>
</template>

<script>
    export default {
        
    }
</script>

<style  scoped>
 .bg-dark{
     background: #002333!important;
 }

 .list-unstyled li a{
     text-decoration: none;
     color: #fff;
 }

  hr{
        background: #fff;
    }

    .main{
        display: flex;
        justify-content: space-between;
        font-size: 15px;
        flex-wrap: wrap;        
    }

    .footer-menu ul{
        display: flex;
    }

  .social-media ul{
      display: flex;
  }

  ul li{
        list-style: none;
        font-size: 15px;
        padding-left: 10px;
    }

</style>