/**
 * @param {number} articleId
 * @param {Array} tags
 */
function saveArticle(articleId, tags){
   var uniqueTags = new Set();
   
   tags.forEach(function tag){
      uniqueTags.add(tag);
   });

   uniqueTags.forEach(function(tag){
       var  tagId = saveTag(tag);
       addTagToArticle(articleId, tagId);
   });
}

