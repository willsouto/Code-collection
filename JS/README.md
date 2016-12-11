Javascript



Console 

imprimir msg:
console.log("msg");

tamanho de uma string:
"test".lenght




Função

function Hello(name){
	return "Hello"+name;
}

console.log(Hello("World"));
alert(Hello("World"));



Converte / Parse

x = parseFloat("15.7")+5;
console.log(x);



Array


	var arr1 = new Array("Red",10,20.3);
	var arr2 = new Array("Red",10,20.3);
	
	document.write("<p>Arr1: "+ arr[0] +"</p>");
	document.write("<p>Arr1: "+ arr[1] +"</p>");
	document.write("<p>Arr1: "+ arr[2] +"</p>");

arr1.length = 2;

//concat array
arr1 = arr1.concat(arr2);
console.log(arr1);

//junta array em uma string
var list = arr1.join(" - ");
console.log(list);

//push
arr1.push("newpush");
console.log(arr1);

//pop
arr1.pop();
console.log(arr1);

//shift = pop inv
arr1.shift();
console.log(arr1);

//unshift = push inv
arr1.unshift("unshift");
console.log(arr1);

//slice
var arrslice = arr1.slice(0,2);
console.log(arrslice);
console.log(arr1);

//splice = substitui e add elementos
arr1.splice(1,2,"A","B","C");
console.log(arr1);

//reverse
arr1.reverse();
console.log(arr1);





