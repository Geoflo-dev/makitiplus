<template>
        <div class="app">
                  <!-- le menu de navigation-->
    
        <div class="navbar-top">
                          <!-- plutard -->
        </div>
        <nav class="navbar is-transparent py-3">
               <div class="navbar-brand">
                 <a class="navbar-item" href="https://bulma.io">
                    <img :src="require('./assets/svg/makitisvg.svg')"/>
                 </a>
                 <div class="navbar-burger" data-target="navbarExampleTransparentExample">
                   <span></span>
                    <span></span>
                   <span></span>
                  </div>
               </div>

              <div id="navbarExampleTransparentExample" class="navbar-menu">
                       <div class="navbar-start">
                               <div class="buttons">
                                  <a class="button categories">
                                  <img :src="require('./assets/svg/carbon_categories.svg')"/>
                                  <p class="text">Catégories</p>
                                  </a>
                                </div>
                        </div>

                        <!-- la search bar -->
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
                        <!-- fin search bar -->
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
                                     <a class="button favoris">Favoris</a>
                                     <a class="button is-light">
                                      <img :src="require('./assets/svg/avatar.png')"/>
                                     </a>
                                   </div>
                                </div>
                             </div>

                        </div>
                 </nav>

                     
 

        
          <!-- content hero-->
          <section class="section  box mx-5 my-5">
                        <div class="columns ">
                               <div class="column is-7 ">
                                      <!-- premiere rangée des categories  -->
                                      <div class="tile is-ancestor"  >
                                          <div class="tile is-parent">
                                            <article class="tile is-child  categorie-electronique container">
                                                <a style="display:flex">
                                                        <img :src="require('./assets/svg/informatique.svg')"/>
                                                         <p class="subtitle">Catégories</p>
                                                 </a>
                                            </article>
                                          </div>
                                          <div class="tile is-parent">
                                            <article class="tile is-child categorie-transport container">
                                              <a style="display:flex">
                                                        <img :src="require('./assets/svg/transport.svg')"/>
                                                         <p class="subtitle">Catégories</p>
                                                 </a>
                                            </article>
                                          </div>
                                          <div class="tile is-parent">
                                            <article class="tile is-child categorie-immo container">
                                             <a style="display:flex">
                                                        <img :src="require('./assets/svg/immo.svg')"/>
                                                         <p class="subtitle">Catégories</p>
                                                 </a>
                                            </article>
                                          </div>
                                        </div>
                                        <!-- fin de la rangée -->
                                        <!-- deuxieme rangée -->
                                        <div class="tile is-ancestor">
                                          <div class="tile is-parent">
                                            <article class="tile is-child categorie-vetement container">
                                                 <a style="display:flex">
                                                        <img :src="require('./assets/svg/vetement1.svg')"/>
                                                         <p class="subtitle">Catégories</p>
                                                 </a>
                                            </article>
                                          </div>
                                          <div class="tile is-parent">
                                            <article class="tile is-child categorie-aliment container">
                                                 <a style="display:flex">
                                                        <img :src="require('./assets/svg/aliment.svg')"/>
                                                         <p class="subtitle">Catégories</p>
                                                 </a>
                                            </article>
                                          </div>
                                          <div class="tile is-parent">
                                            <article class="tile is-child categorie-electromenager container">
                                               <a style="display:flex">
                                                        <img :src="require('./assets/svg/electro.svg')"/>
                                                         <p class="subtitle">Catégories</p>
                                                 </a>
                                            </article>
                                          </div>
                                        </div>
                                        <!-- fin de la deuxieme  rangée -->
                                        <!-- troisieme rangée -->
                                        <div class="tile is-ancestor" >
                                          <div class="tile is-parent">
                                            <article class="tile is-child categorie-emplois container">
                                                <a style="display:flex">
                                                        <img :src="require('./assets/svg/emplois.svg')"/>
                                                         <p class="subtitle">Catégories</p>
                                                 </a>
                                            </article>
                                          </div>
                                          <div class="tile is-parent">
                                            <article class="tile is-child categorie-services container">
                                              <a style="display:flex">
                                                        <img :src="require('./assets/svg/services.svg')"/>
                                                         <p class="subtitle">Catégories</p>
                                                 </a>
                                            </article>
                                          </div>
                                          <div class="tile is-parent">
                                            <article class="tile is-child categorie-divers container">
                                             <a style="display:flex">
                                                        <img :src="require('./assets/svg/divers.svg')"/>
                                                         <p class="subtitle">Catégories</p>
                                                 </a>
                                            </article>
                                          </div>
                                        </div>
                                    </div>
                               <div class="column is-5 is-hidden-mobile">
                                  <div class="button">

                                  </div>
                               </div>
                        </div>
                      
                   </section>

                   <!-- Annonces -->
                   <div class="columns">
                     <div class="column is-3">
                          <div class="banniere">

                          </div>
                     </div>
                     <div class="column is-9">
                            <div class="top-annonce box">
                                   <div class="ligne-annonce">
                                           <div class="box">
                                                <h1> ligne 1 carousel 1</h1>
                                           </div>
                                     </div> 
                                     <div class="ligne-annonce">
                                           <div class="box">
                                                <h1> ligne 2 carousel 1</h1>
                                           </div>
                                     </div>     
                             </div>
                            <div class="top-annonce box">
                                   
                                   <div class="ligne-annonce">
                                           <div class="box">
                                                <h1> ligne 1 carousel 1</h1>
                                           </div>
                                     </div> 
                                     <div class="ligne-annonce">
                                           <div class="box">
                                                <h1> ligne 2 carousel 1</h1>
                                           </div>
                                     </div> 

                            </div>
                     </div>
                   </div>

                   <!-- fin annonce -->
                <!-- footer -->
                <footer class="footer">
                   <div class="content has-text-centered">
                   <p>
                  <strong>Bulma</strong> by <a href="https://jgthms.com">Jeremy Thomas</a>. The source code is licensed
                  <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The website content
                  is licensed <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY NC SA 4.0</a>.
                </p>
              </div>
            </footer>
                  
  </div>
  
