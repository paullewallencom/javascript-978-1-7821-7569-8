var authors = [
   {name: 'Spencer H.', sections: ['Business']},
   {name: 'John C.', sections: ['Movies']},
   {name: 'Rob J.', sections: ['Weather', 'Sports']},
   {name: 'Josh F.', sections: ['Sports']},
   {name: 'Megan M.', sections: ['World']}
];

var sportsAuthors = [];
for (var i = 0; i < authors.length; i++){
   if (authors[i].sections.indexOf('Sports') >= 0) {
      sportsAuthors.push(authors[i].name)
   }
}

sportsAuthors = authors.filter(function(author){
      return author.sections.indexOf('Sports') >= 0;
   }).map(function(sportsAuthor){
      return sportsAuthor.name;
   }); 

// SportsAuthors;
// > [
//    {name: 'Rob J.', sections: ['Weather', 'Sports']},
//    {name: 'Josh F.', sections: ['Sports']}
//   ]
