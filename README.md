# Basic Dice Rolling tool

[See in action](https://rosnovsky.github.io/dice/)

Further improvements will include: 
- selecting the number of sides a dice has (now set to 6)
- selecting a number of dice to roll (now set to 1)
- tracking stats
- adding Random.org API for improved randomness

## My favorite features

Thanks to ```Dice``` object prototype, ```roll``` method, and the use of ```this```, the app is ready for any number of dice rolled, and dice could have arbitrary number of sides. To roll a die with certanin number of sides, just say:

```javascript
new Dice(6);
```
