<template>
  <div>
    
   
    <!------ Include the above in your HEAD tag ---------->

    <div class="container">
      <nav class="navbar navbar-inverse">
        <div class="navbar-header">
          <button
            class="navbar-toggle"
            type="button"
            data-toggle="collapse"
            data-target=".js-navbar-collapse"
          >
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#">My Store</a>
        </div>

        <div class="collapse navbar-collapse js-navbar-collapse">
          <ul class="nav navbar-nav">
            <li class="dropdown mega-dropdown" @mouseenter="dropdownhover(event)">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown"
                >Men <span class="caret"></span
              ></a>
              <ul class="dropdown-menu mega-dropdown-menu">
                <li class="col-sm-3">
                  <ul>
                    <li class="dropdown-header">Men Collection</li>
                    <div
                      id="menCollection"
                      class="carousel slide"
                      data-ride="carousel"
                    >
                      <div class="carousel-inner">
                        <div class="item active">
                          <a href="#"
                            ><img
                              src="http://placehold.it/254x150/ff3546/f5f5f5/&text=New+Collection"
                              class="img-responsive"
                              alt="product 1"
                          /></a>
                          <h4><small>Summer dress floral prints</small></h4>
                          <button class="btn btn-primary" type="button">
                            49,99 €
                          </button>
                          <button
                            href="#"
                            class="btn btn-default"
                            type="button"
                          >
                            <span class="glyphicon glyphicon-heart"></span> Add
                            to Wishlist
                          </button>
                        </div>
                        <!-- End Item -->
                        <div class="item">
                          <a href="#"
                            ><img
                              src="http://placehold.it/254x150/3498db/f5f5f5/&text=New+Collection"
                              class="img-responsive"
                              alt="product 2"
                          /></a>
                          <h4><small>Gold sandals with shiny touch</small></h4>
                          <button class="btn btn-primary" type="button">
                            9,99 €
                          </button>
                          <button
                            href="#"
                            class="btn btn-default"
                            type="button"
                          >
                            <span class="glyphicon glyphicon-heart"></span> Add
                            to Wishlist
                          </button>
                        </div>
                        <!-- End Item -->
                        <div class="item">
                          <a href="#"
                            ><img
                              src="http://placehold.it/254x150/2ecc71/f5f5f5/&text=New+Collection"
                              class="img-responsive"
                              alt="product 3"
                          /></a>
                          <h4><small>Denin jacket stamped</small></h4>
                          <button class="btn btn-primary" type="button">
                            49,99 €
                          </button>
                          <button
                            href="#"
                            class="btn btn-default"
                            type="button"
                          >
                            <span class="glyphicon glyphicon-heart"></span> Add
                            to Wishlist
                          </button>
                        </div>
                        <!-- End Item -->
                      </div>
                      <!-- End Carousel Inner -->
                      <!-- Controls -->
                      <a
                        class="left carousel-control"
                        href="#menCollection"
                        role="button"
                        data-slide="prev"
                      >
                        <span
                          class="glyphicon glyphicon-chevron-left"
                          aria-hidden="true"
                        ></span>
                        <span class="sr-only">Previous</span>
                      </a>
                      <a
                        class="right carousel-control"
                        href="#menCollection"
                        role="button"
                        data-slide="next"
                      >
                        <span
                          class="glyphicon glyphicon-chevron-right"
                          aria-hidden="true"
                        ></span>
                        <span class="sr-only">Next</span>
                      </a>
                    </div>
                    <!-- /.carousel -->
                    <li class="divider"></li>
                    <li>
                      <a href="#"
                        >View all Collection
                        <span
                          class="glyphicon glyphicon-chevron-right pull-right"
                        ></span
                      ></a>
                    </li>
                  </ul>
                </li>
                <li class="col-sm-3">
                  <ul>
                    <li class="dropdown-header">Features</li>
                    <li><a href="#">Auto Carousel</a></li>
                    <li><a href="#">Carousel Control</a></li>
                    <li><a href="#">Left & Right Navigation</a></li>
                    <li><a href="#">Four Columns Grid</a></li>
                    <li class="divider"></li>
                    <li class="dropdown-header">Fonts</li>
                    <li><a href="#">Glyphicon</a></li>
                    <li><a href="#">Google Fonts</a></li>
                  </ul>
                </li>
                <li class="col-sm-3">
                  <ul>
                    <li class="dropdown-header">Plus</li>
                    <li><a href="#">Navbar Inverse</a></li>
                    <li><a href="#">Pull Right Elements</a></li>
                    <li><a href="#">Coloured Headers</a></li>
                    <li><a href="#">Primary Buttons & Default</a></li>
                  </ul>
                </li>
                <li class="col-sm-3">
                  <ul>
                    <li class="dropdown-header">Much more</li>
                    <li><a href="#">Easy to Customize</a></li>
                    <li><a href="#">Calls to action</a></li>
                    <li><a href="#">Custom Fonts</a></li>
                    <li><a href="#">Slide down on Hover</a></li>
                  </ul>
                </li>
              </ul>
            </li>
            <li class="dropdown mega-dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown"
                >Women <span class="caret"></span
              ></a>
              <ul class="dropdown-menu mega-dropdown-menu">
                <li class="col-sm-3">
                  <ul>
                    <li class="dropdown-header">Features</li>
                    <li><a href="#">Auto Carousel</a></li>
                    <li><a href="#">Carousel Control</a></li>
                    <li><a href="#">Left & Right Navigation</a></li>
                    <li><a href="#">Four Columns Grid</a></li>
                    <li class="divider"></li>
                    <li class="dropdown-header">Fonts</li>
                    <li><a href="#">Glyphicon</a></li>
                    <li><a href="#">Google Fonts</a></li>
                  </ul>
                </li>
                <li class="col-sm-3">
                  <ul>
                    <li class="dropdown-header">Plus</li>
                    <li><a href="#">Navbar Inverse</a></li>
                    <li><a href="#">Pull Right Elements</a></li>
                    <li><a href="#">Coloured Headers</a></li>
                    <li><a href="#">Primary Buttons & Default</a></li>
                  </ul>
                </li>
                <li class="col-sm-3">
                  <ul>
                    <li class="dropdown-header">Much more</li>
                    <li><a href="#">Easy to Customize</a></li>
                    <li><a href="#">Calls to action</a></li>
                    <li><a href="#">Custom Fonts</a></li>
                    <li><a href="#">Slide down on Hover</a></li>
                  </ul>
                </li>
                <li class="col-sm-3">
                  <ul>
                    <li class="dropdown-header">Women Collection</li>
                    <div
                      id="womenCollection"
                      class="carousel slide"
                      data-ride="carousel"
                    >
                      <div class="carousel-inner">
                        <div class="item active">
                          <a href="#"
                            ><img
                              src="http://placehold.it/254x150/3498db/f5f5f5/&text=New+Collection"
                              class="img-responsive"
                              alt="product 1"
                          /></a>
                          <h4><small>Summer dress floral prints</small></h4>
                          <button class="btn btn-primary" type="button">
                            49,99 €
                          </button>
                          <button
                            href="#"
                            class="btn btn-default"
                            type="button"
                          >
                            <span class="glyphicon glyphicon-heart"></span> Add
                            to Wishlist
                          </button>
                        </div>
                        <!-- End Item -->
                        <div class="item">
                          <a href="#"
                            ><img
                              src="http://placehold.it/254x150/ff3546/f5f5f5/&text=New+Collection"
                              class="img-responsive"
                              alt="product 2"
                          /></a>
                          <h4><small>Gold sandals with shiny touch</small></h4>
                          <button class="btn btn-primary" type="button">
                            9,99 €
                          </button>
                          <button
                            href="#"
                            class="btn btn-default"
                            type="button"
                          >
                            <span class="glyphicon glyphicon-heart"></span> Add
                            to Wishlist
                          </button>
                        </div>
                        <!-- End Item -->
                        <div class="item">
                          <a href="#"
                            ><img
                              src="http://placehold.it/254x150/2ecc71/f5f5f5/&text=New+Collection"
                              class="img-responsive"
                              alt="product 3"
                          /></a>
                          <h4><small>Denin jacket stamped</small></h4>
                          <button class="btn btn-primary" type="button">
                            49,99 €
                          </button>
                          <button
                            href="#"
                            class="btn btn-default"
                            type="button"
                          >
                            <span class="glyphicon glyphicon-heart"></span> Add
                            to Wishlist
                          </button>
                        </div>
                        <!-- End Item -->
                      </div>
                      <!-- End Carousel Inner -->
                      <!-- Controls -->
                      <a
                        class="left carousel-control"
                        href="#womenCollection"
                        role="button"
                        data-slide="prev"
                      >
                        <span
                          class="glyphicon glyphicon-chevron-left"
                          aria-hidden="true"
                        ></span>
                        <span class="sr-only">Previous</span>
                      </a>
                      <a
                        class="right carousel-control"
                        href="#womenCollection"
                        role="button"
                        data-slide="next"
                      >
                        <span
                          class="glyphicon glyphicon-chevron-right"
                          aria-hidden="true"
                        ></span>
                        <span class="sr-only">Next</span>
                      </a>
                    </div>
                    <!-- /.carousel -->
                    <li class="divider"></li>
                    <li>
                      <a href="#"
                        >View all Collection
                        <span
                          class="glyphicon glyphicon-chevron-right pull-right"
                        ></span
                      ></a>
                    </li>
                  </ul>
                </li>
              </ul>
            </li>
            <li><a href="#">Store locator</a></li>
          </ul>
          <ul class="nav navbar-nav navbar-right">
            <li class="dropdown">
              <a
                href="#"
                class="dropdown-toggle"
                data-toggle="dropdown"
                role="button"
                aria-expanded="false"
                >My account <span class="caret"></span
              ></a>
              <ul class="dropdown-menu" role="menu">
                <li><a href="#">Action</a></li>
                <li><a href="#">Another action</a></li>
                <li><a href="#">Something else here</a></li>
                <li class="divider"></li>
                <li><a href="#">Separated link</a></li>
              </ul>
            </li>
            <li><a href="#">My cart (0) items</a></li>
          </ul>
        </div>
        <!-- /.nav-collapse -->
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  setup() {
    function dropdownhover($e){
      
      // // document.getElementsByClassName('.dropdown-menu').not('.in .dropdown-menu').stop(true,true).slideDown("400");
      // document.querySelector(".dropdown-menu:not(.in):not(.dropdown-menu)").stostop(true,true).slideDown("400");
      //         document.getElementsByClassName('.dropdown').toggleClass('open');
      console.log("a"+$e);
          
    };
    return{
      dropdownhover
    }
  },
  // $(document).ready(function(){
  //     $(".dropdown").hover(
  //         function() {
  //             $('.dropdown-menu', this).not('.in .dropdown-menu').stop(true,true).slideDown("400");
  //             $(this).toggleClass('open');
  //         },
  //         function() {
  //             $('.dropdown-menu', this).not('.in .dropdown-menu').stop(true,true).slideUp("400");
  //             $(this).toggleClass('open');
  //         }
  //     );
  // });

};
</script>

