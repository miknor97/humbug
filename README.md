for (var i = 1; i <= 100; i++) {

var output = "";

if (i % 3 == 0) {output += "Hum"; } 
if  (i % 5 == 0) {output += "Bug"; }


if  (output == "") {output = i; }

console.log(output);

}
