# Grid-away-grid-ahoy

## Made by : Audric Skivée (BeCode@hamiltons 5.32)

New project this time, to learn more about Grid-layout and the responsivity of it.
**everything is done with pure CSS, no js**

### what did I use ? 

1. sass  
2. grid-layout  
3. flex-box
4. node-sass (transpiler)

## First thing first

if you want to use node-sass too, here how : 

install node.js, found it [here](https://nodejs.org/en/)  
it will *unlock* the __npm__ command.

## Secondly

install node-sass with your terminal, write :  

```
npm install -g node-sass
```  

the -g flag indicates you're installing it for the whole device.

## thirdly

with your terminal, go to your active directory, write :  

```
cd /path/to/your/working/directory
``` 

Now that you're in right directory, you may start the transpiler, write :

```
node-sass sass/screen.scss css/screen.css -o --watch
```  

### I'll explain what the above does : 

1. __*node-sass*__ : it calls the newly added package to your terminal.

2. __*sass/screen.scss*__ : this argument tells node-sass the directory from where it will fetch the data to "feed" the transpiler.

3. __*css/screen.css*__ : this argument tells node-sass the output directory, were the transpiled file will go when it's finished to transpile.

4. __*-o*__  : this flag will specify that the argument before this flag is an output directory, if ommited the output will be sent to stdout(?). 

5. __*--watch*__  : this flag will make node-sass stay put and watch your files, and every time there is a modification, it will sees it.  

## now ?

you're all set, everytime you're gonna save/modify your screen.scss (or the files imported inside your screen.scss) it will transpile all your files into a .css file inside your /css directory.  

/!\ Watch out, I showed you how *I* did it with the files named __my way__. If your files/directory have other names, modify your code accordingly, or just use the same tree as me.

Thanks my lads, now I'm gonne drink a cold one with the boïs!
