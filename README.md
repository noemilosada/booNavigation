**booNavigation jQuery plugin**
==============================
------------------------------

Smooth and dynamic navigation with a three column drop down.

**HTML Structure**

```html
<nav id="booNavigation" class="booNavigation">
    <ul>
        <li class="navItem">
            <a href="#" title="First Item">First Item</a>
            <ul class="navContent">
                <!-- Three columns -->
                <li>
                    <ul>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                    </ul>
                </li>
                <li>
                    <ul>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                    </ul>
                </li>
                <li>
                    <ul>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                    </ul>
                </li>
            </ul>
        </li>

        <li class="navItem">
            <a href="#" title="Second Item">Second Item</a>
            <ul class="navContent">
                <li>
                    <ul>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                    </ul>
                </li>
                <li>
                    <ul>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                    </ul>
                </li>
                <li>
                    <ul>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                    </ul>
                </li>
            </ul>
        </li>

        <li class="navItem">
            <a href="#" title="Third Item">Third Item</a>
            <ul class="navContent">
                <li>
                    <ul>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                    </ul>
                </li>
                <li>
                    <ul>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                    </ul>
                </li>
                <li>
                    <ul>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                        <li><a href="#" title="Boo the cat">Boo the cat</a></li>
                    </ul>
                </li>
            </ul>
        </li>

        <!-- You can add more navItems as you need -->
    </ul>
</nav>
```

**Plugin Usage**

```javascript
$('#yourNavigationCustomId').booNavigation({
    slideSpeed: 600,
    fadeSpeed: 400,
    delay: 500
});
```

**Options**

```slideSpeed:``` 200 / 400 / 600 / 'slow' / 'fast'   
This will be the speed to open the drop down with a slide effect.   
The default option is 600.
   
```fadeSpeed:``` 200 / 400 / 600 / 'slow' / 'fast'   
This will be the speed to display the drop down content with a fade effect.   
The default option is 200.
   
```delay:``` any numeric value   
This is a delay to avoid opening the drop down immediately when the user hovers the item.   
The default option is 500.
