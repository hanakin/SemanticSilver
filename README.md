SemanticSilver
===========

New projet dedicated to the creation of a completely semantic modenized style to be included in future versions of PHPBB. The scope of this project will be handled in several stages. Keep in mind that this is not an inherited style but a replacement of the current default style. The use of moderen front-end workflow tools will be leveraged to enable faster prototyping.


Tools Used
==========
* [HMTL5](http://www.w3.org/html/logo/ "HTML5")
	> We are looking to develop a future proof template one that can and will be extendable for quite awhile so we will be using the porposed HTML5 spec selectors

* [CSS3](http://www.w3.org/Style/CSS/ "CSS3")
	> In order to keep our code progress but also clean, expressive and semantic we need to use the leverage of CSS3 to obsficate the use of classes and ids from our HTML code where it is not inherently needed as well as reduce the ammount of server requests for images. CSS3 is a huge help in this regaurd.

* [HTML5Boilerplate](http://html5boilerplate.com/ "HMTL5Boilerplate")
	> Since we are going to already be leveraging technology that is tried and true with the rest of the software platform then it makes sense that we do so with our theme boilerplate helps us do just that by establishing at the most basic level a well layed out template file structure to adhere to.

* [Normalize.css](http://necolas.github.io/normalize.css/ "Normalize.css")
	> Browser wars are a huge thing in evelopment and their have been many common practices over the yeras to reset all of them to behave the smae. however its usually results in a lot more overhead than is nessecary so by using normalize we focus on fixing the incosistancies. Thus eliviating the need to restablish everything ourselves.

* [Stylus](http://learnboost.github.io/stylus/ "Stylus")
	> Devlopment time is a huge concern these days with anything so if there are anyways to speed up the prototping and creation of files then we should leverage it at least at the development level. That is why when it comes to CSS you need to really rely on a preprocessor to enable the devloper to make broad strokes to handle things rather than millons of little ones.
	
	> The acctual selection of Stylus is due to the framework choice

* [NIB](http://visionmedia.github.io/nib/ "NIB")
	> When it comes to preprocessors for CSS you really need some libraries to utilize when adding vendor prefixes. Thats where NIB comes in

* [JEET](http://jeetframework.com/ "JEET")
	> This was not an easy choice to make. Their are several reasons why Jeet was selected but let me first state what I was looking for in this category. 
	
	> I new that we needed an effective powerful way to introduce two very fundamental aspects to the theme that have been mising prior to now, a grid system & responible layouts. 
	
	> I considered all the options their were. I wanted an option that did not add blot to either the HTML or the CSS. JEET allowed me to do just that. It is a fraework unlike the rest in that it was designed to be used and disgaurded upon final render. 
	
	> It leverages the semantic grid system to handle the grid so that you apply the grid to the CSS selectors rather than to classes in the HTMl thus keeping your html very clean. 
	
	> It also has mixins that make working with media queries extremely powerful and simplitic. The combination of these come together beautifly to provide you with a truely responsive & fluid layout down to IE7


Approach
========
####Step 1: 
Style Guide (Colors/Fonts/Form Elements/Buttons/Look & Feel)

####Step 2: 
HTML/CSS structure coding of a static representation of area51 page by page.

####Step 3: 
Break it up into template files

####Step 4: 
Apply aesthtics

####Step 5: 
Fix template engine to work with new proposed template structure

####Step 6: 
Beta/Approaval