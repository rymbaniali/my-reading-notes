1.What is a ‘Controlled Component’?
	It is an input form elements kept in the state property of components, and only updated with setState(). We can combine the two by making the React state be the “single source of truth”.

2.Should we wait to store the users responses from the form into state when they submit the form OR 
should we update the state with their responses as soon as they enter them? Why.
	With a controlled component, the input’s value is always driven by the React state. While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers.

3.How do we target what the user is entering if we have an event handler on an input field?
	Using event.target.name for the input field

4.Why would we use a ternary operator?
	to simplify the code.

5.Rewrite the following statement using a ternary statement:
	 if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

	(x ===y)? console.log('true'):console.log('false');