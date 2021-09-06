<template>
    <div>
        <div class="row" id="logo-container">
            <div id="logo" class="col col-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 justify-content-bottom">
                <img src="@/assets/googlelogo_color_272x92dp.png" alt="">
            </div>
        </div>
        <div class="row">
            <div id="search" class="col col-12 col-sm-12 col-md-12 col-lg-12 col-xl-12" style=" padding:20px">
                <div class="input-group justify-content-center" style="margin:auto;margin-top: 6px;width:100%;margin:0px;padding-top:6px;">
                        <!-- <div class="input-group-prepend" >
                            <span class="input-group-text" id="magnifingGlass">
                                <img src="@/assets/49116.png" width="15px" height="15px" style="position:absolute" alt="">
                            </span>
                        </div> -->
                        <div class="form-group" style="display:inline-block;max-width: 500px;min-width: 200px;width:70%" id="ceva">
                            
                            <input type="text" class="form-control"  id="input-form">
                        </div>
                    </div>
                <div style="padding-top:18px">
                    <button class="btn" type="button" id="google-search">Google Search</button>
                    <button class="btn" type="button" id="google-lucky">I'm feeling Lucky</button>
                </div>
            </div>
        </div>
        <div class="row">
            <div id="languages" class="col col-12 col-sm-12 col-md-12 col-lg-12 col-xl-12">
                <p style="font-size: 14px;margin-bottom: 24px;height:">Google offered in:  
                    <a href="" style="color:#1a0dab">Romana</a> 
                    <a href="" style="color:#1a0dab">Maghiar</a> 
                    <a href="" style="color:#1a0dab">Deutsch</a>
                </p>
            </div>
        </div>
        
    </div> 

</template>

<script>
export default {
    name:'page-content'
}
</script>

<style>
#logo-container{
    min-height: 100px;
    max-height: 290px;
    height: calc(100vh - 560px);
    position:relative;
    min-width:400px;
}

#logo{
    text-align: center;
    position: absolute;
    bottom: 0px;
}
#google-lucky, #google-search{
    background-color: rgb(248, 248, 248);
    padding:0px 16px;
    margin:11px 4px;
    height:36px;
    
}

#google-lucky:hover, #google-search:hover{
    border: solid 1px rgb(218, 218, 218);
    box-shadow: 1px 1px 1px #bfbfbf
}
#search{
    text-align: center;
}
#languages{
    margin-left: 0px;
    margin-right: 0px;
    width:100%;
    display:inline-block;  
    height:30vh ;
    min-height: 50px; 
    text-align: center;
    padding:0px
    
}

#languages>p>a{
    margin-right:10px
}

#search-bar{
    min-width:350px;
    max-width:580px;
    width:100%
}
#input-form{
    border-radius: 30px;
}
</style>