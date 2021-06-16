-Understanding the JavaScript Call Stack


1.What is a ‘call’?
	the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

2.How many ‘calls’ can happen at once?
	one at a time.

3.What does LIFO mean?
	the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

4.Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
	firstFunction().


5.What causes a Stack Overflow?
	A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.


--JavaScript error messages


1.What is a ‘refrence error’?
	When you try to use a variable that is not yet declared.

2.What is a ‘syntax error’?
	 Occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

3.What is a ‘range error’?
	Occurs when manipulate an object with some kind of length and give it an invalid length

4.What is a ‘tyep error’?
	This types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

5.What is a breakpoint?
	Make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values.

6.What does the word ‘debugger’ do in your code?
	 achieved The breakpoint in your code.