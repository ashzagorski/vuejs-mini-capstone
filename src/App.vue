<template>
  <div id="app">
   

    <!-- Search Overlay Menu ----------------------------------------------------->
    <section class="search-overlay-menu">
        <!-- Close Icon -->
        <a href="javascript:void(0)" class="search-overlay-close">
            <!--<i class="ti-close"></i>-->
        </a>
        <!-- End Close Icon -->
        <div class="container">
            <!-- Search Form -->
            <form role="search" id="searchform" action="/search" method="get">
                <label class="h6 normal search-input-label" for="search-query">Enter keywords to Search Product</label>
                <input value="" name="q" type="search" placeholder="Search..." />
                <button type="submit">
                    <i class="ti-search"></i>
                </button>
            </form>
        </div>
    </section>
    <!-- End Search Overlay Menu ------------------------------------------------>

    
        <!--Topbar-->
        <section class="topbar bg-gray">
            <div class="container">
                <div class="row">
                    <div class="col-md-6 mb-3 mb-md-0">
                        <p class="info"><i class="fa fa-headphones left"></i>+630-939-2562</p>
                    </div>
                    <div class="col-md-6 text-lg-right text-md-left">
                        <ul class="links">
                            <li class="">
                                <a href="#" class="dropdown-toggle" data-toggle="dropdown"><i class="fa fa-user left hidden-md-up"></i><span class="hidden-sm-down">My Account</span></a>
                                <div class="dropdown-menu">
                                    <a href="login-register.html" class="dropdown-item">My Account</a>
                                    <a href="#" class="dropdown-item">Order History</a>
                                    <a href="#" class="dropdown-item">Returns</a>
                                    <a href="#" class="dropdown-item">My Wishlist</a>
                                    <a href="checkout.html" class="dropdown-item">Checkout</a>
                                    <div class="dropdown-divider"></div>
                                    <a href="#/login" class="dropdown-item">Login</a>
                                    <a href="login-register.html" class="dropdown-item">Create an Account</a>
                                </div>
                            </li>
          
                            <li>
                                <a href="#">Shipping</a>
                            </li>
                            <li>
                                <a href="#">Information</a>
                            </li>
                            <li>
                                <a href="#/login">Log In</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
        <!-- End Topbar -->

        <!--Header-->
        <header class="header">
            <div class="container">
                <div class="row">
                    <!--Logo-->
                    <div class="col">
                        <a class="logo" href="index.html">
                            <img src="img/" alt="" />
                        </a>
                    </div>

                    <!--Search Bar-->
                    <div class="col-lg-4 d-none d-lg-block">
                        <form class="search-bar">
                            <input class="search-bar-input form-full" type="search" placeholder="Search..." name="search" />
                            <button class="search-bar-icon"><i class="ti-search"></i></button>
                        </form>
                    </div>

                    <!--Toolbar Icon-->
                    <div class="col text-right header-toolbar">
                        <ul>
                            <!--Search Tool Icon-->
                            <li class="search-tool" id="search-overlay-menu-btn">
                                <a><i class="ti-search"></i></a>
                            </li>

                            <!--Account Tool Icon-->
                            <li class="account-tool">
                                <a data-toggle="dropdown"><i class="ti-user"></i></a>
                                <!--Dropdown-->
                                <div class="dropdown-menu dropdown-menu-right">
                                    <a href="#/login" class="dropdown-item"><i class="fa fa-sign-in left"></i>Login</a>
                                    <a href="#/login" class="dropdown-item"><i class="fa fa-user left"></i>Create an Account</a>
                                    <div class="dropdown-divider"></div>
                                    <a href="login-register.html" class="dropdown-item">My Account</a>
                                    <a href="#" class="dropdown-item">Order History</a>
                                    <a href="#" class="dropdown-item">Returns</a>
                                    <a href="#" class="dropdown-item">My Wishlist</a>
                                    <a href="checkout.html" class="dropdown-item">Checkout</a>
                                </div>
                            </li>

                            <!--Cart Tool Icon-->
                            <li id="sidebar_toggle_btn" class="cart-tool">
                                <a><i class="ti-bag"></i><span class="cart-count">2</span></a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Navigation -->
            <div id="sticky_element" class="container-fluid p-0">
                <div class="container">
                    <div class="row">
                        <!--Mobile Memu Button-->
                        <div class="menu-mobile-btn col-12"><span><i class="fa fa-bars left"></i>Menu</span></div>

                        <!--Navigation Menu-->
                        <nav class="nav-menu col-md-12 col-sm-12">
                            <ul>
                                <li class="nav-menu-item">
                                    <a href="#">Home</a>
                                </li>
                                <li class="nav-menu-item">
                                    <a href="shop_grid.html">Tea</a>
                                    <div class="nav-dropdown col2-dropdown">
                                        <div class="row">
                                            <div class="col-lg-6">
                                                <ul>
                                                    <li><span class="dropdown-title">Tea</span></li>
                                                    <li><a href="#">Red Tea</a></li>
                                                    <li><a href="#">Green Tea</a></li>
                                                    <li><a href="#">White Tea</a></li>
                                                    <li><a href="#">Puerth Tea</a></li>
                                                    <li><a href="#">DTH Services</a></li>
                                                </ul>
                                            </div>
                                            <div class="col-lg-6">
                                                <ul>
                                                    <li><span class="dropdown-title">Teaware</span></li>
                                                    <li><a href="#">Gaiwans</a></li>
                                                    <li><a href="#">Cups</a></li>
                                                    <li><a href="#">Pitchers</a></li>
                                                </ul>
                                                <ul>
                                                    <li><span class="dropdown-title">Kombucha</span></li>
                                                    <li><a href="#">Headphones</a></li>
                                                    <li><a href="#">Earphones</a></li>
                                                    <li><a href="#">Headsets with mic</a></li>
                                                </ul>
                                            </div>

                                        </div>
                                    </div>
                                </li>

                                <li class="nav-menu-item">
                                    <a href="shop_list-sidebar_right.html">Teaware</a>
                                    <div class="nav-dropdown col3-dropdown">
                                        <div class="row">
                                            <div class="col-lg-4">
                                                <ul>
                                                    <li><span class="dropdown-title">Kitchen Appliances</span></li>
                                                    <li><a href="#">Gaiwan</a></li>
                                                    <li><a href="#">Cups</a></li>
                                                    <li><a href="#">Pitchers</a></li>
                                                </ul>
                                            </div>
                                        </div>
                                    </div>
                                </li>
                                <li class="nav-menu-item">
                                    <a href="shop_grid.html">Kombucha</a>
                                    <div class="nav-dropdown col3-dropdown center">
                                        <div class="row">
                                            <div class="col-lg-4">
                                                <ul>
                                                    <li><a href="#">Refrigerators</a></li>
                                                    <li><a href="#">Water Purifiers</a></li>
                                                    <li><a href="#">Juicer Mixer Grinders</a></li>
                                                    <li><a href="#">Hand Blenders</a></li>
                                                    <li><a href="#">Water Bottles</a></li>
                                                    <li><a href="#">Ice Trays</a></li>
                                                    <li><a href="#">Food Processors</a></li>
                                                    <li><a href="#">Air Coolers</a></li>
                                                </ul>
                                            </div>
                                        
                                        </div>
                                    </div>
                                </li>
                                <li class="nav-menu-item">
                                    <a href="#/about">About</a>
                                </li>
                               
                                <li class="nav-menu-item">
                                    <a href="#">Blog</a>
                                    <div class="nav-dropdown">
                                        <ul>
                                            <li class="nav-menu-item">
                                                <a href="index.html">Home</a>
                                            </li>
                                            <li class="nav-menu-item">
                                                <a href="shop_grid.html">Shop Grid</a>
                                                <ul class="nav-dropdown-sub left">
                                                    <li><a href="shop_grid.html">Sidebar Left</a></li>
                                                    <li><a href="shop_grid-sidebar_right.html">Sidebar Right</a></li>
                                                    <li><a href="shop_grid-no_sidebar.html">No Sidebar</a></li>
                                                </ul>
                                            </li>
                                            <li class="nav-menu-item">
                                                <a href="shop_list.html">Shop List</a>
                                                <ul class="nav-dropdown-sub left">
                                                    <li><a href="shop_list.html">Sidebar Left</a></li>
                                                    <li><a href="shop_list-sidebar_right.html">Sidebar Right</a></li>
                                                </ul>
                                            </li>
                                            <li class="nav-menu-item">
                                                <a href="product_detail.html">Product Page</a>
                                                <ul class="nav-dropdown-sub left">
                                                    <li><a href="product_detail.html">Default</a></li>
                                                    <li><a href="product_detail-with_sidebar.html">With Sidebar</a></li>
                                                </ul>
                                            </li>
                                            <li class="nav-menu-item">
                                                <a href="cart.html">Cart Page</a>
                                            </li>
                                            <li class="nav-menu-item">
                                                <a href="checkout.html">Checkout Page</a>
                                            </li>
                                            <li class="nav-menu-item">
                                                <a href="login-register.html">Ligin & Register</a>
                                            </li>
                                            <li class="nav-menu-item">
                                                <a href="about.html">About Us</a>
                                            </li>
                                            <li class="nav-menu-item">
                                                <a href="contact.html">Contact Us</a>
                                            </li>
                                            <li class="nav-menu-item">
                                                <a href="portfolio.html">Portfolio</a>
                                            </li>
                                            <li class="nav-menu-item">
                                                <a href="portfolio-single.html">Portfolio Detail</a>
                                            </li>
                                            <li class="nav-menu-item">
                                                <a href="blog.html">Blog</a>
                                                <ul class="nav-dropdown-sub left">
                                                    <li><a href="blog.html">Default</a></li>
                                                    <li><a href="blog-with_sidebar.html">With Sidebar</a></li>
                                                    <li><a href="blog-single.html">Blog Single</a></li>
                                                </ul>
                                            </li>
                                        </ul>
                                    </div>
                                </li>
                            </ul>
                        </nav>
                        <!--End Navigation Menu-->
                    </div>
                </div>
            </div>
            <!-- Navigation -->
        </header>
  <router-view/>
  <footer class="footer">

            <!-- footer Info -->
            <div class="container ptb-15">
                <div class="row">

                    <!-- About -->
                    <div class="col-lg-3 col-md-8 col-sm-12">
                        <div class="footer-block about-us-block">
                            <ul class="footer-social-icon list-none-ib">
                                <li><a href="http://facebook.com/" target="_blank"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
                                <li><a href="https://twitter.com/" target="_blank"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
                                <li><a href="https://www.pinterest.com/" target="_blank"><i class="fa fa-pinterest-p" aria-hidden="true"></i></a></li>
                                <li><a href="https://plus.google.com/" target="_blank"><i class="fa fa-google-plus" aria-hidden="true"></i></a></li>
                                <li><a href="https://www.instagram.com/" target="_blank"><i class="fa fa-instagram" aria-hidden="true"></i></a></li>
                            </ul>
                        </div>
                    </div>

                    <!-- Links -->
                    <div class="col-lg-2 col-md-4 col-sm-4">
                        <div class="footer-block links">
                            <h6>Information</h6>
                            <ul>
                                <li><a href="#">About Us</a></li>
                                <li><a href="#">Delivery Information</a></li>
                                <li><a href="#">Discount</a></li>
                                <li><a href="#">Latest News</a></li>
                                <li><a href="#">Our Sitemap</a></li>
                                <li><a href="#">Terms &amp; Condition</a></li>
                            </ul>
                        </div>
                    </div>

                    <!-- Links -->
                    <div class="col-lg-2 col-md-4 col-sm-4">
                        <div class="footer-block links">
                            <h6>Our Links</h6>
                            <ul>
                                <li><a href="#">About Us</a></li>
                                <li><a href="#">Delivery Information</a></li>
                                <li><a href="#">Discount</a></li>
                                <li><a href="#">Latest News</a></li>
                                <li><a href="#">Our Sitemap</a></li>
                                <li><a href="#">Terms &amp; Condition</a></li>
                            </ul>
                        </div>
                    </div>

                    <!-- Links -->
                    <div class="col-lg-2 col-md-4 col-sm-4">
                        <div class="footer-block links">
                            <h6>Shop</h6>
                            <ul>
                                <li><a href="#">About Us</a></li>
                                <li><a href="#">Delivery Information</a></li>
                                <li><a href="#">Discount</a></li>
                                <li><a href="#">Latest News</a></li>
                                <li><a href="#">Our Sitemap</a></li>
                                <li><a href="#">Terms &amp; Condition</a></li>
                            </ul>
                        </div>
                    </div>


                    <!--Contact-->
                    <div class="col-lg-3 col-md-12 col-sm-12">
                        <div class="footer-block contact-block">
                            <h6>Contact</h6>
                            <ul>
                                <li><i class="fa fa-map-marker" aria-hidden="true"></i>1 Wintergreen Dr. Huntley
                                    <br>
                                    IL 60142, Usa</li>
                                <li><i class="fa fa-envelope" aria-hidden="true"></i><a href="mailto:info@sky.com">info@sky.com</a></li>
                                <li><i class="fa fa-phone" aria-hidden="true"></i>(013) 456789</li>
                                <li><i class="fa fa-fax" aria-hidden="true"></i>89567989</li>
                            </ul>
                        </div>
                    </div>

                </div>
            </div>

            <!-- footer Info -->

            <div class="copyright-bar container-fluid">
                <div class="row">
                    <div class="container">
                        <div class="copyright">
                            <p>&copy; Created by <a>NileForest</a>. MazelShop Responsive Ecommerce Theme 2017</p>
                            <img src="img/payment_logos.png" alt="Mazel Shop" />
                        </div>
                    </div>
                </div>
            </div>

        </footer>
  </div>
</template>

<style>

</style>
