# auth---express-node-mongoDB

## Start

<pre>
$ npm install
</pre>

### Add MONGOURI
<pre>
mongoose
  .connect("*mongodUri*", { useNewUrlParser: true })
  .then(() => console.log("MongoDB successfully connected!"))
  .catch((err) => console.log(err));
</pre>



 




