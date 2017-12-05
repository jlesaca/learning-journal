Date: Dec 5 2017,

Yesterday's topics were Mobile First Design, Responsive Web Design, Flexible Layouts, Viewport Metas, and SMACSS. 

Ed and I worked on CodeWars after lecture. 

Answer to replace all dots:

var replaceDots = function(str) {
    return str.replace(/\./g, '-');
  }

Answer to abbreviate-a-two-word-name:

function abbrevName(name){
    var nameArray = name.split(' ');
    console.log(nameArray);
    var fName = nameArray[0].charAt(0).toUpperCase();
    var uName = nameArray[1].charAt(0).toUpperCase();
    return fName + "." + uName;
  }
  
var x = abbrevName("Sam Harris");