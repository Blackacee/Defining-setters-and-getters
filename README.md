# Defining-setters-and-getters

var setValue;
var obj = {};
Object.defineProperty(obj, "objProperty", {
 get: function(){
 return "a value";
 },
 set: function(value){
 setValue = value;
 }
});
