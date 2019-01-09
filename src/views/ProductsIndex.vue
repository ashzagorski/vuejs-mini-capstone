<template>
  

      <!--Page Content -->
            <section class="content-page">
                <div class="container">
                    <div class="row">
                        <!--Sidebar-->
                        <div class="sidebar-container col-lg-3">
                            

                            <!-- Filter By Price -->
                            <div class="widget-sidebar">
                                <h5 class="widget-title">Filter By Price</h5>
                                <form class="widget-content" method="get" action="#">
                                    <div class="price-range-amount">
                                        <input id="price_range_min" name="price_range_min" value="" data-min="140" placeholder="Min price" style="display: none;" type="text">
                                        <input id="price_range_max" name="price_range_max" value="" data-max="1100" placeholder="Max price" style="display: none;" type="text">
                                        <div id="price-range-from-to">
                                        </div>
                                    </div>
                                    <div class="price-range-slider"></div>

                                    <button class="btn" type="submit">Filter</button>
                                </form>
                            </div>
                            <!-- End Filter By Price -->

                            <!-- Filter By Color -->
                            <div class="widget-sidebar widget-filter-color">
                                <h5 class="widget-title">Filter By Color</h5>
                                <ul class="widget-content">
                                    <li>
                                        <a href="#">
                                            <div class="filter-color-switcher"><span style="background-color: #ff4040"></span></div>
                                            Red</a>
                                        <span class="color-count">(9)</span>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <div class="filter-color-switcher"><span style="background-color: #000"></span></div>
                                            Black</a>
                                        <span class="color-count">(112)</span>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <div class="filter-color-switcher"><span style="background-color: #ff9000"></span></div>
                                            Orange</a>
                                        <span class="color-count">(56)</span>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <div class="filter-color-switcher"><span style="background-color: #ffcf3d"></span></div>
                                            Yellow</a>
                                        <span class="color-count">(24)</span>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <div class="filter-color-switcher"><span style="background-color: #55b0da"></span></div>
                                            Blue</a>
                                        <span class="color-count">(18)</span>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <div class="filter-color-switcher"><span style="background-color: #9ada55"></span></div>
                                            Green</a>
                                        <span class="color-count">(72)</span>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <div class="filter-color-switcher"><span style="background-color: #7a463b"></span></div>
                                            Brown</a>
                                        <span class="color-count">(5)</span>
                                    </li>
                                </ul>
                            </div>
                            <!-- End Filter By Color -->

                            <!-- Filter By Brand -->
                            <div class="widget-sidebar widget-filter-brand">
                                <h5 class="widget-title">Brand</h5>
                                <ul class="widget-content">
                                    <li>
                                        <a href="#">Adidas</a>
                                        <span class="color-count">(334)</span>
                                    </li>
                                    <li>
                                        <a href="#">Puma</a>
                                        <span class="color-count">(238)</span>
                                    </li>
                                    <li>
                                        <a href="#">Nike</a>
                                        <span class="color-count">(617)</span>
                                    </li>
                                    <li>
                                        <a href="#">Reebok</a>
                                        <span class="color-count">(262)</span>
                                    </li>
                                    <li>
                                        <a href="#">Asics</a>
                                    </li>
                                </ul>
                            </div>
                            <!-- End Filter By Brand -->

                            <!-- Filter By Tag -->
                            <div class="widget-sidebar widget-filter-tag">
                                <h5 class="widget-title">Popular Tag</h5>
                                <ul class="widget-content">
                                    <li>
                                        <a href="#">Shirt</a>
                                    </li>
                                    <li>
                                        <a href="#">Bag</a>
                                    </li>
                                    <li>
                                        <a href="#">Vintage</a>
                                    </li>
                                    <li>
                                        <a href="#">Sweaters</a>
                                    </li>
                                    <li>
                                        <a href="#">t-shirt</a>
                                    </li>
                                    <li>
                                        <a href="#">white</a>
                                    </li>
                                    <li>
                                        <a href="#">Black</a>
                                    </li>
                                    <li>
                                        <a href="#">New</a>
                                    </li>
                                    <li>
                                        <a href="#">Popular</a>
                                    </li>
                                </ul>
                            </div>
                            <!-- End Filter By Tag -->

                            <!-- Popular Product -->
                            <div class="widget-sidebar alt-widget-sidebar widget-product">
                                <h5 class="widget-title">Popular Product</h5>
                                <ul class="widget-content">
                                    <!--Item-->
                                    <li>
                                        <a class="product-img" href="#">
                                            <img src="img/product-img/product_125470001.jpg" alt="">
                                        </a>
                                        <div class="product-content">
                                            <a class="product-link" href="#">Alpha Block Black Polo Sleem T-Shirt</a>
                                            <div class="star-rating">
                                                <span style="width: 80%;"></span>
                                            </div>
                                            <div class="product-amount">$399.00</div>
                                        </div>
                                    </li>
                                    <!--Item-->
                                    <li>
                                        <a class="product-img" href="#">
                                            <img src="img/product-img/product_125470002.jpg" alt="">
                                        </a>
                                        <div class="product-content">
                                            <a class="product-link" href="#">Red Printed Round Neck T-Shirt</a>
                                            <div class="star-rating">
                                                <span style="width: 80%;"></span>
                                            </div>
                                            <div class="product-amount">$399.00</div>
                                        </div>
                                    </li>
                                    <!--Item-->
                                    <li>
                                        <a class="product-img" href="#">
                                            <img src="img/product-img/product_125470003.jpg" alt="">
                                        </a>
                                        <div class="product-content">
                                            <a class="product-link" href="#">Maroon Solid Henley T-Shirts</a>
                                            <div class="star-rating">
                                                <span style="width: 80%;"></span>
                                            </div>
                                            <div class="product-amount">$399.00</div>
                                        </div>
                                    </li>
                                </ul>
                            </div>
                            <!-- End Popular Product -->

                        </div>
                        <!--End Sidebar-->

                        <!--Product Content -->
                        <div class="col-lg-9">
                            <!-- Page Title -->
                            <div class="list-page-title">
                                <h2>Tea Products</h2>
                            </div>

                            <!--Page Description-->
                        
                            <!-- Product Filter -->
                            <div class="product-filter-content">
                                <form class="product-filter-divider">
                                    <label>{{products.length}} Items</label>
                                </form>
                                <!--Product Sort By-->
                                <form class="product-sort-by">
                                    <label for="short-by">Short By</label>
                                    <select name="short-by" id="short-by" class="nice-select-box">
                                        <option value="default_sorting" selected="selected">Default sorting</option>
                                        <option value="sort_by_popularity">Popularity</option>
                                        <option value="sort_by_average_rating">Average rating</option>
                                        <option value="sort_by_newness">New product</option>
                                        <option value="price_low_to_high">Price: low to high</option>
                                        <option value="price_high_to_low">Price: high to low</option>
                                    </select>
                                </form>

                                <!--Product Show-->
                                <form class="product-show">
                                    <label for="product-show">Show</label>
                                    <select name="product-show" id="product-show" class="nice-select-box">
                                        <option value="12" selected="selected">12</option>
                                        <option value="15">15</option>
                                        <option value="18">18</option>
                                        <option value="21">21</option>
                                        <option value="24">24</option>
                                        <option value="all">Show All</option>
                                    </select>
                                </form>

                                <!--Product List/Grid Icon-->
                                <form class="product-view-switcher">
                                    <label>View</label>
                                    <div class="product-view-icon product-grid-switcher">
                                        <a class="" href="javascript:void(0)"><i class="fa fa-th" aria-hidden="true"></i></a>
                                    </div>
                                    <div class="product-view-icon product-list-switcher product-view-icon-active">
                                        <a class="" href="javascript:void(0)"><i class="fa fa-th-list" aria-hidden="true"></i></a>
                                    </div>
                                </form>

                            </div>

                            <!-- Product -->
                            <div class="row product-list-item product-list-view">
                                <!-- item.1 -->
                                <div class="product-item-element col-sm-6 col-md-6 col-lg-4">
                                    <div class="product-item">
                                        <div class="product-item-img">
                                            <div class="product-item-img-wrap">
                                                <img src="img/product-img/product_125470001.jpg" alt="mazel" />
                                            </div>
                                            <div class="new-label">New</div>
                                            <div class="product-button">
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Cart"><i class="ti-shopping-cart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Whishlist"><i class="ti-heart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Quick View"><i class="ti-eye"></i></a>
                                            </div>
                                        </div>
                                        <div class="product-item-content" v-for="product in products">
                                            <a class="tag">Men Fashion</a>
                                            <a class="product-title" href="product_detail.html">{{product.name}}</a>
                                            <div class="product-rating">
                                                <div class="star-rating">
                                                    <span style="width: 60%;"></span>
                                                </div>
                                                <a href="#" class="product-rating-count"><span class="count">3</span> Reviews</a>
                                            </div>
                                            <p class="product-description">When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic remaining essentially unchanged.</p>
                                            <div class="product-price">$199.00</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- item.2 -->
                                <div class="product-item-element col-sm-6 col-md-6 col-lg-4">
                                    <div class="product-item">
                                        <div class="product-item-img">
                                            <div class="product-item-img-wrap">
                                                <img src="img/product-img/product_125470002.jpg" alt="mazel" />
                                            </div>
                                            <div class="product-button">
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Cart"><i class="ti-shopping-cart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Whishlist"><i class="ti-heart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Quick View"><i class="ti-eye"></i></a>
                                            </div>
                                        </div>
                                        <div class="product-item-content">
                                            <a class="tag">Men Fashion</a>
                                            <a class="product-title" href="product_detail.html">Dcmr Enterprise Beige Analog Watch for Boys</a>
                                            <div class="product-rating">
                                                <div class="star-rating">
                                                    <span style="width: 60%;"></span>
                                                </div>
                                                <a href="#" class="product-rating-count"><span class="count">3</span> Reviews</a>
                                            </div>
                                            <p class="product-description">When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic remaining essentially unchanged.</p>
                                            <div class="product-price"><del>$299.00</del>$199.00</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- item.3 -->
                                <div class="product-item-element col-sm-6 col-md-6 col-lg-4">
                                    <div class="product-item">
                                        <div class="product-item-img">
                                            <div class="product-item-img-wrap">
                                                <img src="img/product-img/product_125470003.jpg" alt="mazel" />
                                            </div>
                                            <div class="sale-label">Sale</div>
                                            <div class="product-button">
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Cart"><i class="ti-shopping-cart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Whishlist"><i class="ti-heart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Quick View"><i class="ti-eye"></i></a>
                                            </div>
                                        </div>
                                        <div class="product-item-content">
                                            <a class="tag">Men Fashion</a>
                                            <a class="product-title" href="product_detail.html">Puma Strike Fashion Iii Idp Gray Running Shoes</a>
                                            <div class="product-rating">
                                                <div class="star-rating">
                                                    <span style="width: 60%;"></span>
                                                </div>
                                                <a href="#" class="product-rating-count"><span class="count">3</span> Reviews</a>
                                            </div>
                                            <p class="product-description">When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic remaining essentially unchanged.</p>
                                            <div class="product-price"><del>$299.00</del>$199.00</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- item.4 -->
                                <div class="product-item-element col-sm-6 col-md-6 col-lg-4">
                                    <div class="product-item">
                                        <div class="product-item-img">
                                            <div class="product-item-img-wrap">
                                                <img src="img/product-img/product_125470004.jpg" alt="mazel" />
                                            </div>
                                            <div class="product-button">
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Cart"><i class="ti-shopping-cart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Whishlist"><i class="ti-heart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Quick View"><i class="ti-eye"></i></a>
                                            </div>
                                        </div>
                                        <div class="product-item-content">
                                            <a class="tag">Men Fashion</a>
                                            <a class="product-title" href="product_detail.html">Mt-G Analog Digital Wrist Watch For Boys</a>
                                            <div class="product-rating">
                                                <div class="star-rating">
                                                    <span style="width: 60%;"></span>
                                                </div>
                                                <a href="#" class="product-rating-count"><span class="count">3</span> Reviews</a>
                                            </div>
                                            <p class="product-description">When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic remaining essentially unchanged.</p>
                                            <div class="product-price"><del>$299.00</del>$199.00<span class="price-discount-label">-33%</span></div>
                                        </div>
                                    </div>
                                </div>

                                <!-- item.5 -->
                                <div class="product-item-element col-sm-6 col-md-6 col-lg-4">
                                    <div class="product-item">
                                        <div class="product-item-img">
                                            <div class="product-item-img-wrap">
                                                <img src="img/product-img/product_125470005.jpg" alt="mazel" />
                                            </div>
                                            <div class="product-button">
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Cart"><i class="ti-shopping-cart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Whishlist"><i class="ti-heart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Quick View"><i class="ti-eye"></i></a>
                                            </div>
                                        </div>
                                        <div class="product-item-content">
                                            <a class="tag">Men Fashion</a>
                                            <a class="product-title" href="product_detail.html">Coolpad Coll (4GB, 32GB) 13MP</a>
                                            <div class="product-rating">
                                                <div class="star-rating">
                                                    <span style="width: 60%;"></span>
                                                </div>
                                                <a href="#" class="product-rating-count"><span class="count">3</span> Reviews</a>
                                            </div>
                                            <p class="product-description">When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic remaining essentially unchanged.</p>
                                            <div class="product-price"><del>$299.00</del>$199.00</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- item.6 -->
                                <div class="product-item-element col-sm-6 col-md-6 col-lg-4">
                                    <div class="product-item">
                                        <div class="product-item-img">
                                            <div class="product-item-img-wrap">
                                                <img src="img/product-img/product_125470001.jpg" alt="mazel" />
                                            </div>
                                            <div class="product-button">
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Cart"><i class="ti-shopping-cart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Whishlist"><i class="ti-heart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Quick View"><i class="ti-eye"></i></a>
                                            </div>
                                        </div>
                                        <div class="product-item-content">
                                            <a class="tag">Men Fashion</a>
                                            <a class="product-title" href="product_detail.html">Coolpad Coll (4GB, 32GB) 13MP</a>
                                            <div class="product-rating">
                                                <div class="star-rating">
                                                    <span style="width: 60%;"></span>
                                                </div>
                                                <a href="#" class="product-rating-count"><span class="count">3</span> Reviews</a>
                                            </div>
                                            <p class="product-description">When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic remaining essentially unchanged.</p>
                                            <div class="product-price"><del>$299.00</del>$199.00</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- item.7 -->
                                <div class="product-item-element col-sm-6 col-md-6 col-lg-4">
                                    <div class="product-item">
                                        <div class="product-item-img">
                                            <div class="product-item-img-wrap">
                                                <img src="img/product-img/product_125470002.jpg" alt="mazel" />
                                            </div>
                                            <div class="product-button">
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Cart"><i class="ti-shopping-cart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Whishlist"><i class="ti-heart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Quick View"><i class="ti-eye"></i></a>
                                            </div>
                                        </div>
                                        <div class="product-item-content">
                                            <a class="tag">Men Fashion</a>
                                            <a class="product-title" href="product_detail.html">Dcmr Enterprise Beige Analog Watch for Boys</a>
                                            <div class="product-rating">
                                                <div class="star-rating">
                                                    <span style="width: 60%;"></span>
                                                </div>
                                                <a href="#" class="product-rating-count"><span class="count">3</span> Reviews</a>
                                            </div>
                                            <p class="product-description">When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic remaining essentially unchanged.</p>
                                            <div class="product-price"><del>$299.00</del>$199.00</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- item.8 -->
                                <div class="product-item-element col-sm-6 col-md-6 col-lg-4">
                                    <div class="product-item">
                                        <div class="product-item-img">
                                            <div class="product-item-img-wrap">
                                                <img src="img/product-img/product_125470003.jpg" alt="mazel" />
                                            </div>
                                            <div class="product-button">
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Cart"><i class="ti-shopping-cart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Whishlist"><i class="ti-heart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Quick View"><i class="ti-eye"></i></a>
                                            </div>
                                        </div>
                                        <div class="product-item-content">
                                            <a class="tag">Men Fashion</a>
                                            <a class="product-title" href="product_detail.html">Puma Strike Fashion Iii Idp Gray Running Shoes</a>
                                            <div class="product-rating">
                                                <div class="star-rating">
                                                    <span style="width: 60%;"></span>
                                                </div>
                                                <a href="#" class="product-rating-count"><span class="count">3</span> Reviews</a>
                                            </div>
                                            <p class="product-description">When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic remaining essentially unchanged.</p>
                                            <div class="product-price"><del>$299.00</del>$199.00</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- item.9 -->
                                <div class="product-item-element col-sm-6 col-md-6 col-lg-4">
                                    <div class="product-item">
                                        <div class="product-item-img">
                                            <div class="product-item-img-wrap">
                                                <img src="img/product-img/product_125470004.jpg" alt="mazel" />
                                            </div>
                                            <div class="product-button">
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Cart"><i class="ti-shopping-cart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Whishlist"><i class="ti-heart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Quick View"><i class="ti-eye"></i></a>
                                            </div>
                                        </div>
                                        <div class="product-item-content">
                                            <a class="tag">Men Fashion</a>
                                            <a class="product-title" href="product_detail.html">Mt-G Analog Digital Wrist Watch For Boys</a>
                                            <div class="product-rating">
                                                <div class="star-rating">
                                                    <span style="width: 60%;"></span>
                                                </div>
                                                <a href="#" class="product-rating-count"><span class="count">3</span> Reviews</a>
                                            </div>
                                            <p class="product-description">When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic remaining essentially unchanged.</p>
                                            <div class="product-price"><del>$299.00</del>$199.00</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- item.10 -->
                                <div class="product-item-element col-sm-6 col-md-6 col-lg-4">
                                    <div class="product-item">
                                        <div class="product-item-img">
                                            <div class="product-item-img-wrap">
                                                <img src="img/product-img/product_125470005.jpg" alt="mazel" />
                                            </div>
                                            <div class="product-button">
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Cart"><i class="ti-shopping-cart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Whishlist"><i class="ti-heart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Quick View"><i class="ti-eye"></i></a>
                                            </div>
                                        </div>
                                        <div class="product-item-content">
                                            <a class="tag">Men Fashion</a>
                                            <a class="product-title" href="product_detail.html">Coolpad Coll (4GB, 32GB) 13MP</a>
                                            <div class="product-rating">
                                                <div class="star-rating">
                                                    <span style="width: 60%;"></span>
                                                </div>
                                                <a href="#" class="product-rating-count"><span class="count">3</span> Reviews</a>
                                            </div>
                                            <p class="product-description">When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic remaining essentially unchanged.</p>
                                            <div class="product-price"><del>$299.00</del>$199.00</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- item.11 -->
                                <div class="product-item-element col-sm-6 col-md-6 col-lg-4">
                                    <div class="product-item">
                                        <div class="product-item-img">
                                            <div class="product-item-img-wrap">
                                                <img src="img/product-img/product_125470002.jpg" alt="mazel" />
                                            </div>
                                            <div class="product-button">
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Cart"><i class="ti-shopping-cart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Whishlist"><i class="ti-heart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Quick View"><i class="ti-eye"></i></a>
                                            </div>
                                        </div>
                                        <div class="product-item-content">
                                            <a class="tag">Men Fashion</a>
                                            <a class="product-title" href="product_detail.html">Dcmr Enterprise Beige Analog Watch for Boys</a>
                                            <div class="product-rating">
                                                <div class="star-rating">
                                                    <span style="width: 60%;"></span>
                                                </div>
                                                <a href="#" class="product-rating-count"><span class="count">3</span> Reviews</a>
                                            </div>
                                            <p class="product-description">When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic remaining essentially unchanged.</p>
                                            <div class="product-price"><del>$299.00</del>$199.00</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- item.12 -->
                                <div class="product-item-element col-sm-6 col-md-6 col-lg-4">
                                    <div class="product-item">
                                        <div class="product-item-img">
                                            <div class="product-item-img-wrap">
                                                <img src="img/product-img/product_125470003.jpg" alt="mazel" />
                                            </div>
                                            <div class="sale-label">Sale</div>
                                            <div class="product-button">
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Cart"><i class="ti-shopping-cart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Whishlist"><i class="ti-heart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Quick View"><i class="ti-eye"></i></a>
                                            </div>
                                        </div>
                                        <div class="product-item-content">
                                            <a class="tag">Men Fashion</a>
                                            <a class="product-title" href="product_detail.html">Puma Strike Fashion Iii Idp Gray Running Shoes</a>
                                            <div class="product-rating">
                                                <div class="star-rating">
                                                    <span style="width: 60%;"></span>
                                                </div>
                                                <a href="#" class="product-rating-count"><span class="count">3</span> Reviews</a>
                                            </div>
                                            <p class="product-description">When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic remaining essentially unchanged.</p>
                                            <div class="product-price"><del>$299.00</del>$199.00</div>
                                        </div>
                                    </div>
                                </div>

                            </div>
                            <!-- End Product -->

                            <!--Pagination-->
                            <div class="pagination-wraper">
                                <p>Showing 1 - 15 of 120 results</p>
                                <div class="pagination">
                                    <ul class="pagination-numbers">
                                        <!--<li>
                                            <a href="#" class="prev page-number"><i class="fa fa-angle-double-left"></i></a>
                                        </li>-->
                                        <li>
                                            <a href="#" class="page-number current">1</a>
                                        </li>
                                        <li>
                                            <a href="#" class="page-number">2</a>
                                        </li>
                                        <li>
                                            <a href="#" class="page-number">3</a>
                                        </li>
                                        <li>
                                            <span class="page-number dots">...</span>
                                        </li>
                                        <li>
                                            <a href="#" class="page-number">29</a>
                                        </li>
                                        <li>
                                            <a href="#" class="next page-number"><i class="fa fa-angle-double-right"></i></a>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                            <!--End Pagination-->

                        </div>
                        <!--End Product Content -->

                    </div>
                </div>
            </section>
            <!--End Page Content -->


</template>

<style>

</style>

<script>
  var axios = require('axios');

export default {
  data: function() {
    return {
      products: [],
    };
  },
  created: function() {

    axios
    .get("http://localhost:3000/api/products")
    .then(response => {
      this.products = response.data;
    });
  },

  methods: {},
  computed: {}
};
</script>
