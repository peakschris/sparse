# sparse
Demonstrates issue with sparse checkout

1. git clone --sparse https://github.com/peakschris/sparse.git
2. cd sparse
3. copy sparse-checkout.txt .git\info\sparse-checkout
4. git sparse-checkout reapply

Output:
```warning: unrecognized negative pattern: '/A/B'
warning: disabling cone pattern matching
warning: unrecognized negative pattern: '/A/B'
warning: disabling cone pattern matching```
