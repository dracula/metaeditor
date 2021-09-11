### [MetaEditor](https://www.metatrader5.com/en/automated-trading/metaeditor)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/metaeditor.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/metaeditor/archive/master.zip) option and unzip them.

#### Activating theme

1. Open the configuration folder for the Metatrader version you want to change, in MT5 usually at:

```
C:\Users\{YOUR USER}\AppData\Roaming\MetaQuotes\Terminal\{Code}\config
```

2. Add the following lines to the file **metaeditor.ini**   :
```c++
[Colors]
Color0= 3549736
Color1= 15923448
Color2= 5916484
Color3= 0
Color4= 0
Color5= 13007359
Color6= 8744041
Color7= 16356285
Color8= 13007359
Color9= 9239281
Color10= 16356285
Color11= 8125008
Color12= 15923448
Color13= 16640395
Color14= 7125247 
```
*Replace the `[Colors]` section if it already exists.
  
3. Restart MetaEditor to apply changes

4. Boom! It's working
