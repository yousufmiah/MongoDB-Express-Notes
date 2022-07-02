# MongoDB-Express-Notes


### get() Method

`Server side code`

```javascript
app.get("/service", async (req, res) => {
      const result = await testCollection.find().toArray();
      res.send(result);
    });
```
