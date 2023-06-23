# terser-constant-condition-dce

RE: https://twitter.com/JLarky/status/1672245484885512192

Showing how `0 && <MyComponent />` will remove `MyComponent` from your bundle since it's unused.
