# spinny

Console wait indicators inspired by [this SO thread](http://stackoverflow.com/questions/2685435/cooler-ascii-spinners).

## Usage

```
var spinny = require('spinny');

// Start the spinner with a call to spinny()
var spinner = spinny();

// Do some async work...

// Stop the spinner by calling stop() on your spinner
spinner.stop();

// Create a different kind of spinner
spinny.clock();
spinny.slashes();

// Display a message with the spinner
spinny('Downloading, please wait...');

// Change the speed of the spinner
spinny('Optional message', {
  duration: 2000 // milliseconds for one cycle of the animation
});

spinny({
  interval: 100 // milliseconds for a single animation frame
});
```

## Spinners
- `braille`
- `brailleCircle`
- `arrows`
- `volume`
- `width`
- `corner`
- `boxCorner`
- `circleCorner`
- `slashes`
- `halfNHalf`
- `blink`
- `moon`
- `clock`

