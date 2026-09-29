HTML =>
CSS =>
Tailwind =>
Javascript => 
	JS is a client side scripting language. means it has few things as programming language.
	Js is developed BY Sir Brendon Eich in 1995.
	It is developed in only 10 days.
	First name of JS is mocha.
	second name of Javascript is Livescript.
	Final name is Javascript.
	now JS is a programming language. 
	JS is used to validation and DOM manipulation ,also we can do manipulate the things in cpu using node js.
	
	Javascript is based on OBPL(Object based programming language).
	1.BOM =>Browser Object Model
		Browser OBject Model is used to handle functionalities.
	2.DOM =>Document Object 
		Document OBject Model is used to handle the User Interface(frontend) document related functionalities.
		
	Javascript is a interpreted and Highly case sensitive language.
	It follows the camel case format by Default.
	Ex-: hellWorld,pushkarSingh,getElementById etc.
	
	ECMA => (European Computer Manufacturing Association.)
		In 1997 js officially being Standardise , Called as ECMA Script.
		In 2015 js released its major update known as ES-6 (ECMA Script).
	==> Javascript is a dynamic symantic language.
		or we can called  as losely typed language.
		
	Variables =>
		Variables is a container which is used for storing the values in the memory.
		
		1.var
		2.let
		3.const
	Rule for variable declartion
		1. Variable started with aplhabet or underscore.
		2. Variable can be alpha numeric.
		3. Variables are case sensitive.										
		4. variables cannot be any special character.
	1. var =>
		var is a old type to declare any variable. In var we can do with a
		variable redeclaration, reassign, hoisted, global scope.
		var stored themselves in the window object .
	
	2. let =>
		let is a new type that is added in js in ES-6 (2015).
		With the let we can do only reassign the variable. let has block scope.
		
	3. const =>
		const is a new type that is used to declare variable as constant. 
		In the const we can not reassign ,
		redeclaration , not hoisted. const has blocked scope.
		=> (), [] ,{}
		
	Datatype=>
		Datatype tell us about the which type of data is stored in the variable.
		type=>
		1.primitive Datatype
			-->primitive Datatype are independent.
				1.number
				2.string
				3.boolean
				4.symbol
				5.undefined
				6.null
				7.bigint
			
		2.non primitive Datatype
			-->Non primitive Datatype are that tells us values can be stored as  reference.
			1.Object
				i.object
				ii.array
			2.function
			
Operators=>
	-->Operators are used to perform the operation b/w two operands.
	1.Arithemetic Operators
		(+,-,*,/,%,**)
	2.Assignment Operators
		(=,+=,-=,/=,%=)
	3.Relational Operators
		(<,>,<=,>=,==,===)
	4.Logical Operators
		(&&,||,!)
	5.Bitwise Operators
		(&,|,!,<<,>>)
	6.Increment/Decrement Operators
		(i++,i--,--i,++i)
	7.Ternary Operators
		(condition)?true:false
	8.Special Operators
		(... ,@ ,#)
		
		
Conditional Statements=> 
	Conditional Statements are used to execute the block code on the particular condition.
	It helps to take the decision on the behalf of condition in programming.
		
		1.if 
		2.ladder if
		3.nested if 
		4.switch
		
	Syntax =>
		if(condition){
		Statements
		}else{
		statements
	}
	
	if(a=b){
	console.log("if statements")
	}else{
	console.log("else statements")
	}
	
	falsy=>
		0,false,null,undefined,NaN,Infinite etc.
		
	
Switch => 
	Switch case is used to make a menu driven program .
	Syntax-
		switch (condition){
			case :
				//Statements
				break;
			case :
				//Statements
				break;
			default:
				// Statements
					break;
					
			}
			
Loop control =>
	loop control are used to do a repeatation work.
	1. Entry Control
		Entry control loop are those loop that is check condition first after that execute the block of code.
		
	2. Exit Control
		Exit control loop are those loop that is check the condition after the executing block of code.
		ex- do while
	
Array =>
	Array is a collection of multiple data , data can be any datatype . 
	In the array indexing started from the 0 .
	We can declare array using two types.
	1. Using Literals => []
		Literals are the fastest way to use the array.
		Syntax-
			const ar = [1,"two",true,[],50,"hello"];
			
	2. Using Constructor => new Array()
		Constructor are the old and and it is less faster than Literals.
		Syntax-
			const ar = new Array(1,"two",true,[],50,"hello");
			

String =>
	String is a sequence of characters. In JS we can declare a string using 3 types.
	1.Using ""
	2.Using ''
	3.Using template literals ``
	


Function =>
		Function is a block of code which is used to perform a particular task when it invoked.
		There are two types of functionalities available in Javascript .
			1. Predefined Function 
			2. User defined function :-
				1.	Named function
				2.	Arrow function 
				3.	Anonymous function
				4.	Constructor function
				5.	Immediately Invoked Function Expression
				6.	Closure function
				7.	Callback function
				8.	Higher Order function
	 
	1.Named function:
		ex:- 
			<script>
			//named function
			function sayhello(){
				alert("Hello Guys");
			}
			sayhello();
			</script>
	
	2. Arrow function:
		ex:-
		<script>
		const a => ()=>{
		alert("Hey guys kaise ho")
		}
		a()
		console.log(a)
		</script>
		
	3. Anonymous function :
		ex:-
		<script>
		const b = function(){
		alert("Hey class How are you")
		}
		b();
		</script>
	
	4. Constructor function : Constructor function is a function that is invoked/called itself when a object created 
		ex:- 
		<script>
		function person(a,b){
			this.name = a;
			this.branch = b;
		}
		let a = new person("Himanshu","IT")
		console.log(a);
		</script>
		
	5. Immediately Invoked Function Expression:
		ex:-
			<script>
			(function(){
			console.log("hiii")
			})();
			</script>
			
	6. Closure function :-
		Closure function are those function which remember scope of their parent function after the termination of parent function.
		
ex:-
<script>	
function papaji(){
let rupee = 100;
function main(){
console.log(rupee);
rupee++;
}
main();
main();
main();
main();
}
papaji();
</script>

		7. Callback function:- Callback function is passed as argument to another function
		
		
		
		
Object => 
	Object is a collection of method and properties in js or 
	We can say in another language.
	"Object is a real world entity."
	Method=>
		Method is a function that is written inside the the object.
	Properties=>
		Properties are the key value pair.
	
Ex=>
	const a = {name:"john" , email:"john@gmail.com" }
	
	Types=>
		1. Using Constructor
			Ex->
				const obj = new Object ({name:"abc",age:18})
		2.Using Literals
			const b = {name:"vaibhav",email:"jaiswal@gmial.com"}
			
There are predefined objects available in js 
1.DOM
2.BOM		
--------------------------------------------------------------**DOM**-----------------------------------------------------------------------
DOM =>
	DOM is a object and it is stand for Documnet Object Model.
BOM =>
	
	


Event = >
Something which can happen on the browser is called events.
like => onclick, onload,onmouseover,onmouseout etc.
Types To Implement the event --
	1.Using HTML Attributes
		ex-
		<button onclick="fun()">click</button>
	2.Using Method 
		addEventListener('eventName',callback)