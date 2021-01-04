var colors = new Set();
colors.add('red');
colors.add('blue');
colors.add('green');
colors.add('blue');
colors.add('red');

// Manually iterating
var itr = colors.values();
for (var c = itr.next(); !c.done; c = itr.next()){
   console.log(c.value);
}

// Leaning on for..of loop
for (var c of colors) {
   console.log(c);
}

colors.forEach(function(value, key, set){
   console.log(value);
});

