var numOfStars = 4;
let space = "_";
let star = " ";
for ( let count = 1 ; count <= numOfStars ; count++) {
  for (let i = 3 ; i >= count ; i--) {
    space = space + "_";
  }
  for (let x = 1 ; x <= count ; x++) {
    star = star + "*" + " ";
  }

  console.log( space + star );
  star = "" ;
  space = "_" ;
}
