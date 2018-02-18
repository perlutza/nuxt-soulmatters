<template>


    <div class="layer">
<div class="background">
    <img src="/images/abstract2.jpg">
<h1>Soulmatters</h1>
        


        </div>
</div>



</template>

<style>


h1{
    font-size: 20px;
    color: #fff;
}


.background{
  height: 800px;
  width: 100%;
  display: flex;
  object-fit: cover;
  justify-content: center;
  opacity: 0.9;
  position: relative;


}


img{
    width: 100%;
    object-fit: cover;
}

.layer {
    width: 100%;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    background-color: #212121;
    position: relative;
    -o-object-fit: cover;
    object-fit: cover;
    z-index: 101;
}



.background{
    grid-template-columns: repeat(1);
    grid-template-areas: ".content";
    grid-gap: 20px;
}


</style>


<style>
.item1 { grid-area: header; }
.item2 { grid-area: menu; }
.item3 { grid-area: main; }
.item4 { grid-area: right; }
.item5 { grid-area: footer; }

.grid-container {
  display: grid;
  grid-template-areas:
    'header header header header header header'
    'menu main main main right right'
    'menu footer footer footer footer footer';
  grid-gap: 10px;
  background-color: #2196F3;
  padding: 10px;
}
.grid-container > div {
  background-color: rgba(255, 255, 255, 0.8);
  text-align: center;
  padding: 20px 0;
  font-size: 30px;
}
</style>

