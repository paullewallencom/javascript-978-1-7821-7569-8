function binarySearch(data, value) {
	while (true) {
		var mid = parseInt(data.length / 2, 10);

		if (value === data[mid]) {
			return data[mid];
		} else if (value > data[mid]) {
			data = data.slice(mid);
		} else if (value < data[mid]) {
			data = data.slice(0, mid);
		}

		if (mid === 0) {
			if (value === data[0]) {
				return data[0];
			}
			return null;
		}
	}
}

var list = [];
for (var i = 0; i < 1000000; i++){
	list.push(i);
}

var val = Math.random() * 10000 | 0;

match = binarySearch(list, val);
