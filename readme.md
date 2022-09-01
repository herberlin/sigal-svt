## sigal svt

http://sigal.saimon.org/en/latest/getting_started.html

### HowTo

The sigal - home directory is mapped to `./sigal`.  Place your images at 
`./sigal/pictures/`.

```
docker-compose up &
```
Starts the processor for `./sigal/pictures`, the starts the server for the 
`./sigal/_build` directory. Serves for `http://localhost:8000`.

To run the build again use: 
```
docker exec sigal sigal build
```
