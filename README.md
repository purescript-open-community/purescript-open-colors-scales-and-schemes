# purescript-open-colors-scales-and-schemes

The `Color.Scale.Perceptual` and `Color.Scheme.XXX` were deleted from https://github.com/purescript-contrib/purescript-colors.

So, I have restored them.

- [Module documentation](https://pursuit.purescript.org/packages/purescript-open-colors-scales-and-schemes)

## Development

To run the unit tests, the following steps are necessary:

```
spago install
spago test
```

To build the interactive docmentation, run:

```
cd documentation
spago install
spago build -O -m Main -t html/test.js
```
