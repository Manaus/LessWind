# LessWind

This project is a mixin library to speed up the development of style sheets for web pages. 
The idea is to convert utility classes into mixins, and declutter web pages. 
The pre-processor used is Less. 

For example: 

```less 
.my-section {
    .p-1; // padding: 1rem 
    .bg-red; // background-color; red;
    .h-half; // height: 50vh;
}
```

## Development process

I'm using EasyLess for transpiling Less files to Css. 
EasyLess is an extension you can find in the Extensions Catalogue within Microsoft VSCode.  