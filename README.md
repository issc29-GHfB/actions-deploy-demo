# fib-tools

[![Board Status](https://dev.azure.com/issc29/5889ceb5-6da0-40b5-92c1-8e893549b136/99542af5-6e8e-4694-bb7a-4255dc708950/_apis/work/boardbadge/951a6e0f-5fab-4055-9b82-e47139cbeae8)](https://dev.azure.com/issc29/5889ceb5-6da0-40b5-92c1-8e893549b136/_boards/board/t/99542af5-6e8e-4694-bb7a-4255dc708950/Microsoft.RequirementCategory/)

[![Build Status](https://dev.azure.com/issc29/actions-deploy-demo/_apis/build/status/issc29-GHfB.actions-deploy-demo?branchName=master)](https://dev.azure.com/issc29/actions-deploy-demo/_build/latest?definitionId=2&branchName=master)

Make the magic happen now!

## Get the nth Number

```javascript
const {getNumber} = require('@bbq-beets/fib-tools')
assert.strictEqual(getNumber(8), 21)
```asdfasdfadsf

## Get a List of Numbers

```javascript
const {getList} = require('@bbq-beets/fib-tools')
assert.strictDeepEqual(getList(8), [0, 1, 1, 2, 3, 5, 8, 13, 21])
```

## Get a Sequence of Numbers

```javascript
const {getSequence} = require('@bbq-beets/fib-tools')

const seq = getSequence()

for (const n of seq) {
  console.log(n) // The next Fibonacci number in the sequence
}
```
