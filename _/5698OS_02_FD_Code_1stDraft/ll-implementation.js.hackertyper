/**
 * @param {*} data
 * @constructor
 */
function Node(data){
	this.data = data;
	this.next = null;
}

/**
 * @constructor
 */
function LinkedList(){
	this.head = null;
	this.tail = null;
	this.length = 0;
}

/**
 * @param {*} data
 */
LinkedList.prototype.add = function(data){
	var node = new Node(data);

	if (this.head === null) {
		this.head = node;
		this.tail = node;
	}

	this.tail.next = node;
	this.tail = node;
	this.length += 1;
	
	return node;
};

/**
 * @param {Node} node
 */
LinkedList.prototype.delete = function(node){
	if (this.length === 1) {
		return false;
	}
	
	if (node instanceof Node) {
		for (var _node = this.head; _node !== null; _node = _node.next) {
			if (_node.next === node) {
				_node.next = node.next;
				this.length -= 1;
				return true;
			}
		}
	} else {
		for (var _node = this.head; _node !== null; _node = _node.next) {
			if (_node.next === this.tail) {
				_node.next = null;
				this.tail = _node;
				this.length -= 1;
				return true;
			}
		}
	}

	return false;
};


/**
 *
 */
LinkedList.prototype.clear = function(){
	this.length = 0;
	this.head = null;
	this.tail = null;
};

/**
 * @param {Node} node
 */
LinkedList.prototype.has = function(node){
	for (var _node = list.head; _node !== null; _node = _node.next) {
		if (_node === node) {
			return true;
		}
	}

	return false;
};

