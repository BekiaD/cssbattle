

# CSS Battle Daily Targets: 17 June 2024

## Daily Targets to Solve

### Target Image

![picture of daily target](https://github.com/BekiaD/cssbattle/assets/144695091/e36c653f-6498-4e9a-b371-c70f1bfe67ca)

### My solution

![picture of my solution](https://github.com/BekiaD/cssbattle/assets/144695091/7171354c-7fc7-4d42-8b72-53f1d0009410)

## Stats

**Match**: 100%
**Score**:

## Code

### Raw

```html
<p class='a' id='l'><div class='big'><div class='in'><p class='s'><p class='c'></div><div class='in' id='inn'><p class='c'><p class='s'></div><p class='a' id='r'>
  <style>
    body{
      background:#EFF8FE;
      display:flex;
      justify-content:space-around;
      align-items:center;
      justify-content:center
    }
    .big{
      background:#4F77FF;
      width:270;
      height:180
    }

    .a{
      width:20;
      height:180;
      background:#4F77FF
    }

    #l{
      position:absolute;
      left:35;
      top:44
    }

     #r{
      position:absolute;
      right:35;
      top:44
    }

    .c{
      aspect-ratio:1;
      width:75;
      background:#EFF8FE;
      border-radius:50%
    }

    .s{
      width:165;
      height:75;
      background:#EFF8FE
    }

    .in{
      margin-top:-6;
      display:flex;
      justify-content:space-evenly;
      align-items:center
    }

    #inn{
      margin-top:-22
    }
  </style>
```

### Minified

```html
<p class='a' id='l'><div class='big'><div class='in'><p class='s'><p class='c'></div><div class='in' id='inn'><p class='c'><p class='s'></div><p class='a' id='r'><style>body{background:#EFF8FE;display:flex;justify-content:space-around;align-items:center;justify-content:center}.big{background:#4F77FF;width:270;height:180}.a{width:20;height:180;background:#4F77FF}#l{position:absolute;left:35;top:44}#r{position:absolute;right:35;top:44}.c{aspect-ratio:1;width:75;background:#EFF8FE;border-radius:50%}.s{width:165;height:75;background:#EFF8FE}.in{margin-top:-6;display:flex;justify-content:space-evenly;align-items:center}#inn{margin-top:-22}</style>
```
