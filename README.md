URL: http://localhost:8080/graphql

Examples

<h2>Query</h2>

{
  recentPosts(count:3){
    id
    title
    category
  }
}

<h2>Mutation</h2>

mutation {
   writePost(title:"test3",text:"test",category:"test",author:"test") {
     id
   }
}
