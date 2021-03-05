<template>
  <div class="app">
    <!-- le menu de navigation-->
    <div class="container is-fullhd">
        <div class="navbar-top">
        <!-- plutard -->
        </div>
        <!-- Menu de naviagation -->
        <div class="nav-section">
           <nav class="navbar" role="navigation" aria-label="main navigation">
               <div class="navbar-brand">
                  <a class="navbar-item" href="https://bulma.io">
                   <img :src="require('./assets/svg/makitisvg.svg')"/>
                 </a>

                <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
                  <span aria-hidden="true"></span>
                  <span aria-hidden="true"></span>
                  <span aria-hidden="true"></span>
                </a>
              </div>

              <div id="navbarBasicExample" class="navbar-menu">
                 <div class="navbar-start">
                   <div class="navbar-item">
                      <div class="buttons">
                        <a class="button is-light">
                        <img :src="require('./assets/svg/carbon_categories.svg')"/>
                        <p class="text">Catégories</p>
                        </a>
                      </div>
                   </div>
                 </div>
                 <!-- search menu -->
                 <div class="navbar-item">
                    <div class="rechercher">
                       <div class="columns">
                        <div class="column">
                           <input  type="search" class="search-input"  placeholder="Small input">
                        </div>
                        <div class="column">Second </div> 
                       </div>  
                     </div>
                 </div>


                <div class="navbar-end">
                  <div class="navbar-item">
                    <div class="buttons">
                        <a class="button is-primary">
                        <strong>Sign up</strong>
                        </a>
                        <a class="button is-light">
                        Log in
                    </a>
                  </div>
                </div>
           </div>
      </div>
    </nav>
  </div>
  </div>

</div>
  
</template>
<script>
export default {
  
}
</script>

<style lang="scss">
  .navbar-top{
    width: 1440px;
    height: 34px;
    left: 0px;
    top: 0px;
   /* Blue Gradient btn */
    background: linear-gradient(270deg, #067AC2 0%, #209EDB 100%), #C4C4C4;
   }
   .nav-section{
    
    background: #FFFFFF;
   }
   .cat-menu{
  padding:5px 5px;
  width: 150px;
  height: 45px;
  background: linear-gradient(0deg, #DCE5EC, #DCE5EC), #C4C4C4;
  border-radius: 5px;
   }
  .rechercher{
   width: 516px;
   height: 45px;
   border-radius: 10px;
   background: linear-gradient(180deg, #4DBCEF 0%, #077BC3 100%);
   border-radius: 10px;
  }
  .search-input{
   width: 462px;
   height: 45px;
   background: #FFFFFF;
   border: 0.5px solid rgba(196, 196, 196, 1);
   border-radius: 10px;
  }
</style>
