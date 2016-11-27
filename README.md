# Angular Directive for Listing accounts and Sharing page 

* Both examples: https://git-demos.herokuapp.com/#/social

## Usage

	<link rel="stylesheet" href="/css/social.min.css">

#### If you use the library, you need to load jQuery and bootstrap the angular app first then social.min.js
#### the angular app definition should be app: ie 
   
    var app = angular.module("name-You-Assigned-To-The-ng-app", []);
    
	<script src="/js/social.min.js"></script>


## use the library to list your profiles.

Then use the directive in your page. 
  
	&lt;button ng-profile={facebook:YOUR_NAME,twitter:YOUR_NAME,google:YOUR_NAME}&gt; connect &lt;/button&gt;
   
   or
   
	&lt;button ng-profile={facebook:YOUR_NAME,twitter: YOUR_NAME,google:YOUR_NAME} animation="launchpadReverse" blur="" &gt; connect &lt;/button&gt;
    
    **optional attributes**
    
    *the animation is for animation the profiles. the default is launchpad reverse* 
    // launchpad, launchpadReverse, slideTop, slideDown, slideLeft, slideRight, chain
    
    *the blur is used to blur the background on show*

**NB: the ng-profile value needs to be an object and not a string containing an object.**
   
## use the library to share pages.

Then use the directive in your page. 
  
	&lt;button ng-share="facebook,twitter,google,pinterest,linkedin"&gt; share &lt;/button&gt;
   
   or
   
	&lt;button ng-share="facebook,twitter,google,pinterest,linkedin" animation="launchpadReverse" blur&gt; share &lt;/button&gt;
    
    optional attributes
    
    the animation is for animation the profiles. the default is launchpad reverse 
    // launchpad, launchpadReverse, slideTop, slideDown, slideLeft, slideRight, chain
    
    the blur is used to blur the background on show
    
**NB: the ng-share value is a comma-separated string of the social platform names.**    
	
	
## Directory and files

    /
		/css
            social.css
			social.min.css
		/images
			social-sprite.png
		/js
			social.js
			social.min.js

## Authors

**Danny Mcwaves**

+ http://twitter.com/DannyMcwaves
+ http://dannymcwaves.herokuapp.com

:sparkles: :+1:			

**(c) danny mcwaves**


