## Welcome

This component implements 'The Stack' from [EveryLayout](https://every-layout.dev/layouts/stack/).

It is used like so:

```
 <Stack>
    <your/>
    <html/>
    <here/>
 </Stack>
```

When you setup a global CSS with a scale as described [here](https://every-layout.dev/rudiments/modular-scale/) or have your own CSS variables it can be parametrized like so:

```
<Stack margin="--some-css-variable">
    ...
 </Stack>
```