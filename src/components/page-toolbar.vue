<template>
    <div class="row justify-content-end" id="toolbar">
        <div class="d-inline my-auto" id="toolbar-links">
            <a href="" class="link" style="padding-left:15px;">Gmail</a>
            <a href="" class="link">Images</a>
        </div>
        <div class="d-inline my-auto" id="toolbar-buttons">
            <button class="btn btn-secondary" id="button-option">
                <img id="options" src="@/assets/keyboard-of-nine-circle-for-digital-devices.png" alt="">
            </button>
            <i class="far fa-eye"></i>
            <button class="btn btn-primary" id="button-signin">Sign in</button>
        </div>
    </div>
</template>

<script>
export default {
    name:'page-toolbar'
}
</script>

<style>
#toolbar{
    width:100%;
    padding:6px; 
    height:60px;
    margin: 0px;
    min-width:400px
}
#toolbar-buttons{
    width:135px;
    padding:0px
}
#toolbar-links{
    width:120px;
    padding:0px
}
.link{
    text-decoration: none;
    color: black;
    padding-right:15px;
    font-size:13px
}

.link:hover{
    text-decoration: underline;
    color: black;
    padding-right:15px;
    font-size:13px
}
#toolbar-container{
    width:160px
}
#options{
    width:20px;
    height:20px;

}
#button-option{
    width:36px;
    padding:8px;
    margin:4px;
    border-radius: 50%;
    background-color: white;
    border:transparent
}
#button-option:hover{
    padding:8px;
    border-radius: 50%;
    background-color: rgb(165, 165, 165);
    border:transparent
}
#button-signin{
    margin:0 8px;
    padding:9 23px;
}
</style>