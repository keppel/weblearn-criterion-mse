## weblearn-criterion-mse

Mean squared error criterion for [WebLearn]

### Usage
```
npm install weblearn-criterion-mse
```

```js
const MSECriterion = require('weblearn-criterion-mse')

const criterion = MSECriterion()

criterion.forward(output, target)
const err = criterion.backward(output, target)

```

[WebLearn]: https://github.com/keppel/weblearn
