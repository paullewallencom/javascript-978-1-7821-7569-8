function linearSearch(data, pred) {
	var item = null;

	data.some(function(row){
		if (pred(row)) {
			item = row;
			return true;
		}

		return false;
	});

	return item;
}

var list = [];
for (var i = 0; i < 10; i++){
	list.push(i);
}

var match = linearSearch(list, function(item){ return item > 5 && item % 2 === 0; });
