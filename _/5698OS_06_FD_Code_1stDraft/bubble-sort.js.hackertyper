function bubbleSort(data) {
	var len = data.length;

	do {
		for (var i = 0; i < len - 1; i++) {
			if (data[i] > data[i + 1]) {
				swap(data, i, i + 1);
			}
		}
	} while (len--);

	return data;
}

function swap(arr, indexA, indexB) {
	var tmp = arr[indexA];
	arr[indexA] = arr[indexB];
	arr[indexB] = tmp;
}
