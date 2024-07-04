

# CSS Battle Daily Targets: 2 July 2024

## Daily Targets to Solve

### Target Image

![picture of daily target](https://github.com/BekiaD/cssbattle/assets/144695091/ff3e6807-4c8e-445b-8ad4-541d55b87ac7)

### My solution

![picture of my solution](https://github.com/BekiaD/cssbattle/assets/144695091/38d17d9d-8b68-45e6-8d5c-7724db309073)

## Stats

**Match**: 100%
**Score**: 

## Code

### Raw

```html
<div> <p class='t' id='lt'><p class='c' id='lc'></div>

<p class='t' id='rt'><p class='c' id='rc'>
<style>
body{
  background:#EDAF38;
  display:flex;
  align-items:center;
}
div{
  position:absolute;
  width:200;
  height:300;
  left:0;
  background:#FFFFCD;
  z-index:-1;
}
p{
  position:absolute;
}
  .t{
  width:120;
  height:100;
  top:85;
  }

#lt{
  background:#EDAF38;
  border-radius:50px 0 0 50px;
  left:80;
}
 #rt{
  background:#FFFFCD;
  border-radius:0 50px 50px 0;
  right:80;
} 
.c{
  border-radius:50%;
  width:60px;
  height:60px;
  background:black;
  top:105;
}

  #lc{
    left:100;
    background:#FFFFCD;
  }

  #rc{
    right:100;
    background:#EDAF38;
  }
</style>

```

### Minified

```
<div><p class='t' id='lt'><p class='c' id='lc'></div><p class='t' id='rt'><p class='c' id='rc'><style>body{background:#EDAF38;display:flex;align-items:center}div{position:absolute;width:200;height:300;left:0;background:#FFFFCD;z-index:-1}p{position:absolute}.t{width:120;height:100;top:85}#lt{background:#EDAF38;border-radius:50px 0 0 50px;left:80}#rt{background:#FFFFCD;border-radius:0 50px 50px 0;right:80}.c{border-radius:50%;width:60px;height:60px;background:#000;top:105}#lc{left:100;background:#FFFFCD}#rc{right:100;background:#EDAF38}</style>
```
