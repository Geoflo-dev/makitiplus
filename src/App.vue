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
               <div class="navbar-brand logo">
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
                        <a class="button categories">
                        <img :src="require('./assets/svg/carbon_categories.svg')"/>
                        <p class="text">Catégories</p>
                        </a>
                      </div>
                   </div>
                 </div>
                 <!-- search menu -->
                 <div class="navbar-item">
                    <div class="rechercher">
                      
                        <div class="columns is-gapless">
                            <div class="column">
                                <input  type="search" class=" search-input"  placeholder="Rechercher">
                            </div>
                             
                             <div class="column my-2 mx-2">
                              <a class="btn-voice ">
                                 <img :src="require('./assets/svg/mic.svg')"/>
                              </a>
                             </div>
                         
                        </div>
                     </div>
                  </div>

                  <!-- poster une annonce -->
                  <div class="navbar-item">
                      <div class="buttons">
                        <a class=" button post-annonce">
                        <img :src="require('./assets/svg/akar-icons_circle-plus.svg')"/>
                        <p class="has-text-white">Poster une annonce</p>
                        </a>
                      </div>
                   </div>
                  <!-- fin poster une annonce -->
                     
                <div class="navbar-end">
                  <div class="navbar-item">
                    <div class="buttons">
                        
                        <a class="button favoris">
                              Favoris
                        </a>
                        <a class="button is-light">
                           <img :src="require('./assets/svg/avatar.png')"/>
                        </a>
                  </div>
                </div>
           </div>
      </div>
    </nav>
  </div>
  </div>

  <!-- content hero-->
  <section class="section ">
         <div class="menu-annonce mx-2">

          </div>   
   </section>

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
   border: 0.5px solid #077BC3;
   border-radius: 10px;
  }
  .search-input:focus{
   border-color: #077BC3;
   box-shadow:0 0 8px 0  #077BC3 ;
  }
  .btn-voice{
   height: 45px;
   border-radius: 10px;
   }
   .app{
    background-color:rgba(246, 246, 246, 1);
   }
   .post-annonce{
     
      width: 213px;
      height: 45px;
      /* Blue Gradient btn */

      background: linear-gradient(270deg, #067AC2 0%, #209EDB 100%), #C4C4C4;
      border-radius: 5px;
   }

   .categories{
    
      width: 150px;
      height: 45px;
      background: linear-gradient(0deg, #DCE5EC, #DCE5EC), #C4C4C4;
      border-radius: 5px;
   }
   .logo{
     width: 182px;
     height: 52px;
   }
   .favoris{
     width: 87px;
     height: 26px;
     background:#FFFFFF;
     border-color: #FFFFFF;


   }

   .menu-annonce{
      width: 1362px;
      height: 355px;
      background: #FFFFFF;
      border-radius: 10px;

   }
</style>
