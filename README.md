# Restaurant-GraphQL
Using GraphQL to query a list of restaurants

## Description
Node.js app that uses GraphQL and runs on port 5500 

### My contribution (index.js)
- Wrote the code in the root to respond to queries and mutations
- Wrote GraphQL queries and mutations listed in GraphQL.txt for others to test and use

## How To Run:
1. Download files locally and put into a folder
2. Navigate to that folder in Terminal and run npm install
3. Once npm install completes, run node index.js
4. Once the application is running locally, open your browser and go to localhost:5500/graphql
5. Have fun writing queries or using the ones provided in GraphQL.txt

## GraphQL:
If you use the queries and mutations I provided in GraphQL.txt, you will need to add Query Variables, such as the ones provided below.
```
{
  "idd": 2,
  "name": "OLDO"
}
```
## Roadmap of future improvements:
-[x] Edit the existing code to use the restaurant's attribute id instead of the restaurant's index in the array

## License Information
Distributed under MIT License  
Please read LICENSE file for further details.
