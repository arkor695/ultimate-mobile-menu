# ultimate-mobile-menu
At this point, anyone with a website should know that making sure that website is mobile responsive is more than a suggestion -- it’s a requirement. However, issues can pop up when optimizing a website for mobile. You might struggle to maintain some elements of UX design that you love on a desktop layout. You only have so much space to work with on mobile design, and you’ve also got to include pertinent company information. 
  		  
## Tutorial		  
For detailed instruction's, view Solodev's [How to Make the Ultimate Mobile Menu](https://www.solodev.com/blog/web-design/how-to-make-the-ultimate-mobile-menu.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/5pyq6L99/149/).

## HTML

The tutorial contains the following basic HTML markup.

```
 <div class="navigation">
                <img src="https://www.solodev.com/_/images/solodev-logo-white.png">
            </div>
            <div id="overlay" class="overlay hidden" role="navigation" data-ps-id="0bc2bd66-545d-d7f1-3fdc-e0a9b0992c40">
                <div class="wrap box-wrap">
                  <div class="mobileNav black;">            <div class="box-close box-toggle open2">
                      <a href="#" class="toggle-mobile" aria-label="Menu Toggle">×</a>
                    </div>
                    <div class="box-mobile-menu mobile-menu">
                      <div class="row">
                        <div class="col">
                          <h4><a href="/">Home</a></h4>
                          <ul>
                            <li><a href="https://www.solodev.com/product/create.stml">Product</a></li>
                            <li><a href="https://www.solodev.com/pricing/">Pricing</a></li>
                            <li><a href="https://www.solodev.com/resources/">Resources</a></li>
                            <li><a href="https://www.solodev.com/customers/">Customers</a></li>
                            <li><a href="https://www.solodev.com/blog/">Blog</a></li>
                          </ul>
                        </div>
                        <div class="col">
                          <h4><a href="/about/">About</a></h4>
                          <ul>
                            <li><a href="https://www.solodev.com/product/host.stml">Hosting</a></li>
                            <li><a href="https://www.solodev.com/product/support.stml">Support</a></li>
                            <li><a href="/about/partners.stml">Partners</a></li>
                            <li><a href="https://www.solodev.com/careers/">Careers</a></li>
                            <li><a href="https://www.solodev.com/contact/">Contact Us</a></li>
                          </ul>
                        </div>
                      </div>
                    </div><!--.mobile-menu-->
                  <form class="search-form hidden-xs" action="/search/">
                      <label for="searchBox" class="sr-only">Search</label>              
                      <input id="searchBox" name="q" type="search">
                      <button class="submit" type="submit" value="" aria-label="Search"><i class="fa fa-search" aria-hidden="true">&nbsp;</i></button>
                    </form>
                    <div class="box-social text-center">
                      <ul>
                        <li><a href="https://www.facebook.com/Solodev" aria-label="Facebook"><i class="fab fa-facebook-f text-white" aria-hidden="true">&nbsp;</i></a></li>
                        <li><a href="https://www.linkedin.com/company/solodev" aria-label="LinkedIn" class="fab fa-linkedin-in text-white"></a></li>
                        <li><a href="https://twitter.com/solodev?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor" aria-label="Twitter"><i class="fab fa-twitter text-white" aria-hidden="true">&nbsp;</i></a></li>
                        <li><a href="https://medium.com/@solodev" aria-label="Medium"><i class="fab fa-medium-m text-white" aria-hidden="true">&nbsp;</i></a></li>
                        <li><a href="https://github.com/solodev" aria-label="Github"><i class="fab fa-github text-white" aria-hidden="true">&nbsp;</i></a></li>
                      </ul>
                    </div><!--.box-social-->
                    <div class="box-addres">
                       <p> <img src="https://www.solodev.com/_/images/solodev-logo-stacked.png" class="mx-auto d-block right-nav-logo"></p>
                      <ul class="row">
                      <li class="col-md-12 text-center">
                          800 N. Magnolia Ave, Suite 1400<br>Orlando, FL 32803<br>Phone: 800.859.7656<br><a href="mailto:info@solodev.com">info@solodev.com</a>
                      </li>
                      </ul>
                    </div><!--.box-addres-->
                  </div>
                </div>
              <div class="ps-scrollbar-x-rail" style="left: 0px; bottom: 0px;"><div class="ps-scrollbar-x" tabindex="0" style="left: 0px; width: 0px;"></div></div><div class="ps-scrollbar-y-rail" style="top: 0px; right: 0px;"><div class="ps-scrollbar-y" tabindex="0" style="top: 0px; height: 0px;"></div></div></div>
```

## CSS

All required CSS is contained with mobile-menu.css

## JavaScript

All required JS is contained with mobile-menu.js

## External Resources

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js"></script>
```

