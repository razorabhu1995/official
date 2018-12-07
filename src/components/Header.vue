<template>
    <div>
         <div class="animationload">
        <div class="loader"></div>
    </div>

    <!-- HEADER
    ============================================= -->
    <header id="header">		
        <div class="navbar navbar-fixed-top">	
            <div class="container">

                <!-- Navigation Bar -->
                <div class="navbar-header">

                    <!-- Responsive Menu Button -->
                    <button type="button" id="nav-toggle" class="navbar-toggle" data-toggle="collapse" data-target="#navigation-menu">
                        <span class="sr-only">Toggle navigation</span> 
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>

                    <!-- Logo Image -->
                    <a class="navbar-brand" href="#"><img src="../assets/img/logo.png" alt="Dverse Corporation Limited" role="banner"></a>

                </div>	<!-- End Navigation Bar -->


                <!-- Navigation Menu -->
                <nav id="navigation-menu" class="collapse navbar-collapse" role="navigation">
                    <!-- <ul class="nav navbar-nav navbar-right" id="cbp-tm-menu">
                         <li><a id="GoToHome" class="selected-nav" href="#slideSide"><?= getTexts("menu", "home"); ?></a></li>							
                         <li><a id="GoToLeonardo" href="#followLeonardo"><?= getTexts("menu", "whoweare"); ?></a></li>	
                         <li><a id="GoToBiomimesis" href="#biomimesis"><?= getTexts("menu", "biomimesis"); ?></a></li>							
                         <li><a id="GoToHydrogen" href="#fuelCell"><?= getTexts("menu", "fuelcell"); ?></a></li>	
                         <li><a id="GoToAI" href="#computer_engineering"><?= getTexts("menu", "ai"); ?></a></li>                            
                         <li>
                             <a id="GoToLanguage" href="#language"><?= getTexts("menu", "lang"); ?></a>
                             <ul class="cbp-tm-submenu">
                                 <li><a href="#"><span style="float: left;width:10em;"> English</span>
                                     <img src="img/icons/flags/32/United-kingdom.png"></a></li>
                                 <li><a href="#"><span style="float: left;width:10em;"> Italian</span>
                                     <img src="img/icons/flags/32/Italy.png"></a></li>
 
                             </ul>
                         </li>
                         <li><a id="GoToContacts" href="#contact-info"><?= getTexts("menu", "contacts"); ?></a></li>
                     </ul>-->
                    <ul class="nav navbar-nav navbar-right" id="cbp-tm-menu">
                        <li><a id="GoToHome" class="selected-nav nav-click" href="#home"><?= getTexts("menu", "home"); ?></a></li>							
                        <li><a id="GoToLeonardo" class="nav-click" href="#dversescience"><?= getTexts("menu", "whoweare"); ?></a></li>	
                        <li><a id="GoToBiomimesis" class="nav-click" href="#biomimesis"><?= getTexts("menu", "biomimesis"); ?></a></li>							
                        <li><a id="GoToHydrogen" class="nav-click" href="#hydrogencells"><?= getTexts("menu", "fuelcell"); ?></a></li>	
                        <li><a id="GoToAI" class="nav-click" href="#computerscience"><?= getTexts("menu", "ai"); ?></a></li>                            
                        <li>
                            <a id="GoToLanguage" href="#language"><?= getTexts("menu", "lang"); ?></a>
                            <ul class="cbp-tm-submenu">
                                <li><a href="#"><span style="float: left;width:10em;"> English</span>
                                        <img src="../assets/img/icons/flags/32/United-kingdom.png"></a></li>
                                <li><a href="#"><span style="float: left;width:10em;"> Italian</span>
                                        <img src="../assets/img/icons/flags/32/Italy.png"></a></li>

                            </ul>
                        </li>
                        <li><a id="GoToContacts" class="nav-click" href="#contact-info"><?= getTexts("menu", "contacts"); ?></a></li>
                    </ul>
                </nav>  <!-- End Navigation Menu -->

            </div>	 <!-- End container -->
        </div>	  <!-- End navbar fixed top  -->		
    </header>	<!-- END HEADER -->

    <div id="content_wrapper">

        <section id="home">

            <!-- SLIDES HOLDER -->
            <div id="slides">
                <ul class="slides-container">
                    <?php
                    for ($i = 1; $i <= SLIDEIMAGES; $i++) {
                        ?>
                        <li>
                            <div class="overlay"></div>
                            <div class="intro-content text-center">
                                <h2><?= getTexts("slides", "slide0" . $i); ?></h2>	
                                <div class="intro_buttons">
                                    <a class="btn btn-theme" href="#"><?= getTexts("slides", "button0" . $i); ?></a>
                                </div>								
                            </div>
                            <img src="../assets/img/slider/<?= getTexts("slides", "img0" . $i); ?>.jpg" alt="<?= getTexts("slides", "button0" . $i); ?>">
                        </li>
                        <?php
                    }
                    ?>
                </ul>

                <!-- SLIDES NAVIGATION -->
                <nav class="slides-navigation">
                    <a href="#" class="next fa fa-angle-right"></a>
                    <a href="#" class="prev fa fa-angle-left"></a>
                </nav>

            </div>	<!-- END SLIDES HOLDER -->

            <!-- SCROLL DOWN MOUSE -->
            <div class="scroll-down">
                <div class="mouse">
                    <span class="fa fa-angle-down"></span>
                </div>
                <span><?= getTexts("GENERAL", "scroll"); ?></span>
            </div>

        </section>
    </div>
    </div>
    
</template>
<script>
export default {
    
}
</script>
