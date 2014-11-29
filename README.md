Divisory_SVG_graph_library
==========================

SVG graphs library, used Snap.svg
It helps you to create beatiful graphs on your web site, used SVG for that. Library doesn`t use jQuery.

Creating new element
====================

For creating element, you must get the DOM element:
›› element = document.getElementById('hereYourElement');

After that, you can paint the graph. For that - create new object of main class, put the options into options-object, and put the array, which consist objects with values, colors and text.
›› radial = new GRAPH (element, {
  		typeOfGraph: 	'arc',    // here you type
  		sizeOfGraph: 	1.5,      // size
  		innerRadius: 	.8,       // inner radius
  		animSpeed: 		200,      // animation speed 
  		animCoef: 		1.05,     // coefficient of animation
  		animType: 		'inout',  // type of animation
  	}, [
  	{
  		value: 75               // value
  		caption: 'Your caption' // caption
  		color: '#787EB3'        // color
  	}
  ]
