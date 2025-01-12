# OutputBasedJavascript

//compare boolean with String, number, null, undefined

console.log(0<true); //true
console.log(0>true); //false
console.log(0 == true); //false
console.log(0 === true); //false
console.log("------------------");
console.log(1<true); //false
console.log(1>true); //false
console.log(1 == true); //true
console.log(1 === true); //false
console.log("------------------");
console.log(0<false); //false
console.log(0>false); //false
console.log(0 == false); //true
console.log(0 === false); //false
console.log("------------------");
console.log(1<false); //false
console.log(1>false); //true
console.log(1 == false); //false
console.log(1 === false); //false
console.log("------------------");
console.log(2 === false); // false
console.log(2 == false); //false 
//compare with string to boolean 
console.log("------------------");
console.log("1" === true); // false type mismatched
console.log("1" === false); // false type mismatched
console.log("0" === true); // false type mismatched
console.log("0" === false); // false type mismatched
console.log("------------------");
console.log("1" == true); // true type mismatched
console.log("1" == false); // false type mismatched
console.log("0" == true); // false type mismatched
console.log("0" == false); // true type mismatched
console.log("------------------");
console.log("1" == true); // true type mismatched
console.log("1" == false); // false type mismatched
console.log("0" == true); // false type mismatched
console.log("0" == false); // true type mismatched
//Corecion effect will works only with the operands like 
"==","<=",">=","<",">","!="
console.log("------------------");
console.log("true" == true); //can not compare
console.log("true" == false); //can not compare
console.log("false" == true); //can not compare
console.log("false" == false); //can not compare
console.log("------------------");
console.log("1" < true); //false   
console.log("2" > false); //true  
console.log("abc" > true); //false
console.log("------------------");
console.log(null == undefined); // true
console.log(null === undefined); //false
console.log("------------------");
console.log(null == true);
console.log(null == false);
console.log(undefined == true);
console.log(undefined == false);
console.log("------------------");
