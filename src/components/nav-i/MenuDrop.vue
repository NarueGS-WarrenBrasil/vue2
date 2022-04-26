<template>
    <div class= 'dropdow'>
            <div class="dropdown">
                <span id="menu">Menu</span>
                <div class="dropdown-content">
                    <li>Link1</li><br>
                    <li>Link2</li><br>
                    <li>Link3</li>
                </div>
            </div>
        </div>
</template>

<script>
export default {
    name:'Menudrop',
}
</script>

<style>
    #menu{
        font-size:7mm;
    min-width: 10px;
    max-width: 190px;
    float: left;
    text-decoration: none;
    color: #f2f2f2;
    padding: 14px 60px;
    padding-top: 20px;
    }
    
    .dropdown-content{
        margin-top:3%;
    }
</style>