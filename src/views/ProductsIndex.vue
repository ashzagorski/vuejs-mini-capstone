<template>

   <section class="breadcrumb">
                <div class="container">
                    <div class="row">
                        <div class="col-12">
                            <nav class="breadcrumb-link">
                                <a href="#"><span>Home</span></a>
                            </nav>
                        </div>
                    </div>
                </div>
            </section>
            <!-- Bread Crumb -->
  

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
                                        <span class="color-count">(1)</span>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <div class="filter-color-switcher"><span style="background-color: #000"></span></div>
                                            Black</a>
                                        <span class="color-count">(1)</span>
                                    </li>
                                
                                    <li>
                                        <a href="#">
                                            <div class="filter-color-switcher"><span style="background-color: #ffcf3d"></span></div>
                                            Yellow</a>
                                        <span class="color-count">(1)</span>
                                    </li>
                                 
                                    <li>
                                        <a href="#">
                                            <div class="filter-color-switcher"><span style="background-color: #9ada55"></span></div>
                                            Green</a>
                                        <span class="color-count">(1)</span>
                                    </li>
                                </ul>
                            </div>
                            <!-- End Filter By Color -->


                            <!-- Filter By Tag -->
                            <div class="widget-sidebar widget-filter-tag">
                                <h5 class="widget-title">Popular Tag</h5>
                                <ul class="widget-content">
                                    <li>
                                        <a href="#">Tea</a>
                                    </li>
                                    <li>
                                        <a href="#">Green Tea</a>
                                    </li>
                                    <li>
                                        <a href="#">Cup</a>
                                    </li>
                                    <li>
                                        <a href="#">Kombucha</a>
                                    </li>
                                    <li>
                                        <a href="#">Red Tea</a>
                                    </li>
                                    <li>
                                        <a href="#">White Tea</a>
                                    </li>
                                </ul>
                            </div>
                            <!-- End Filter By Tag -->
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

                                <form class="product-show">
                                    <label for="product-show">Show</label>
                                    <select name="product-show" id="product-show" class="nice-select-box">
                                        <option value="4" selected="selected">{{products.length}}</option>
                                        <option value="3">{{products.length - 1}}</option>
                                        <option value="2">{{products.length - 2}}</option>
                                        <option value="1">{{products.length - 3 }}</option>
                                        <option value="all">Show All</option>
                                    </select>
                                </form>


                            </div>

                            <!-- Product -->
                            <div class="row product-list-item product-list-view" v-for="product in products">
                                <!-- item.1 -->
                                <div class="product-item-element col-sm-6 col-md-6 col-lg-4">
                                    <div class="product-item">
                                        <div class="product-item-img">
                                            <div class="product-item-img-wrap">
                                                <img src="img/red.jpg" alt="mazel" />
                                            </div>
                                            <div class="new-label">New</div>
                                            <div class="product-button">
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Cart"><i class="ti-shopping-cart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Add To Whishlist"><i class="ti-heart"></i></a>
                                                <a href="#" rel="tooltip" data-placement="right" title="Quick View"><i class="ti-eye"></i></a>
                                            </div>
                                        </div>
                                        <div class="product-item-content" >
                                            <a class="tag">Tea</a>
                                            <a class="product-title" href="product_detail.html">{{product.name}}</a>
                                            <div class="product-rating">
                                                <div class="star-rating">
                                                    <span style="width: 60%;"></span>
                                                </div>
                                                <a href="#" class="product-rating-count"><span class="count">3</span> Reviews</a>
                                            </div>
                                            <p class="product-description">{{product.description}}</p>
                                            <div class="product-price">{{product.formatted.price}}</div>
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