</template>
<script>
export default {
  
}
</script>

<style lang="scss">
  .navbar-top{
    height: 34px;
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
      height:45px;
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

   


    // mise en page du menu categorie et carousel
    .categorie-annonce{
      height: 310px;
      background: #FFFFFF;
      border-radius: 10px;
      


    }
    .categories-elements{
      border-radius:10px;
      width: 225px;
      height:100px;
    }
    .categorie-electronique{
          background: linear-gradient(129.88deg, #D2F6AC -0.76%, #B8F6D2 103.14%), #FFFFFF;
          border-radius: 10px;
         
    }
    .categorie-transport{
      background: linear-gradient(271.66deg, #AAEEF2 7.73%, #D4F3F2 98.27%), #FFFFFF;
      border-radius: 10px;
    }
    .categorie-immo{
      background: linear-gradient(96.58deg, #C2DEBF 5.17%, #E2F6DE 96.02%), #FFFFFF;
      border-radius: 10px;
    }
    .categorie-vetement{
      background: linear-gradient(270deg, #B3E3F1 0%, #BFEDF2 100%), #FFFFFF;
      border-radius: 10px;
    }
    .categorie-aliment{
      background: linear-gradient(90deg, #FAECE3 0%, #FFD6BF 95.38%), #FFFFFF;
      border-radius: 10px;
    }
    .categorie-electromenager{
      background: linear-gradient(270deg, #BEE8E0 0%, #CFF6EF 100%), #FFFFFF;
      border-radius: 10px;
    }
    .categorie-emplois{
      background: linear-gradient(273.26deg, #C8CDEA 2.92%, #DEE1EE 96.43%), #FFFFFF;
      border-radius: 10px;
    }
    .categorie-services{
      background: linear-gradient(90deg, #F7E4AA 0%, #F6F3C1 100%), #FFFFFF;
      border-radius: 10px;
    }
    .categorie-divers{
      background: linear-gradient(90deg, #F7E4AA 0%, #F6F3C1 100%), #FFFFFF;
      border-radius: 10px;
    }

</style>
