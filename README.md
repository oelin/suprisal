# surprisal

Compute the surprisal of an event given its probability.


## Installation

```sh
npm i surprisal
```


## Usage

```js
import surprisal from 'surprisal'

surprisal(0.5) // returns 1.0

surprisal(1.0) // returns 0.0

surprisal(0.0) // returns Infinity
```

Suprisal is given in bits (base 2) by default, however you can also specify other bases via the second argument. For example, to compute surprisal in nats (base 10):

```js
surprisal(0.5, base=10) // returns 0.301
```
