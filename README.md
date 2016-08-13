# INNOVOSKIES Repository Log
## Initial Commit to the Project
### 11th August 2016
Initialized the Repository

## Added Video Background with Plugin
### 11th August 2016
I have been looking for a nice plugin, Meh, might as well give Vide plugin a try.
###12th August 2016
#### JS Error free ...!!
Removed, all the errors, added a nice video background plugin, will be adding all the works soon !!

##Added, a new Javascript for Typing effect... Typed.js
###13th August 2016
Typed JS JQuery invocation script

`$("#typed").typed({
    // strings: ["Typed.js is a <strong>jQuery</strong> plugin.", "It <em>types</em> out sentences.", "And then deletes them.", "Try it out!"],
    stringsElement: $('#typed-strings'),
    typeSpeed: 25,
    backDelay: 2500,
    loop: true,
    contentType: 'html', // or text
    // defaults to false for infinite loop
    loopCount: false,
    callback: function(){ foo(); },
    resetCallback: function() { newTyped(); }
});
$(".reset").click(function(){
    $("#typed").typed('reset');
});
});
function newTyped(){ /* A new typed object */ }
function foo(){ console.log("Callback"); }`

Typed JS CSS styles:

`/*Typed.js CSS Script for cursor blink*/
/* code for animated blinking cursor */
.type-wrap{
	/*border: 1px solid red;*/
	display: block;
	width: 100%;
	position: absolute;
	z-index: 10000;
	top: 77%;
	text-align: center;
	/*left: 35%;*/
	font-size: 30px;
	text-transform: uppercase;
	margin: 0;
	color: #26292E;
}
.typed-cursor{
		opacity: 1;
		font-weight: 100;
		-webkit-animation: blink 0.7s infinite;
		-moz-animation: blink 0.7s infinite;
		-ms-animation: blink 0.7s infinite;
		-o-animation: blink 0.7s infinite;
		animation: blink 0.7s infinite;
}
@-keyframes blink{
		0% { opacity:1; }
		50% { opacity:0; }
		100% { opacity:1; }
}
@-webkit-keyframes blink{
		0% { opacity:1; }
		50% { opacity:0; }
		100% { opacity:1; }
}
@-moz-keyframes blink{
		0% { opacity:1; }
		50% { opacity:0; }
		100% { opacity:1; }
}
@-ms-keyframes blink{
		0% { opacity:1; }
		50% { opacity:0; }
		100% { opacity:1; }
}
@-o-keyframes blink{
		0% { opacity:1; }
		50% { opacity:0; }
		100% { opacity:1; }
}`
