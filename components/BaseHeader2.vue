 <template>
 <nav class="uk-navbar-container uk-margin" uk-navbar>
                        <div class="uk-navbar-left">
                        <div class="uk-width-auto">
						<a href="#" class="uk-logo" title="Portfolio"><img src="denzilla.png" width="170" alt="Logo"></a>
					     </div>

                           

                        </div>
                         <div class="uk-navbar-right">
                          <ul class="uk-navbar-nav">
                                <li class="uk-active"><a href="#">Active</a></li>
                                <li>
                                    <a href="#">Parent</a>
                                    <div class="uk-navbar-dropdown">
                                        <ul class="uk-nav uk-navbar-dropdown-nav">
                                            <li class="uk-active"><a href="#">Active</a></li>
                                             <li class="uk-parent">
                                                <a href="#">Parent</a>
                                                <ul class="uk-nav-sub">
                                                    <li><a href="#">Sub item</a></li>
                                                    <li><a href="#">Sub item</a></li>
                                                </ul>
                                            </li>
                                            <li class="uk-nav-header">Header</li>
                                            <li><a href="#"><span class="uk-margin-small-right" uk-icon="icon: table"></span> Item</a></li>
                                            <li><a href="#"><span class="uk-margin-small-right" uk-icon="icon: thumbnails"></span> Item</a></li>
                                            <li class="uk-nav-divider"></li>
                                            <li><a href="#"><span class="uk-margin-small-right" uk-icon="icon: trash"></span> Item</a></li>
                                        </ul>
                                    </div>
                                </li>
                                <li>
                                    <a href="#">Content</a>
                                    <div class="uk-navbar-dropdown">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</div>
                                </li>
                                <li><a href="#">Item</a></li>
                                <li><a href="#">Item</a></li>
                            </ul>

                         </div>
                    </nav>
    </template>