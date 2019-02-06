---
layout: without-banner
title: Shop
---

<div class="storefront-breadcrumb">
  <div class="col-full">
    <nav class="woocommerce-breadcrumb">
      <a href="{{ site.baseurl }}/" onclick="ga('send', 'event', 'Navbar', 'Community links', 'Home');">Home</a>
      <span class="breadcrumb-separator"> / </span>Shop
    </nav>
  </div>
</div>

<section class="shop-container product-section product-categories" aria-label="Product Categories">
  <div class="container">
    {% include shop.html %}
  </div>
</section>
