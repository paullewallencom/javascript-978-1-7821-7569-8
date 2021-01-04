article = {
   id: 23465,
   title: 'Some people almost did something',
   author: 'Rodrigo Silveira',
   publish_date: '2015-01-01T10:11:12',
   body: '...'
};

articleArray = getArticles();
articleList = getListFromArray(articleArray);

function insertArticle(article) {
   var head = articleList.head;
   var node = head;
   
   for (var _node = head; _node !== null; _node = _node.next) {
      if (_node.data.author === article.author) {
         node = _node;
         break;
      }
   }

   articleList.add(article, node);
}

