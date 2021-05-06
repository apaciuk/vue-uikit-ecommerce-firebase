<template>
<header id="site-head">
			<div class="uk-container uk-container-expand">
				<div class="uk-grid uk-grid-medium uk-flex uk-flex-middle" data-uk-grid>
					<div class="uk-width-auto" id="logo">
						<a href="#" class="uk-logo" title="eCommerce"><img src="denzilla.png" width="150" alt="Logo"></a>
					</div>
					<div class="uk-width-expand">
						<form id="search-form" action="">
							<div class="uk-inline uk-width-1-1">
								<span class="uk-form-icon uk-form-icon-flip" data-uk-icon="icon: search"></span>
								<input class="uk-input uk-width-1-1 search-fld" type="text" placeholder="Type and hit enter" autofocus>
								<a hidden href="#" class="search-filter" data-uk-filter-control="[data-tags*='']">Search</a>
								<a hidden href="#" class="search-filter-all" data-uk-filter-control>Search all</a>
								<a hidden href="#" class="search-filter-none" data-uk-filter-control="[data-empty='']">Filter none</a>
							</div>
						</form>
					</div>
					<div class="uk-width-auto">
						<ul class="uk-subnav" data-uk-margin>
		            <li class="uk-visible@s"><NuxtLink to="/">Home</NuxtLink></li>
							<li class="uk-visible@s"><NuxtLink to="/contact">Contact</NuxtLink></li>
							<li class="uk-visible@s">
								<a href="#" data-uk-icon="icon:heart"></a>
								<div class="drop-nav uk-dropdown" data-uk-dropdown="mode: click; offset: 20;animation: uk-animation-slide-bottom-small; duration: 150">
									<h4 class="uk-margin-small-bottom uk-margin-remove-adjacent">Wishlist</h4>
									<p class="uk-text-small uk-text-muted">My Wishlist</p>
									<hr>
<ul class="uk-nav-default uk-nav-parent-icon" data-uk-nav>
										<li class="uk-nav-header">Wishlist</li>
										<li><a href="#"><span class="uk-margin-small-right" data-uk-icon="icon: table"></span>Wishlist Item</a></li>
										<li><a href="#"><span class="uk-margin-small-right" data-uk-icon="icon: thumbnails"></span>Wishlist Item</a></li>
									    <li><a href="#"><span class="uk-margin-small-right" data-uk-icon="icon: trash"></span>Wishlist Item</a></li>
									</ul>
                                    <hr>
									<a href="#" class="uk-button uk-button-secondary uk-width-1-1">VIEW WISHLIST</a>
									<hr>
									
								</div>
							</li>
							<li class="uk-visible@s">
								<a href="#" data-uk-icon="icon:cart"></a>
								<div class="drop-nav uk-dropdown" data-uk-dropdown="mode: click; offset: 20;animation: uk-animation-slide-bottom-small; duration: 150">
									<h4 class="uk-margin-small-bottom uk-margin-remove-adjacent">Cart.</h4>
									<p class="uk-text-small uk-text-muted">Cart Contents.</p>
									<hr>
<ul class="uk-nav-default uk-nav-parent-icon" data-uk-nav>
										<li class="uk-nav-header">Cart Contents</li>
										<li><a href="#"><span class="uk-margin-small-right" data-uk-icon="icon: table"></span>Cart Item</a></li>
										<li><a href="#"><span class="uk-margin-small-right" data-uk-icon="icon: thumbnails"></span>Cart Item</a></li>
									    <li><a href="#"><span class="uk-margin-small-right" data-uk-icon="icon: trash"></span>Cart Item</a></li>
									</ul>
                                    <hr>
									<a href="#" class="uk-button uk-button-secondary uk-width-1-1">VIEW CART</a>
									<hr>
									
								</div>
							</li>
						<li class="uk-hidden@s"><a data-uk-navbar-toggle-icon data-uk-toggle href="#offcanvas-nav"></a></li>
						</ul>
					</div>
				</div>
			</div>
		</header>
     <!--/HEADER-->
</template>
<script>
export default {
}
</script>
<style scoped>
#site-head {
background-color: #f5f5f5;
}
#logo {
padding-bottom: 6px;
}
</style>
