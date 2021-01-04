var coords = new Set();
coords.add({x: 10, y: 15});
coords.add({x: 20, y: 16});
coords.add({x: 30, y: 23});
coords.add({x: 40, y: 108});

coords.delete({x: 40, y: 108});
// > false

coords.forEach(function(point){
   if (point.y > 20) {
      coords.delete(point);
      // > true
   }
});
