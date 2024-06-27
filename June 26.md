

# CSS Battle Daily Targets: 26 June 2024

## Daily Targets to Solve

### Target Image

![picture of daily target](https://github.com/BekiaD/cssbattle/assets/144695091/715b8d3a-86ec-44b0-8a9e-55f8f1721a9a)


### My solution

![picture of my solution](https://github.com/BekiaD/cssbattle/assets/144695091/cabbc17a-b567-4c1d-8289-f00b7306a962)

## Stats

**Match**: 100%
**Score**: 

## Code

### Raw

```html
<p id='a'><div id='dh'><p class='gv'><p class='gv'></div><div id='dv'><p class='gv'><p class='gv'></div>

<div id='dhx'><p class='gl'><p class='gl'></div><div id='dvx'><p class='gl'><p class='gl'></div>
<style>
body{
  background: #024817;
  display: flex;

  justify-content:center;
  align-items:center;
}
  
p{
  aspect-ratio:1;
  border-radius:50%;
  width:40px;
}
    #a{
    width:60px;
    background:#48BF7D;
    position:absolute;
  }
  
  div{
  position:absolute;
  display:flex;
  align-items:center;
  justify-content:space-between;
  }
  
#dh{
  flex-direction: column;
  height:210;
}


  #dv{
  flex-direction: row;
  width:180;
}

.gv{
    background:#176C36;
    width:40px;
  }
  .gl{
       background:#48BF7D;
    width:40px;
  }

  #dhx{
  flex-direction: column;
    transform: rotate(45deg);
  height:210;
}


  #dvx{
  transform: rotate(45deg);
  flex-direction: row;
  width:180;
}

</style>
```

### Minified

```html
<p id='a'><div id='dh'><p class='gv'><p class='gv'></div><div id='dv'><p class='gv'><p class='gv'></div><div id='dhx'><p class='gl'><p class='gl'></div><div id='dvx'><p class='gl'><p class='gl'></div><style>body{background:#024817;display:flex;justify-content:center;align-items:center}p{aspect-ratio:1;border-radius:50%;width:40}#a{width:60;background:#48BF7D;position:absolute}div{position:absolute;display:flex;align-items:center;justify-content:space-between}#dh{flex-direction:column;height:210}#dv{flex-direction:row;width:180}.gv{background:#176C36;width:40}.gl{background:#48BF7D;width:40}#dhx{flex-direction:column;transform:rotate(45deg);height:210}#dvx{transform:rotate(45deg);flex-direction:row;width:180}</style>
```
