# react-pagination
React fetch data from api and display paginations(CRUD)

# codesandbox
Here adding codesandbox to directly view the code `https://codesandbox.io/s/epic-water-83mndm`

# dummyjson
Meanwhile you can see how to fetch the data from dummy json here is the link `https://dummyjson.com/docs/products`

# front-end fetch the data with limits (back-end will do the calculations)
* Using this fetch link `https://dummyjson.com/products?limit=10&skip=10`
* It will be present in codesandbox just go through `https://codesandbox.io/s/epic-water-83mndm`


# front-end fetch all the data in once
* Remove this line because front-end will do the fetch once `const [totalPages, setTotalPages] = useState(0);`
* Replace the fetch with this link `https://dummyjson.com/products?limit=100`
* Remove this line `setTotalPages(data.total / 10);`
* Replace the `totalPages` with this `products.length / 10`
