# MongoDB-Express-Notes


# get() Method

````
app.get("/service", async (req, res) => {
      const result = await testCollection.find().toArray();
      res.send(result);
    });
````
