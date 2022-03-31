# Svelte Wheel of Fortune
This is a simple wheel of fortune game developed using svelte, vanilla JavaScript code and css. Feel free to bet your life's savings 🤑.

## Usage Example
```html
<script>
import WheelOfFortune from 'https://deno.land/x/svelte_wheel_of_fortune';
</script>

<div>
    <WheelOfFortune /> 
</div>
```
On winning and losing the bet the Wheel-of-Fortune component will dispatch a 'win' or 'lose' event using svelte's own createEventDispatcher.
For now the winnings and losings amount is hardcoded into the component but for now you can fork your own version and edit the 'winAmount' and 'loseAmount' yourself!
