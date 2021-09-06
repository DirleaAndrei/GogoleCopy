<template>
    <div class="row" id="footer">
        <div class="col-12" id="footerRo">
            <p id="pRomania">Romania</p>
        </div>
        <div class="row" id="footerLinks">
            <div class="col col-12 col-sm-12 col-md-8 col-lg-6 col-xl-6 d-inline-flex justify-content-center justify-content-sm-center justify-content-xl-start justify-content-lg-start jusify-content-md-start" id="footerLeft">
                <div class="d-inline footer-left"><a href="">About</a></div>
                <div class="d-inline footer-left"><a href="">Advertising</a></div>
                <div class="d-inline footer-left"><a href="">Business</a></div>
                <div class="d-inline footer-left"><a href="">How search works</a></div>
            </div>
            <div class="col col-12 col-sm-12 col-md-4 col-lg-6 col-xl-6 d-inline-flex justify-content-center justify-content-sm-center justify-content-xl-end justify-content-lg-end jusify-content-md-end" id="footerRight">
                <div class="d-inline footer-right"><a href="">Privacy</a></div>
                <div class="d-inline footer-right"><a href="">Terms</a></div>
                <div class="d-inline footer-right"><a href="">Settings</a></div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'page-footer'
}
</script>

<style>
    #footer{
        background-color: #f2f2f2; 
        color: rgba(0,0,0,.54);
        width:100%;
        margin:0px;
        min-width:400px;
        padding:0px;
        position: absolute;
        bottom: 0;
    }
    #footerRo{
        border-bottom: 1px solid #dadce0
    }
    #pRomania{
        margin-bottom: 0px; 
        padding:15px 30px; 
        font-size: 14px;
    }
    .footer-right{
        padding:15px;
        float:right;
        font-size: 14px;
        text-decoration: none;
    }
    .footer-left{
        padding:15px;
        float:left;
        font-size: 14px;
        text-decoration: none;
    }
    .footer-left>a, .footer-right>a{
         text-decoration: none;
        color: rgba(0,0,0,.54);
    }
    .footer-left>a:hover, .footer-right>a:hover{
        color: rgba(0,0,0,.54);
        text-decoration: underline;
    }

</style>