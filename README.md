BenchMark.playground
====================

```
Benchmark.measure("重いかもしれない処理1", block: {
  sleep(1)
  return
})

let myBenchMark = Benchmark(key: "重いかもしれない処理2")
let myHeavyValue = MyHeavyClass()
myHeavyValue.myMethod()
myBenchMark.finish()
```

http://qiita.com/tady/items/40d7c4feecda337cf271
