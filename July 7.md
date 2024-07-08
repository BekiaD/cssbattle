

# CSS Battle Daily Targets: 7 July 2024

## Daily Targets to Solve

### Target Image

![picture of daily target](https://github.com/BekiaD/cssbattle/assets/144695091/4131ceec-9944-4c40-bd5b-e33f135578b4)


### My solution

![picture of my solution](https://github.com/BekiaD/cssbattle/assets/144695091/3c636ef8-cef1-46ad-948f-fff92d4395d7)

## Stats

**Match**: 100%
**Score**: 

## Code

### Raw

```html
<p id='a'><p id='l'><p id='r'>
<style>
  body{
    background:#0A6190;
    display:flex;
    justify-content:center;
    align-items:center
  }

  #a{
    position:absolute;
    width: 200px;
	height: 100px;
	transform: skew(-27deg);
	background:#328FC1
  }

  #l{
  position:absolute;
  left:0;
  top:130;
  width: 0; 
  height: 0; 
  border-right: 25px solid transparent;
  border-bottom: 55px solid #328FC1
  }


  #r{
  position:absolute;
  right:0;
  top:84;
  width: 0; 
  height: 0; 
  border-right: 24px solid transparent;
  border-bottom: 55px solid #328FC1;
  transform:rotate(180deg)
  }
</style>
```

### Minified

```
<p id='a'><p id='l'><p id='r'><style>body{background:#0A6190;display:flex;justify-content:center;align-items:center}#a{position:absolute;width:200px;height:100px;transform:skew(-27deg);background:#328FC1}#l{position:absolute;left:0;top:130;width:0;height:0;border-right:25px solid #fff0;border-bottom:55px solid #328FC1}#r{position:absolute;right:0;top:84;width:0;height:0;border-right:24px solid #fff0;border-bottom:55px solid #328FC1;transform:rotate(180deg)}</style>
```
