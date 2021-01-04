var articlesArray = getArticles();
var articlesTree = new Btree();

articlesArray.forEach(function(article){
    articlesTree.add(article);
});

app.get('/article/:articleId', function(req, res){
   var articleId = req.params.articleId;
   var article = articlesTree.find(articleId);
   res.json(article);
});
