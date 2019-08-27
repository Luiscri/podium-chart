# podium-chart

<div style="text-align:center"><img src="./img/podium-preview.png" alt="Podium preview"/></div>

`<podium-chart>` is a web component designed to display text information over a podium making clear the existence of a classification or ranking. If any of the throphies is clicked a modal window will appear showing additional information.

### Usage

This component accepts the following parameters:
- **data:** information to be represented (required)
- **height:** total podium's height (default to 300px)
- **stylebg:** podium's background color (default to navy blue)
- **nwords:** number of words appearing on each trophy (default to 3)

```
<podium-chart
    data="{{data}}"
    height="300"
    stylebg="bg-navy"
    nwords="3">
</podium-chart>
```

### Installation

This web component is available in bower. 

```bash
$ bower install podium-chart
```

This command will install it inside `bower_components` folder.
