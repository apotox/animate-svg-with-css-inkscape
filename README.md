# animate-svg-with-css-inkscape


<p align="center"> 
<img src="demo/animate-svg-with-css.png">
</p>

```
#layer3{
    left: -20px;
    opacity: 0;
    cursor: pointer;
}

#layer1 #layer3{
    animation: animateLayer 1.2s infinite;

}

@keyframes animateLayer{
    0% {
        transform: translateX(0) translateY(0);
        opacity: 0;
    }

    40% {
        transform: translateX(10px) translateY(-6px);
        opacity: 0.6;
    }

    100% {
        transform: translateX(20px) translateY(-12px);
        opacity: 0;
    }
}
```


[Demo live](http://animate-svg-with-css.surge.sh/)
