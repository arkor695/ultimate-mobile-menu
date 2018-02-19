# ultimate-mobile-menu
At this point, anyone with a website should know that making sure that website is mobile responsive is more than a suggestion -- it’s a requirement. However, issues can pop up when optimizing a website for mobile. You might struggle to maintain some elements of UX design that you love on a desktop layout. You only have so much space to work with on mobile design, and you’ve also got to include pertinent company information. 
  		  
## Tutorial		  
For detailed instruction's, view Solodev's [How to Make the Ultimate Mobile Menu](https://www.solodev.com/blog/web-design/how-to-make-the-ultimate-mobile-menu.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/5pyq6L99/149/).

## HTML

The tutorial contains the following basic HTML markup.

```
<div class="container">
  <div class="row mt-5">
	  <div class="col-sm-12">
		  <p class="text-center">
		    <a href="https://www.solodev.com" class="btn btn-info btn-lg cta-open">External Link</a> <a href="#" class="btn btn-info btn-lg cta-open">Internal Link</a>
		  </p>
	  </div>
  </div>
</div>

<!-- start modal-->
<div class="modal fade" id="speedbump" role="dialog">
	<div class="modal-dialog">
	  <!-- Modal content-->
	  <div class="modal-content">
		<div class="modal-header">
		  <button type="button" class="close" data-dismiss="modal">&times;</button>
		  <h4 class="modal-title">Notice</h4>
		</div>
		<div class="modal-body">
		  <p>You are now leaving the our website website.</p>
		</div>
		<div class="modal-footer text-center">
		  <button type="button" title="continue" class="btn btn-modal btn-continue" data-dismiss="modal">Continue</button>
		  <button type="button" title="go back" class="btn btn-modal btn-close" data-dismiss="modal">Go Back</button>
		</div>
	  </div>

	</div>
</div>
<!--end modal-->
```

## CSS

All required CSS is contained with external-popup.css

## JavaScript

All required JS is contained with external-popup.js

## External Resources

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js"></script>
```

