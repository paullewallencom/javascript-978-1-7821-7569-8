app.get('/insert-task/:data', function(req, res, next){
	var data = {
		timestamp: Date.now(),
		payload: req.params.data
	};

	tasks.enqueue(data);
	next();
});

app.get('/process-task', function(req, res, next){
	var task = tasks.dequeue();
	service.save(task.payload);
	next();
});
