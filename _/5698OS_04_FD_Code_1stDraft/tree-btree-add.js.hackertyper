/**
 * @param {*} data
 */
BTree.prototype.add = function(data){
	var node = new Node(data);
	this.length += 1;

	if (this.root === null) {
		return this.root = node;
	}

	var currentNode = this.root;
	var parentNode = null;

	while (currentNode) {
		parentNode = currentNode;

		if (data.id < currentNode.data.id) {
			currentNode = currentNode.left;

			if (currentNode === null) {
				return parentNode.left = node;
			}
		} else {
			currentNode = currentNode.right;

			if (currentNode === null) {
				return parentNode.right = node;
			}
		}
	}
};
