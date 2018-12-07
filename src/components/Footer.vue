<template>
    <div>
        <section id="contact-info">
            <div class="container where_we_are" style="text-align: center">	
                <!-- SECTION TITLE -->				
                <div class="row">
                    <div class="col-sm-12 titlebar">
                        <h3>Our address</h3>
                        <h2>Where you can find us</h2>
                    </div>
                </div>
                <div class="team-member-block clearfix">
                <!-- Office Location -->
                    <div class="team-member-container col-md-4 contact-info text-center triggerAnimation animated" data-animate="bounceIn">
                        <i class="fa fa-map-marker"></i>
                        <h4 class="contact_title">U.S. Location</h4>
                        <p class="contact_description"><strong>DVERSE CORPORATION</strong><br>C/O Science Palace<br>16192 Coastal Highway<br>Lewes<br>DELAWARE<br>19558 {USA}</p>
                    </div>

                    <div class="team-member-container col-md-4 contact-info text-center triggerAnimation animated" data-animate="bounceIn">
                        <i class="fa fa-map-marker"></i>
                        <h4 class="contact_title">EUROPE Location</h4>
                        <p class="contact_description"><strong>DVERSE CORPORATION LTD</strong><br>C/O Spilkin Knight<br>The Street Albury<br>Guildford<br>SURREY<br>GU5 9AE {UK}</p>
                    </div>

                    <!-- Working Hours -->
                    <div class="team-member-container col-md-4 contact-info text-center triggerAnimation animated" data-animate="bounceIn">
                        <i class="fa fa-clock-o"></i>
                        <h4 class="contact_title">Working Hours</h4>
                        <p class="contact_description">Monday - Friday 9:00 - 18:00</p>
                    </div>
                </div>
            </div>	<!-- End container -->
        </section>	   <!-- END CONTACT-INFO -->	



        <!-- GOOGLE MAP
        ============================================= -->	
        <div id="contacts" class="googlemap-wrapper">	

            <div id="map_canvas" class="map-canvas"></div>

        </div>	<!-- END GOOGLE MAP -->



        <!-- CONTACTS
        ============================================= -->
        <section id="contact">
            <div class="container">	


                <!-- SECTION TITLE -->				
                <div class="row">
                    <div class="col-sm-12 titlebar">
                        <h3>Get in touch!</h3>
                        <h2>Send us a message</h2>
                    </div>
                </div>


                <!-- CONTACT FORM -->
                <div class="row">
                    <div class="col-sm-12">

                        <form id="contact-form" action="#" name="contactform" class="row" method="post">

                            <div id="input_name" class="col-md-6">
                                <input type="text" name="first_name" id="name" class="form-control triggerAnimation animated" data-animate="bounceIn" placeholder="Name"> 
                            </div>

                            <div id="input_email" class="col-md-6">
                                <input type="text" name="email" id="email" class="form-control triggerAnimation animated" data-animate="bounceIn" placeholder="Email"> 
                            </div>

                            <div id="input_subject" class="col-md-12">
                                <input type="text" name="subject" id="subject" class="form-control triggerAnimation animated" data-animate="bounceIn" placeholder="Subject"> 
                            </div>

                            <div id="input_message" class="col-md-12">
                                <textarea class="form-control triggerAnimation animated" data-animate="bounceIn" name="message" id="message" rows="6" placeholder="Your Message ..."></textarea>
                            </div>                     

                            <div id="form_btn" class="col-md-12">
                                <!-- ReCaptcha -->
                                <div class="g-recaptcha" data-sitekey="<?= $pubkey; ?>"></div>
                                <!-- Submit Button -->
                                <div class="text-right">
                                    <input type="submit" value="Send" name="act" id="act" class="btn btn-theme triggerAnimation animated" data-animate="bounceIn">
                                </div>
                            </div>

                        </form>

                    </div>		 
                </div>	   <!-- END CONTACT FORM -->	


            </div>	   <!-- End container -->	
        </section>	 <!-- END CONTACTS -->


        <!-- FOOTER
        ============================================= -->
        <footer id="footer">
            <div class="cookie_container">
                <h2><?= getTexts("cookielaw", "title"); ?></h2>
                <p><?= getTexts("cookielaw", "popup"); ?></p>
                <div class="clearfix">
                    <a onclick="return false;" href="javascript:void(0);" class="cookie_close"><?= getTexts("general", "ok"); ?></a>
                    <a href="#" class="cookie_read" data-toggle="modal" data-target="#modal-cookies"><?= getTexts("general", "learnmore"); ?></a>
                </div>
            </div>
            <div class="container">

                <!-- FOOTER COPYRIGHT -->
                <div class="row">						
                    <div id="footer_copyright" class="col-sm-12 text-center">		
                        <p>Copyright <?php echo date("Y"); ?> <span>Dverse Corporation Ltd</span>. All Rights Reserved.</p>
                        <?php include "modal_cookie.php" ?>	

                    </div>
                </div>


                <!-- FOOTER SOCIALS -->
                <div class="row">

                    <div id="footer_socials" class="col-sm-12 text-center">	

                        <div id="contact_icons">																	
                            <ul class="contact-socials clearfix">
                                <li><a class="foo_social ico-facebook" href="#"><i class="fa fa-facebook"></i></a></li>
                                <li><a class="foo_social ico-twitter" href="#"><i class="fa fa-twitter"></i></a></li>	
                                <li><a class="foo_social ico-google-plus" href="#"><i class="fa fa-google-plus"></i></a></li>
                                <li><a class="foo_social ico-behance" href="#"><i class="fa fa-behance"></i></a></li>																								

                                <!--
                                        <li><a class="foo_social ico-dribbble" href="#"><i class="fa fa-dribbble"></i></a></li>									
                                        <li><a class="foo_social ico-pinterest" href="#"><i class="fa fa-pinterest"></i></a></li>		
                                        <li><a class="foo_social ico-linkedin" href="#"><i class="fa fa-linkedin"></i></a></li>
                                        <li><a class="foo_social ico-digg" href="#"><i class="fa fa-digg"></i></a></li>
                                        <li><a class="foo_social ico-deviantart" href="#"><i class="fa fa-deviantart"></i></a></li>
                                        <li><a class="foo_social ico-envelope" href="#"><i class="fa fa-envelope-square"></i></a></li>							
                                        <li><a class="foo_social ico-delicious" href="#"><i class="fa fa-delicious"></i></a></li>
                                        <li><a class="foo_social ico-instagram" href="#"><i class="fa fa-instagram"></i></a></li>
                                        <li><a class="foo_social ico-dropbox" href="#"><i class="fa fa-dropbox"></i></a></li>
                                        <li><a class="foo_social ico-skype" href="#"><i class="fa fa-skype"></i></a></li>									
                                        <li><a class="foo_social ico-youtube" href="#"><i class="fa fa-youtube"></i></a></li>
                                        <li><a class="foo_social ico-tumblr" href="#"><i class="fa fa-tumblr"></i></a></li>
                                        <li><a class="foo_social ico-vimeo" href="#"><i class="fa fa-vimeo-square"></i></a></li>
                                        <li><a class="foo_social ico-flickr" href="#"><i class="fa fa-flickr"></i></a></li>
                                        <li><a class="foo_social ico-github" href="#"><i class="fa fa-github-alt"></i></a></li>
                                        <li><a class="foo_social ico-renren" href="#"><i class="fa fa-renren"></i></a></li>
                                        <li><a class="foo_social ico-vk" href="#"><i class="fa fa-vk"></i></a></li>
                                        <li><a class="foo_social ico-xing" href="#"><i class="fa fa-xing"></i></a></li>
                                        <li><a class="foo_social ico-weibo" href="#"><i class="fa fa-weibo"></i></a></li>
                                        <li><a class="foo_social ico-rss" href="#"><i class="fa fa-rss"></i></a></li>										
                                -->									

                            </ul>
                        </div>

                    </div>	

                </div>	<!-- END FOOTER SOCIALS -->


            </div>	  <!-- End container -->							
        </footer>	<!-- END FOOTER -->	



     </div>
</template>
<script>
export default {
    
}
</script>

