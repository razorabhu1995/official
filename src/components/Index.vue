<template>
  <div>
    <app-header></app-header>


    <section id="dversescience">
        <div class="container">
            <!-- SECTION TITLE -->
            <div class="row">
                <div class="col-sm-12 titlebar">
                    <h3>dverse corporation</h3>
                    <h2><?= getTexts("menu", "whoweare"); ?></h2>
                </div>
            </div>
            <!-- TABS HOLDER -->
            <div id="tabs-holder" class="row">
                <!-- TABS -->
                <div class="col-md-7">
                    <!-- Tab Panes -->
                    <div class="tab-content">
                        <!-- TAB #1 -->
                        <div id="tab_1" class="tab-pane active">
                            <!-- Tab #1 Description --><p>
                                </p>
                        </div>	<!-- END TAB #1 -->
                    </div>	<!-- End Tab Panes -->
                </div>	<!-- END TABS -->
                <!-- TABS HOLDER IMAGE -->
                <div class="col-md-5 text-center animated" data-animation="fadeInRight" data-animation-delay="800">
                    <img class="img-responsive" src="../assets/img/thumbs/followingLeonardo.jpg" alt="" />
                </div>
            </div>	<!-- END TABS HOLDER -->
        </div>	  <!-- End container -->
        <div class="scroll-down">
            <div class="mouse">
                <span class="fa fa-angle-down"></span>
            </div>
            <span></span>
        </div>
    </section>	<!-- END ABOUT -->

    <!------------------------------------------------------------------------->

    <section id="history">
        <div class="container">
            <!-- SECTION TITLE -->
            <div class="row">
                <div class="col-sm-12 titlebar">
                    <h2></h2>
                </div>
            </div>
            <!-- HISTORY TIMELINE HOLDER -->
            <div class="row">
                <div class="col-md-12">
                    <!-- TIMELINE -->
                    <div class="timeline">
                        <!-- TIMELINE YEAR -->
                        <div class="timeline-year first text-center">
                            <span>2008</span>
                        </div>
                        <!-- TIMELINE ITEM -->
                        <div class="timeline-item">
                            <div class="col-xs-12 col-md-5 pull-left timeline-item-content animated" data-animation="fadeInLeft" data-animation-delay="400">
                                <!-- History Date  -->
                                <div class="timeline-item-title clearfix">
                                    <h4></h4>
                                </div>
                                <!-- History Date Text  -->
                                <div class="timeline-item-text">
                                    <p></p>
                                </div>
                            </div>
                        </div>	<!-- END HISTORY DATE  -->
                        <!-- TIMELINE YEAR -->
                        <div class="timeline-year text-center animated" data-animation="bounceIn" data-animation-delay="400">
                            <span>2009 </span>
                        </div>
                        <!-- TIMELINE ITEM -->
                        <div class="timeline-item">
                            <div class="col-xs-12 col-md-5 pull-right timeline-item-content animated" data-animation="fadeInRight" data-animation-delay="500">
                                <!-- History Date  -->
                                <div class="timeline-item-title clearfix">
                                    <h4></h4>
                                </div>
                                <!-- History Date Text  -->
                                <div class="timeline-item-text">
                                    <p></p>
                                </div>
                            </div>
                        </div>	<!-- END HISTORY DATE  -->
                        <!-- TIMELINE YEAR -->
                        <div class="timeline-year text-center animated" data-animation="bounceIn" data-animation-delay="550">
                            <span>2012</span>
                        </div>
                        <!-- TIMELINE ITEM -->
                        <div class="timeline-item">
                            <div class="col-xs-12 col-md-5 pull-left timeline-item-content animated" data-animation="fadeInLeft" data-animation-delay="600">
                                <!-- History Date  -->
                                <div class="timeline-item-title clearfix">
                                    <h4></h4>
                                </div>
                                <!-- History Date Text  -->
                                <div class="timeline-item-text">
                                    <p></p>
                                </div>
                            </div>
                        </div>	<!-- END HISTORY DATE  -->
                        <!-- TIMELINE YEAR -->
                        <div class="timeline-year text-center animated" data-animation="bounceIn" data-animation-delay="650">
                            <span>2013</span>
                        </div>
                        <!-- TIMELINE ITEM -->
                        <div class="timeline-item">
                            <div class="col-xs-12 col-md-5 pull-right timeline-item-content animated" data-animation="fadeInRight" data-animation-delay="700">
                                <!-- History Date  -->
                                <div class="timeline-item-title clearfix">
                                    <h4></h4>
                                </div>
                                <!-- History Date Text  -->
                                <div class="timeline-item-text">
                                    <p></p>
                                </div>
                            </div>
                        </div>	<!-- END HISTORY DATE  -->
                        <div class="timeline-year text-center animated" data-animation="bounceIn" data-animation-delay="650">
                            <span>2015 </span>
                        </div>
                        <!-- TIMELINE ITEM -->
                        <div class="timeline-item">
                            <div class="col-xs-12 col-md-5 pull-left timeline-item-content animated" data-animation="fadeInRight" data-animation-delay="700">
                                <!-- History Date  -->
                                <div class="timeline-item-title clearfix">
                                    <h4></h4>
                                </div>
                                <!-- History Date Text  -->
                                <div class="timeline-item-text">
                                    <p></p>
                                </div>
                            </div>
                        </div>  <!-- END HISTORY DATE  -->
                        <!-- TIMELINE YEAR -->
                        <div class="timeline-year last text-center animated" data-animation="bounceIn" data-animation-delay="750">
                            <span><?= getTexts("general", "now"); ?></span>
                        </div>
                    </div>	<!-- END TIMELINE -->
                </div>
            </div>	<!-- END HISTORY TIMELINE HOLDER -->
        </div>	  <!-- End container -->
    </section>	<!-- END HISTORY -->

    <!------------------------------------------------------------------------->

    <section id="team">
        <div class="container">
            <!-- SECTION TITLE -->
            <div class="row">
                <div class="col-sm-12 titlebar">
                    <h3><?= getTexts("SCIENTISTS", "TITLE"); ?></h3>
                    <h2><?= getTexts("SCIENTISTS", "SUBTITLE"); ?></h2>
                </div>
            </div>
           <!-- TEAM MEMBERS HOLDER -->
            <div class="row team_members_wrapper">
                <!-- TEAM MEMBER #1 -->
				<div class="col-sm-6 clearfix nopad-right">
					<div class="col-xs-6 col-sm-6  animated" data-animation="fadeInRight" data-animation-delay="500">
						<div class="team-member text-center">
							<!-- Team Member Photo  -->
							<div class="img-block">
								<img class="img-responsive" src="../assets/img/thumbs/eiichiro_kowada.jpg" alt="team_foto" >
							</div>
							<!-- Team Member Meta  -->
							<div class="team-img-meta">
								<h5>Eiichiro prof. Kowada</h5>
								<h6><?= getTexts("SCIENTISTS", "H_SCIENTIST"); ?></h6>
								<p><?= getTexts("SCIENTISTS", "SCIENTIST01"); ?></p>
							</div>
							<!-- Team Member Social Icons  -->
							<div class="team-socials">
								<ul class="team-member-socials clearfix">

											<li><a class="page_social ico_facebook" href="#"><i class="fa fa-facebook"></i></a></li>
											<li><a class="page_social ico_twitter" href="#"><i class="fa fa-twitter"></i></a></li>
											<li><a class="page_social ico_google_plus" href="#"><i class="fa fa-google-plus"></i></a></li>
											<li><a class="page_social ico_behance" href="#"><i class="fa fa-behance"></i></a></li>
											<li><a class="page_social ico_linkedin" href="#"><i class="fa fa-linkedin"></i></a></li>
											<li><a class="page_social ico_digg" href="#"><i class="fa fa-digg"></i></a></li>
											<li><a class="page_social ico_deviantart" href="#"><i class="fa fa-deviantart"></i></a></li>
											<li><a class="page_social ico_envelope" href="#"><i class="fa fa-envelope-square"></i></a></li>
											<li><a class="page_social ico_delicious" href="#"><i class="fa fa-delicious"></i></a></li>
											<li><a class="page_social ico_dribbble" href="#"><i class="fa fa-dribbble"></i></a></li>
											<li><a class="page_social ico_instagram" href="#"><i class="fa fa-instagram"></i></a></li>
											<li><a class="page_social ico_pinterest" href="#"><i class="fa fa-pinterest"></i></a></li>
											<li><a class="page_social ico_dropbox" href="#"><i class="fa fa-dropbox"></i></a></li>
											<li><a class="page_social ico_skype" href="#"><i class="fa fa-skype"></i></a></li>
											<li><a class="page_social ico_youtube" href="#"><i class="fa fa-youtube"></i></a></li>
											<li><a class="page_social ico_tumblr" href="#"><i class="fa fa-tumblr"></i></a></li>
											<li><a class="page_social ico_vimeo" href="#"><i class="fa fa-vimeo-square"></i></a></li>
											<li><a class="page_social ico_flickr" href="#"><i class="fa fa-flickr"></i></a></li>
											<li><a class="page_social ico_github" href="#"><i class="fa fa-github-alt"></i></a></li>
											<li><a class="page_social ico_renren" href="#"><i class="fa fa-renren"></i></a></li>
											<li><a class="page_social ico_vk" href="#"><i class="fa fa-vk"></i></a></li>
											<li><a class="page_social ico_xing" href="#"><i class="fa fa-xing"></i></a></li>
											<li><a class="page_social ico_weibo" href="#"><i class="fa fa-weibo"></i></a></li>
											<li><a class="page_social ico_rss" href="#"><i class="fa fa-rss"></i></a></li>

								</ul>
							</div>

						</div>
					</div>	<!-- END TEAM MEMBER #1 -->

					<!-- TEAM MEMBER #2 -->
					<div class="col-xs-6 col-sm-6  animated" data-animation="fadeInLeft" data-animation-delay="500">
						<div class="team-member text-center">
							<!-- Team Member Photo  -->
							<div class="img-block">
								<img class="img-responsive" src="../assets/img/thumbs/norman_waters.jpg" alt="team_foto" >
							</div>
							<!-- Team Member Meta  -->
							<div class="team-img-meta">
								<h5>Norman dr. Waters</h5>
								<h6><?= getTexts("SCIENTISTS", "MATHEMATICS"); ?></h6>
								<p><?= getTexts("SCIENTISTS", "SCIENTIST02"); ?></p>
							</div>
						</div>
					</div>	<!-- END TEAM MEMBER #2 -->
				</div>
				<div class="clearfix col-sm-6 nopad-left">
                <!-- TEAM MEMBER #3 -->
					<div class="col-xs-6 col-sm-6  animated" data-animation="fadeInRight" data-animation-delay="800">
						<div class="team-member text-center">

							<!-- Team Member Photo  -->
							<div class="img-block">
								<img class="img-responsive" src="../assets/img/thumbs/mirko_superti.jpg" alt="team_foto" >
							</div>
							<!-- Team Member Meta  -->
							<div class="team-img-meta">
								<h5>Mirko dr. Superti</h5>
								<h6><?= getTexts("SCIENTISTS", "T_SCIENTIST"); ?></h6>
								<p><?= getTexts("SCIENTISTS", "SCIENTIST03"); ?></p>
							</div>
						</div>
					</div>	<!-- END TEAM MEMBER #3 -->

					<!-- TEAM MEMBER #4 -->
					<div class="col-xs-6 col-sm-6  animated" data-animation="fadeInLeft" data-animation-delay="800">
						<div class="team-member text-center">
							<!-- Team Member Photo  -->
							<div class="img-block">
								<img class="img-responsive" src="../assets/img/thumbs/david_smith.jpg" alt="team_foto" >
							</div>
							<!-- Team Member Meta  -->
							<div class="team-img-meta">
								<h5>David eng. Smith</h5>
								<h6><?= getTexts("SCIENTISTS", "ENGINEER"); ?></h6>
								<p><?= getTexts("SCIENTISTS", "SCIENTIST04"); ?></p>
							</div>
						</div>
					</div>	<!-- END TEAM MEMBER #4 -->
				</div>
            </div>	<!-- END TEAM MEMBERS HOLDER -->
        </div>	  <!-- End container -->
    </section>	<!-- END TEAM -->


    <!---------------------------------------------------------------------------->

    <section id="biomimesis">
        <div class="container">
            <!-- SECTION TITLE -->
            <div class="row">
                <div class="col-sm-12 titlebar">
                    <h3>DVERSE CORPORATION</h3>
                    <h2><?= getTexts("menu", "biomimesis"); ?></h2>
                </div>
            </div>
            <!-- TABS HOLDER -->
            <div id="tabs-holder" class="row">
                <!-- TABS -->
                <div class="col-md-7">
                    <!-- Tab Panes -->
                    <div class="tab-content">
                        <!-- TAB #1 -->
                        <div id="tab_1" class="tab-pane active">
                            <!-- Tab #1 Description --><p>></p>
                                <?= getTexts("biomimesis", "article"); ?>
                        </div>	<!-- END TAB #1 -->
                    </div>	<!-- End Tab Panes -->
                </div>	<!-- END TABS -->
                <!-- TABS HOLDER IMAGE -->
                <div class="col-md-5 text-center animated" data-animation="fadeInRight" data-animation-delay="800">
                    <img class="img-responsive" src="../assets/img/thumbs/gecko_engineering.png" alt="<?= getTexts("menu", "biomimesis"); ?>" />
                </div>
            </div>	<!-- END TABS HOLDER -->
        </div>	  <!-- End container -->
        <div class="scroll-down">
            <div class="mouse">
                <span class="fa fa-angle-down"></span>
            </div>
            <span><?= getTexts("GENERAL", "scroll"); ?></span>
        </div>
    </section>	<!-- END FEATURES -->

    <!------------------------------------------------------------------------->

    <div id="statistic_banner">
        <div class="container">
            <!-- SECTION TITLE -->
            <div class="row">
                <div class="col-sm-12 titlebar">
                    <h3><?= getTexts("MENU", "BIOMIMESIS"); ?></h3>
                    <h2><?= getTexts("GENERAL", "STATISTICS"); ?></h2>
                </div>
            </div>
            <!-- STATISTIC HOLDER -->
            <div id="statistic-holder" class="row">
                <!-- STATISTIC BLOCK -->
                <div class="col-xs-3 col-sm-3 col-md-3 statistic-block animated" data-animation="bounceIn" data-animation-delay="300">
                    <div class="statistic-number">112</div>
                    <div class="statistic-text"><?= getTexts("GENERAL", "HAPPYCLIENTS"); ?></div>
                </div>
                <!-- STATISTIC BLOCK -->
                <div class="col-xs-3 col-sm-3 col-md-3 statistic-block animated" data-animation="bounceIn" data-animation-delay="400">
                    <div class="statistic-number">147</div>
                    <div class="statistic-text"><?= getTexts("GENERAL", "PROJECTSDONE"); ?></div>
                </div>
                <!-- STATISTIC BLOCK -->
                <div class="col-xs-3 col-sm-3 col-md-3 statistic-block animated" data-animation="bounceIn" data-animation-delay="500">
                    <div class="statistic-number">160</div>
                    <div class="statistic-text"><?= getTexts("GENERAL", "DEADLINE"); ?></div>
                </div>
                <!-- STATISTIC BLOCK -->
                <div class="col-xs-3 col-sm-3 col-md-3 statistic-block animated" data-animation="bounceIn" data-animation-delay="600">
                    <div class="statistic-number">18775</div>
                    <div class="statistic-text"><?= getTexts("GENERAL", "COFEE"); ?></div>
                </div>
            </div>	<!-- END STATISTIC HOLDER -->
        </div>	<!-- End container -->
    </div>	<!-- END STATISTIC BANNER -->

    <!----------------------------------------------------------------------------->

    <section id="hydrogencells">
        <div class="container">
            <!-- SECTION TITLE -->
            <div class="row">
                <div class="col-sm-12 titlebar">
                    <h3>dverse corporation</h3>
                    <h2><?= getTexts("menu", "fuelcell"); ?></h2>
                </div>
            </div>
            <!-- TABS HOLDER -->
            <div id="tabs-holder" class="row">
                <!-- TABS -->
                <div class="col-md-7">
                    <!-- Tab Panes -->
                    <div class="tab-content">
                        <!-- TAB #1 -->
                        <div id="tab_1" class="tab-pane active">
                            <!-- Tab #1 Description --><p></p>
                             
                        </div>	<!-- END TAB #1 -->
                    </div>	<!-- End Tab Panes -->
                </div>	<!-- END TABS -->
                <!-- TABS HOLDER IMAGE -->
                <div class="col-md-5 text-center animated" data-animation="fadeInRight" data-animation-delay="800">
                    <img class="img-responsive" src="../assets/img/thumbs/fuelcell.jpg" alt="<?= getTexts("menu", "fuelcell"); ?>" />
                </div>
            </div>	<!-- END TABS HOLDER -->
        </div>	  <!-- End container -->
        <div class="scroll-down">
            <div class="mouse">
                <span class="fa fa-angle-down"></span>
            </div>
            <span></span>
        </div>
    </section>	<!-- END ABOUT -->

    <!---------------------------------------------------------------------------->

    <section id="computerscience">
        <div class="container">
            <!-- SECTION TITLE -->
            <div class="row">
                <div class="col-sm-12 titlebar">
                    <h3>DVERSE CORPORATION</h3>
                    <h2></h2>
                </div>
            </div>
            <!-- TABS HOLDER -->
            <div id="tabs-holder" class="row">
                <!-- TABS -->
                <div class="col-md-7">
                    <!-- Tab Panes -->
                    <div class="tab-content">
                        <!-- TAB #1 -->
                        <div id="tab_1" class="tab-pane active">
                            <!-- Tab #1 Description --><p></p>
                        </div>	<!-- END TAB #1 -->
                    </div>	<!-- End Tab Panes -->
                </div>	<!-- END TABS -->
                <!-- TABS HOLDER IMAGE -->
                <div class="col-md-5 text-center animated" data-animation="fadeInRight" data-animation-delay="800">
                    <img class="img-responsive" src="../assets/img/thumbs/ai.png" alt="<?= getTexts("menu", "ai"); ?>" />
                </div>
            </div>	<!-- END TABS HOLDER -->
        </div>	  <!-- End container -->
        <div class="scroll-down">
            <div class="mouse">
                <span class="fa fa-angle-down"></span>
            </div>
            <span><?= getTexts("GENERAL", "scroll"); ?></span>
        </div>
    </section>	<!-- END FEATURES -->

    <!-- PRICING
    ============================================= -->

      <section id="pricing">
      <div class="container">
      <!-- SECTION TITLE -->
      <div class="row">
      <div class="col-sm-12 titlebar">
      <h3><?= $texts[$lang]['ai']['title']; ?></h3>
      <h2><?= $texts[$lang]['ai']['price']; ?></h2>
      </div>
      </div>
      <!-- PRICING TABLE HOLDER -->
      <div class="row price-row">
      <!-- PRICE PLAN BASIC -->
      <div id="price_1" class="col-xs-6 col-sm-6 col-md-3 animated" data-animation="fadeInRight" data-animation-delay="400">
      <div class="pricing-table text-center">
      <!-- Table Header  -->
      <h3>Basic</h3>
      <!-- Plan Price  -->
      <div class="price">
      <sup>£</sup>
      <span class="color">390</span>
      <inf class="color">/day</inf>
      </div>
      <!-- Plan Features  -->
      <ul class="biomimesis">
      <li>Up to <strong>5 Projects</strong></li>
      <li><strong>5 GB</strong> of Storage</li>
      <li>Up to <strong>100 Users</strong></li>
      <li><strong>10 GB</strong> Bandwidth</li>
      <li><strong>Security Suite</strong></li>
      </ul>
      <!-- Table Button  -->
      <a href="#" class="btn btn-theme">Select Plan</a>
      </div>
      </div>	<!-- END PRICE PLAN BASIC -->
      <!-- PRICE PLAN STANDARD -->
      <div id="price_2" class="col-xs-6 col-sm-6 col-md-3 animated" data-animation="fadeInLeft" data-animation-delay="400">
      <div class="pricing-table text-center">
      <!-- Table Header  -->
      <h3>Standard</h3>
      <!-- Plan Price  -->
      <div class="price">
      <sup>$</sup>
      <span class="color">59</span>
      <sup class="color">99</sup>
      </div>
      <!-- Plan Features  -->
      <ul class="biomimesis">
      <li>Up to <strong>10 Projects</strong></li>
      <li><strong>10 GB</strong> of Storage</li>
      <li>Up to <strong>250 Users</strong></li>
      <li><strong>25 GB</strong> Bandwidth</li>
      <li><strong>Security Suite</strong></li>
      </ul>
      <!-- Table Button  -->
      <a href="#" class="btn btn-theme">Select Plan</a>
      </div>
      </div>	<!-- END PRICE PLAN STANDARD -->
      <!-- PRICE PLAN ADVANCED -->
      <div id="price_3" class="col-xs-6 col-sm-6 col-md-3 animated" data-animation="fadeInRight" data-animation-delay="600">
      <div class="pricing-table text-center highlight">
      <!-- Table Header  -->
      <h3>Advanced</h3>
      <div class="down-arrow"></div>
      <!-- Plan Price  -->
      <div class="price">
      <sup>$</sup>
      <span class="color">99</span>
      <sup class="color">99</sup>
      </div>
      <!-- Plan Features  -->
      <ul class="biomimesis">
      <li><strong>Unlimited Projects</strong></li>
      <li><strong>50 GB</strong> of Storage</li>
      <li>Up to <strong>1000 Users</strong></li>
      <li><strong>100 GB</strong> Bandwidth</li>
      <li><strong>Security Suite</strong></li>
      </ul>
      <!-- Table Button  -->
      <a href="#" class="btn btn-theme">Select Plan</a>
      </div>
      </div>	<!-- END PRICE PLAN ADVANCED -->
      <!-- PRICE PLAN ULTIMATE -->
      <div id="price_4" class="col-xs-6 col-sm-6 col-md-3 animated" data-animation="fadeInLeft" data-animation-delay="600">
      <div class="pricing-table text-center">
      <!-- Table Header  -->
      <h3>Basic</h3>
      <!-- Plan Price  -->
      <div class="price">
      <sup>$</sup>
      <span class="color">129</span>
      <sup class="color">99</sup>
      </div>
      <!-- Plan Features  -->
      <ul class="biomimesis">
      <li><strong>Unlimited Projects</strong></li>
      <li><strong>150 GB</strong> of Storage</li>
      <li><strong>Unlimited</strong></li>
      <li><strong>500 GB</strong> Bandwidth</li>
      <li><strong>Security Suite</strong></li>
      </ul>
      <!-- Table Button  -->
      <a href="#" class="btn btn-theme">Select Plan</a>
      </div>
      </div>	<!-- END PRICE PLAN ULTIMATE -->
      </div>	<!-- End row -->
      </div>	<!-- End container -->
      </section>	 <!-- END PRICING -->


    <!-- CLIENTS
    ============================================= -->

      <section id="clients">
      <div class="container">


      <!-- SECTION TITLE -->
      <div class="row">
      <div class="col-sm-12 ">
      <div class="titlebar">
      <h3>Our best clients</h3>
      <h2>Who love to work with us</h2>
      </div>
      </div>
      </div>


      <!-- CLIENTS CAROUSEL HOLDER -->
      <div id="clients-holder" class="row">
      <div class="col-md-12">


      <!-- CLIENTS CAROUSEL -->
      <div id="our-customers" class="owl-carousel">

      <!-- CLIENT LOGO -->
      <div id="client-logo-1" class="item">
      <img class="img-responsive img-customer" src="../assets/img/thumbs/client-1.png" alt="customer_image">
      </div>

      <!-- CLIENT LOGO -->
      <div id="client-logo-2" class="item">
      <img class="img-responsive img-customer" src="../assets/img/thumbs/client-2.png" alt="customer_image">
      </div>

      <!-- CLIENT LOGO -->
      <div id="client-logo-3" class="item">
      <img class="img-responsive img-customer" src="../assets/img/thumbs/client-3.png" alt="customer_image">
      </div>

      <!-- CLIENT LOGO -->
      <div id="client-logo-4" class="item">
      <img class="img-responsive img-customer" src="../assets/img/thumbs/client-4.png" alt="customer_image">
      </div>

      <!-- CLIENT LOGO -->
      <div id="client-logo-5" class="item">
      <img class="img-responsive img-customer" src="../assets/img/thumbs/client-5.png" alt="customer_image">
      </div>

      <!-- CLIENT LOGO -->
      <div id="client-logo-6" class="item">
      <img class="img-responsive img-customer" src="../assets/img/thumbs/client-6.png" alt="customer_image">
      </div>

      <!-- CLIENT LOGO -->
      <div id="client-logo-7" class="item">
      <img class="img-responsive img-customer" src="../assets/img/thumbs/client-1.png" alt="customer_image">
      </div>

      <!-- CLIENT LOGO -->
      <div id="client-logo-8" class="item">
      <img class="img-responsive img-customer" src="../assets/img/thumbs/client-2.png" alt="customer_image">
      </div>


      </div>	<!-- END CLIENTS CAROUSEL -->

      </div>
      </div>	   <!-- END CLIENTS CAROUSEL HOLDER -->


      <!-- CLIENTS CAROUSEL NAVIGATION -->
      <div class="customNavigation">
      <a class="prev btn btn-theme"><i class="fa fa-angle-left"></i></a>
      <a class="next btn btn-theme"><i class="fa fa-angle-right"></i></a>
      </div>


      </div>	  <!-- End container -->
      </section>	<!-- END CLIENTS -->




    <!-- TESTIMONIALS
    ============================================= -->

      <div id="testimonials">
      <div class="container">


      <!-- SECTION TITLE -->
      <div class="row">
      <div class="col-sm-12 text-center">
      <h3>More than <span class="clients-counter">1000</span> Satisfied Customers</h3>
      </div>
      </div>


      <!-- TESTIMONIALS HOLDER -->
      <div class="row">


      <!-- TESTIMONIAL #1 -->
      <div class="col-sm-4">
      <div class="testimonial text-center animated" data-animation="fadeInUp" data-animation-delay="500">

      <!-- Testimonial Message -->
      <div class="testi-content">
      <p>Maecenas laoreet augue egestas volutpat vulputate fermentum suscipit egestas lobortis magna, sit amet fermentum nisl condimentum mauris nec interdum lectus</p>
      <div class="testi-arrow"></div>
      </div>

      <!-- Testimonial Message Avatar -->
      <div class="client-img">
      <img src="../assets/img/thumbs/member-1.jpg" alt="John Doe">
      </div>

      <!-- Testimonial Message Author -->
      <div class="testi-author">
      <h4>John Doe</h4>
      <span>CEO</span>
      </div>

      </div>
      </div>	<!-- END TESTIMONIAL #1 -->


      <!-- TESTIMONIAL #2 -->
      <div class="col-sm-4">
      <div class="testimonial text-center animated" data-animation="fadeInUp" data-animation-delay="600">

      <!-- Testimonial Message -->
      <div class="testi-content">
      <p>Maecenas laoreet augue egestas volutpat vulputate fermentum suscipit egestas lobortis magna, sit amet fermentum nisl condimentum mauris nec interdum lectus</p>
      <div class="testi-arrow"></div>
      </div>

      <!-- Testimonial Message Avatar -->
      <div class="client-img">
      <img src="../assets/img/thumbs/member-2.jpg" alt="Hannah Brown">
      </div>

      <!-- Testimonial Message Author -->
      <div class="testi-author">
      <h4>Hannah Brown</h4>
      <span>Creative Director</span>
      </div>
      </div>
      </div>	<!-- END TESTIMONIAL #2 -->


      <!-- TESTIMONIAL #3 -->
      <div class="col-sm-4">
      <div class="testimonial text-center animated" data-animation="fadeInUp" data-animation-delay="800">

      <!-- Testimonial Message -->
      <div class="testi-content">
      <p>Maecenas laoreet augue egestas volutpat vulputate fermentum suscipit egestas lobortis magna, sit amet fermentum nisl condimentum mauris nec interdum lectus</p>
      <div class="testi-arrow"></div>
      </div>

      <!-- Testimonial Message Avatar -->
      <div class="client-img">
      <img src="../assets/img/thumbs/member-3.jpg" alt="Jane Doe">
      </div>

      <!-- Testimonial Message Author -->
      <div class="testi-author">
      <h4>Jane Doe</h4>
      <span>Programmer</span>
      </div>
      </div>
      </div>	<!-- END TESTIMONIAL #3 -->


      </div>	<!-- END TESTIMONIALS HOLDER -->


      </div>	 <!-- End container -->
      </div>	   <!-- END TESTIMONIALS -->

    <!------------------------------------------------------------------------->
      <section id="skills">
      <div class="container">
      <!-- SECTION TITLE -->
      <div class="row">
      <div class="col-sm-12 titlebar">
      <h2>Our skills</h2>
      </div>
      </div>
      <!-- SKILLS HOLDER -->
      <div class="row">
      <!-- WEB DESIGN -->
      <div class="col-xs-6 col-sm-3 text-center animated" data-animation="bounceIn" data-animation-delay="300">
      <div class="chart">
      <div class="percentage" data-percent="85">
      <span class="percent"></span>
      </div>
      </div>

      <h4>Design</h4>
      </div>
      <!-- WORDPRESS -->
      <div class="col-xs-6 col-sm-3 text-center animated" data-animation="bounceIn" data-animation-delay="500">
      <div class="chart">
      <div class="percentage" data-percent="57">
      <span class="percent"></span>
      </div>
      </div>

      <h4>WordPress</h4>
      </div>                <!-- JQUERY -->
      <div class="col-xs-6 col-sm-3 text-center animated" data-animation="bounceIn" data-animation-delay="700">
      <div class="chart">
      <div class="percentage" data-percent="74">
      <span class="percent"></span>
      </div>
      </div>
      <h4>jQuery</h4>
      </div>
      <!-- HTML/CSS -->
      <div class="col-xs-6 col-sm-3 text-center animated" data-animation="bounceIn" data-animation-delay="900">
      <div class="chart">
      <div class="percentage" data-percent="92">
      <span class="percent"></span>
      </div>
      </div>
      <h4>HTML/CSS</h4>
      </div>
      </div>	<!-- END SKILLS HOLDER -->
      </div>	  <!-- End container -->
      </section>
   <app-footer></app-footer>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Index",
  components: {
    "app-header": Header,
    "app-footer": Footer
  },
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
