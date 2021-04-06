> what is graphql
   Graphql is a query language for APIs.
   
  If we look at REST, it comes with fixed data structure of api response, which sometimes leads overfetching or underfetching. 
  Graphql enables declarative data fetching where a client can specify exactly what data is needed from the server.
  
  Instead of multiple endpoints that return fixed data structures, a GraphQL server only exposes a single endpoint and responds with precisely the data a client asked for.
  
> why should we replace REST with graphql: 
  
  mobile usage has been increased, so efficient data loading is needed. Graphql actually minimizes data transfer over the network.
  REST is the standard for designing web apis. stateless servers and structured access to resources.
  
> No more over fetching or under fetching with graphql.
> overfetching: downloading superfluos data.
> underfetching and n+1 problem
> rapid iterations on frontend: as we see that frontend visual changes very frequently this causes some data to be added to an api and some to be removed, 
  this sometimes lead api changes as well. to make it little rapid. we expose  a single endpoint with whole data graph. user can query anything from there.
> Insightful analytics on the backend: you can view the data that can be requested on the backend. and develops an understanding of how the data is used.
> SDL Schema Benefit: Schema is an abstraction of the server's capabilities.This Schema serves as the contract between client and the server to define how a client can access the data.
> Key components: 
  
  
  
  
