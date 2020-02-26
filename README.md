# TheAdvancedWebDeveloperBootcampColtSteel
Learning Webdevelopment

CSS Animations Transforms and Transforms

pseudo classes 
    hover
    focus 
    active

transform 
    transform:translateX(x),translateY(y),translate(x,y);
    transform:scaleX(),scaleY(),scale();
    transform-origin:x y;left top;right;
    transform:rotate(45deg);
    /* autoprefixer to give prefix */

transition
    transition-duration:1s;                                 5s,1s;
    transition-property:all;opacity;color;background-color; background-color,border-radius;
    trasition-delay:1s;                                     2s,0.5s;
    transition-timing-function:ease-in;ease-out;ease-in-out;cubic-bezier(); // matthewlein.com/tools/ceaser for bezier
    transition: property duration timing-function delay;
    transition: transform 2s linear 1s;

03 CSS Animations Keyframes

    @keyframes name{
        0%{
            ...
        }
        50%{
            ...
        }
        100%{
            ...
        }
    }
    p{
        animation-name:name;
        animation-duration:5s;
        animation-timing-function:linear;
        animation-delay:0s;
        animation-iteration-count:infinte;
        animation-direction:forward;reverse;alternate;
        animation-fill-mode:none;forwards;backwards;both;
        animation-play-state:paused;running;
        animation: name duration timing-function delay iteration-count direction fill-mode;
    }