<style scoped>
  @import url(http://fonts.googleapis.com/css?family=Open+Sans:400,700);
  body {
    font-family: "Open Sans", "sans-serif";
  }
  .mega-dropdown {
    position: static !important;
  }
  .mega-dropdown-menu {
    padding: 20px 0px;
    width: 100%;
    box-shadow: none;
    -webkit-box-shadow: none;
  }
  .mega-dropdown-menu > li > ul {
    padding: 0;
    margin: 0;
  }
  .mega-dropdown-menu > li > ul > li {
    list-style: none;
  }
  .mega-dropdown-menu > li > ul > li > a {
    display: block;
    color: #222;
    padding: 3px 5px;
  }
  .mega-dropdown-menu > li ul > li > a:hover,
  .mega-dropdown-menu > li ul > li > a:focus {
    text-decoration: none;
  }
  .mega-dropdown-menu .dropdown-header {
    font-size: 18px;
    color: #ff3546;
    padding: 5px 60px 5px 5px;
    line-height: 30px;
  }

  .carousel-control {
    width: 30px;
    height: 30px;
    top: -35px;
  }
  .left.carousel-control {
    right: 30px;
    left: inherit;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right {
    font-size: 12px;
    background-color: #fff;
    line-height: 30px;
    text-shadow: none;
    color: #333;
    border: 1px solid #ddd;
  }
</style>
