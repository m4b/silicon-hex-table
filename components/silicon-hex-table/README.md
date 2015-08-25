# Install

`bower install silicon-hex-table`

# Usage

`<silicon-hex-table>` accepts an optional `offset` and a `Uint8Array` called `bytes`, and then displays the results, as all hexadecimal editors/viewers should.

If you data bind or modify `offset`, the table updates accordingly.

If you want more rows, modify `rows` (the default is 16).  `rows` is zero-indexed.

Example:

````html
<silicon-hex-table offset="[[offset]]" bytes="[[bytes]]"></silicon-hex-table>
````

For more details and a demo, head on over to the [documentation page](http://m4b.github.io/silicon-hex-table).

And remember: **_always hex responsibly_**.
