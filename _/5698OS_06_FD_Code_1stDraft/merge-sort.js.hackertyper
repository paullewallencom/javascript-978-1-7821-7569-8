function mergeSort(data){
	if (data.length < 2) {
		return data;
	}

	var midPoint = Math.round(data.length / 2);
	return merge(mergeSort(data.slice(0, midPoint)), mergeSort(data.slice(midPoint)));
}

function merge(left, right){
	var out = [];

    while (left.length && right.length) {
        out.push(left[0] < right[0] ? left.shift() : right.shift());
    }

    while (left.length) {
        out.push(left.shift());
    }

    while (right.length) {
        out.push(right.shift());
    }

    return out;
}
