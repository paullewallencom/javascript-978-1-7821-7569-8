Graph.prototype.addEdge = function(nodeA, nodeB){
	var nA = this.nodes.filter(function(node){
		return node.data.id === nodeA;
	});

	var nB = this.nodes.filter(function(node){
		return node.data.id === nodeB;
	});

	if (nA.length && nB.length) {
		nA[0].neighbors.push(nB[0]);
		nB[0].neighbors.push(nA[0]);
	}
};
