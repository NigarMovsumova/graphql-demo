<h1>GraphQL Demo Application</h1>

This repository includes 2 samples.
The one in lodash folder fetches data from a predefined list.
The one in file folder fetches it from <strong>db.json</strong> file.

You can use yarn, but commands are provided here are just for npm.

1. Make sure Npm is installed.

2. Install dependencies:
<pre>
npm install --save express express-graphql graphql lodash json-server axios
</pre>

3. Go to folder:

<pre>cd file
OR 
cd lodash </pre>

4. Run json server:
<pre> npm run json:server </pre>

5. Run server.js:

<pre> node server.js </pre>

http://localhost:4000/graphql & http://localhost:3000/ must be up by now.

Use http://localhost:4000/graphql to run your queries. 