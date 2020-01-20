URL: http://localhost:8080/graphql

Examples

##Query

{
  recentPosts(count:3){
    id
    title
    category
  }
}

##Mutation

mutation {
   writePost(title:"test3",text:"test",category:"test",author:"test") {
     id
   }
}