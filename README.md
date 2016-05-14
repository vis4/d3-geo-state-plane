# d3.geo.statePlanes

Nice projections for US states in D3. 

[Live demo](http://bl.ocks.org/gka/f2aabf4a516e16a5190f25fd1923406f)

```js
var proj = d3.geo.statePlane('NY');
```

By default, the projection will be scaled and translated to fit the state into a 1000px * 600px rect, but you can easily scale for a different output size by passing width and height as additional parameters:

```js
// center NY into a 500px * 350px viewport
var proj = d3.geo.statePlane('NY', 500, 350);
```

This was hacked together in a few hours, so please feel free to fix projections or correct errors using pull requests.

## Related work

* For more D3 state plane projections, check out Noah Veltman's [d3-stateplane](https://github.com/veltman/d3-stateplane)
