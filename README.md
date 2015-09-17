# buttons
## tags
``` html
<a href="#" class="btn">a.btn</a>
<button type="button" class="btn">button.btn</button>
```

## flat
``` html
<a href="#" class="btn btn--flat--default">default color</a>
<a href="#" class="btn btn--flat--primary">primary color</a>
<a href="#" class="btn btn--flat--highlight">highlight color</a>
<a href="#" class="btn btn--flat--action">action color</a>
```

## flat disabled
``` html
<a href="#" class="btn btn--flat--default disabled">default disabled</a>
<a href="#" class="btn btn--flat--primary disabled">primary disabled</a>
<a href="#" class="btn btn--flat--highlight disabled">highlight disabled</a>
<a href="#" class="btn btn--flat--action disabled">action disabled</a>
```

## border
``` html
<a href="#" class="btn btn--border--default">default color</a>
<a href="#" class="btn btn--border--primary">primary color</a>
<a href="#" class="btn btn--border--highlight">highlight color</a>
<a href="#" class="btn btn--border--action">action color</a>
```

## border disabled
``` html
<a href="#" class="btn btn--border--default disabled">default disabled</a>
<a href="#" class="btn btn--border--primary disabled">primary disabled</a>
<a href="#" class="btn btn--border--highlight disabled">highlight disabled</a>
<a href="#" class="btn btn--border--action disabled">action disabled</a>
```

## rounded
``` html
<a href="#" class="btn btn--rounded--default">default color</a>
<a href="#" class="btn btn--rounded--primary">primary color</a>
<a href="#" class="btn btn--rounded--highlight">highlight color</a>
<a href="#" class="btn btn--rounded--action">action color</a>
```

## rounded disabled
``` html
<a href="#" class="btn btn--rounded--default disabled">default disabled</a>
<a href="#" class="btn btn--rounded--primary disabled">primary disabled</a>
<a href="#" class="btn btn--rounded--highlight disabled">highlight disabled</a>
<a href="#" class="btn btn--rounded--action disabled">action disabled</a>
```

## 3D
``` html
<a href="#" class="btn btn--3d--default">default color</a>
<a href="#" class="btn btn--3d--primary">primary color</a>
<a href="#" class="btn btn--3d--highlight">highlight color</a>
<a href="#" class="btn btn--3d--action">action color</a>
```

## 3D disabled
``` html
<a href="#" class="btn btn--3d--default disabled">default disabled</a>
<a href="#" class="btn btn--3d--primary disabled">primary disabled</a>
<a href="#" class="btn btn--3d--highlight disabled">highlight disabled</a>
<a href="#" class="btn btn--3d--action disabled">action disabled</a>
```

## size
``` html
<a href="#" class="btn btn--flat--primary btn--jumbo">size jumbo</a>
<a href="#" class="btn btn--flat--primary btn--large">size large</a>
<a href="#" class="btn btn--flat--primary">size default</a>
<a href="#" class="btn btn--flat--primary btn--small">size small</a>
<a href="#" class="btn btn--flat--primary btn--tiny">size tiny</a>
```

## icon right

iconは以下を使用しています。

[Font Awesome](https://fortawesome.github.io/Font-Awesome/)

``` html
<a href="#" class="btn btn--flat--primary btn--jumbo">size jumbo<i class="btn__icon--right fa fa-angle-right"></i></a>
<a href="#" class="btn btn--flat--primary btn--large">size large<i class="btn__icon--right fa fa-angle-right"></i></a>
<a href="#" class="btn btn--flat--primary">size default<i class="btn__icon--right fa fa-angle-right"></i></a>
<a href="#" class="btn btn--flat--primary btn--small">size small<i class="btn__icon--right fa fa-angle-right"></i></a>
<a href="#" class="btn btn--flat--primary btn--tiny">size tiny<i class="btn__icon--right fa fa-angle-right"></i></a>
```

## icon left

iconは以下を使用しています。

[Font Awesome](https://fortawesome.github.io/Font-Awesome/)

``` html
<a href="#" class="btn btn--flat--primary btn--jumbo"><i class="btn__icon--left fa fa-check-circle"></i>size jumbo</a>
<a href="#" class="btn btn--flat--primary btn--large"><i class="btn__icon--left fa fa-check-circle"></i>size large</a>
<a href="#" class="btn btn--flat--primary"><i class="btn__icon--left fa fa-check-circle"></i>size default</a>
<a href="#" class="btn btn--flat--primary btn--small"><i class="btn__icon--left fa fa-check-circle"></i>size small</a>
<a href="#" class="btn btn--flat--primary btn--tiny"><i class="btn__icon--left fa fa-check-circle"></i>size tiny</a>
```

## btn block
``` html
<a href="#" class="btn btn--flat--primary btn--block">btn-block</a>
```

##　ブランドカラーを変更する

ブランドカラーを変更することもできます。

_configs.scss

``` css
/* -- brand color -- */
$var-brand-default:         #E6E6EA !default;
$var-brand-primary:			#FED766 !default;
$var-brand-highlight:		#2AB7CA !default;
$var-brand-action:			#FE4A49 !default;
```