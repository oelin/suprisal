# suprisal

Compute the suprisal of an event given its probability.


## Installation

```sh
npm i suprisal
```


## Usage

```js
import suprisal from 'suprisal'

suprisal(0.5) // returns 1.0

suprisal(1.0) // returns 0.0

suprisal(0.0) // returns Infinity
```

Suprisal is given in bits (base 2) by default, however you can also specify other bases via the second argument. For example, to compute suprisal in nats (base 10):

```js
suprisal(0.5, base=10) // returns 0.301
```
