# Fix my code challenge

Fix my code is a new type of project, where we’ll jump into an existing code base and fix it!

Sometime you will know the language, sometime not.

### 0. Server status

I just started a new Flask project and the first thing I’m putting in place is a route for the status of my API (super important for a load balancer implementation).
```bash
 curl -XGET http://0.0.0.0:5000/api/v1/status
{
  "error": "Not found"
}
```
