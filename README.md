# snippets
snippets publicly available


## How to detect touch screen device using JavaScript?

https://www.geeksforgeeks.org/how-to-detect-touch-screen-device-using-javascript/
```
function is_touch_enabled() { 
    return ( 'ontouchstart' in window ) ||  
           ( navigator.maxTouchPoints > 0 ) ||  
           ( navigator.msMaxTouchPoints > 0 ); 
} 


```
