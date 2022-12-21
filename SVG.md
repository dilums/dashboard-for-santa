# SVG Generation  

- ### Text Generation
    - [Basic Layout](https://github.com/dilums/dashboard-for-santa#basic-layout)
    - [Staff Contact Info](https://github.com/dilums/dashboard-for-santa#staff-contact-info)
    - [Notifications](https://github.com/dilums/dashboard-for-santa#notifications-list)
    - [Naughty & Nice](https://github.com/dilums/dashboard-for-santa#naughty--nice-list)
    - [Todos](https://github.com/dilums/dashboard-for-santa#todos)
    - [Quote](https://github.com/dilums/dashboard-for-santa#quote)  
- ### SVG Generation
    - [Santa's Travel Map](#santas-travel-map)
    - [Colors](#colors)
    - [Ornaments](#ornaments)
    - [Logic](#logic)

## Santa's Travel Map
### can you create Santa's travel map in SVG
```SVG
<svg width="500" height="300">
  <rect x="50" y="50" width="400" height="200" fill="#ccc" />
  <circle cx="100" cy="100" r="20" fill="#f00" />
  <circle cx="200" cy="100" r="20" fill="#0f0" />
  <circle cx="300" cy="100" r="20" fill="#00f" />
  <circle cx="400" cy="100" r="20" fill="#ff0" />
  <polyline points="100,100 200,100 200,200 300,200 300,100 400,100 400,200" stroke="#000" stroke-width="2" fill="none" />
</svg>
```
![1](https://res.cloudinary.com/ds574fco0/image/upload/v1671547037/live/santa-dashboard/1_p1ne4l.svg)  

### can you give me a map with more paths  
```SVG
<svg width="600" height="400">
  <rect x="50" y="50" width="500" height="300" fill="#ccc" />
  <circle cx="100" cy="100" r="20" fill="#f00" />
  <circle cx="200" cy="100" r="20" fill="#0f0" />
  <circle cx="300" cy="100" r="20" fill="#00f" />
  <circle cx="400" cy="100" r="20" fill="#ff0" />
  <circle cx="500" cy="100" r="20" fill="#f00" />
  <polyline points="100,100 200,100 200,200 300,200 300,100 400,100 400,200 500,200" stroke="#000" stroke-width="2" fill="none" />
  <circle cx="100" cy="200" r="20" fill="#0f0" />
  <circle cx="200" cy="200" r="20" fill="#00f" />
  <circle cx="300" cy="200" r="20" fill="#ff0" />
  <circle cx="400" cy="200" r="20" fill="#f00" />
  <circle cx="500" cy="200" r="20" fill="#0f0" />
  <polyline points="100,200 200,200 200,300 300,300 300,200 400,200 400,300 500,300" stroke="#000" stroke-width="2" fill="none" />
</svg>
```
![2](https://res.cloudinary.com/ds574fco0/image/upload/v1671547148/live/santa-dashboard/2_sdqo3t.svg)  
### can you create a new map representing 12 cities or towns Santa will visit
```SVG
<svg width="700" height="500">
  <rect x="50" y="50" width="600" height="400" fill="#ccc" />
  <circle cx="100" cy="100" r="20" fill="#f00" />
  <circle cx="200" cy="100" r="20" fill="#0f0" />
  <circle cx="300" cy="100" r="20" fill="#00f" />
  <circle cx="400" cy="100" r="20" fill="#ff0" />
  <circle cx="500" cy="100" r="20" fill="#f00" />
  <circle cx="600" cy="100" r="20" fill="#0f0" />
  <polyline points="100,100 200,100 200,200 300,200 300,100 400,100 400,200 500,200 500,300 600,300" stroke="#000" stroke-width="2" fill="none" />
  <circle cx="100" cy="200" r="20" fill="#0f0" />
  <circle cx="200" cy="200" r="20" fill="#00f" />
  <circle cx="300" cy="200" r="20" fill="#ff0" />
  <circle cx="400" cy="200" r="20" fill="#f00" />
  <circle cx="500" cy="200" r="20" fill="#0f0" />
  <circle cx="600" cy="200" r="20" fill="#00f" />
  <polyline points="100,200 200,200 200,300 300,300 300,200 400,200 400,300 500,300 500,400 600,400" stroke="#000" stroke-width="2" fill="none" />
</svg>
```
![3](https://res.cloudinary.com/ds574fco0/image/upload/v1671547266/live/santa-dashboard/3_xn5och.svg)  
### can you adjust cx and cy values of the SVG so that those are not multiplications of 10
```SVG
<svg width="700" height="500">
  <rect x="50" y="50" width="600" height="400" fill="#ccc" />
  <circle cx="120" cy="110" r="20" fill="#f00" />
  <circle cx="220" cy="110" r="20" fill="#0f0" />
  <circle cx="320" cy="110" r="20" fill="#00f" />
  <circle cx="420" cy="110" r="20" fill="#ff0" />
  <circle cx="520" cy="110" r="20" fill="#f00" />
  <circle cx="620" cy="110" r="20" fill="#0f0" />
  <polyline points="120,110 220,110 220,210 320,210 320,110 420,110 420,210 520,210 520,310 620,310" stroke="#000" stroke-width="2" fill="none" />
  <circle cx="120" cy="210" r="20" fill="#0f0" />
  <circle cx="220" cy="210" r="20" fill="#00f" />
  <circle cx="320" cy="210" r="20" fill="#ff0" />
  <circle cx="420" cy="210" r="20" fill="#f00" />
  <circle cx="520" cy="210" r="20" fill="#0f0" />
  <circle cx="620" cy="210" r="20" fill="#00f" />
  <polyline points="120,210 220,210 220,310 320,310 320,210 420,210 420,310 520,310 520,410 620,410" stroke="#000" stroke-width="2" fill="none" />
</svg>
```
![4](https://res.cloudinary.com/ds574fco0/image/upload/v1671547384/live/santa-dashboard/4_msizpo.svg)
### can you use one polyline instead of 2
```SVG
<svg width="700" height="500">
  <rect x="50" y="50" width="600" height="400" fill="#ccc" />
  <circle cx="120" cy="110" r="20" fill="#f00" />
  <circle cx="220" cy="110" r="20" fill="#0f0" />
  <circle cx="320" cy="110" r="20" fill="#00f" />
  <circle cx="420" cy="110" r="20" fill="#ff0" />
  <circle cx="520" cy="110" r="20" fill="#f00" />
  <circle cx="620" cy="110" r="20" fill="#0f0" />
  <polyline points="120,110 220,110 220,210 320,210 320,110 420,110 420,210 520,210 520,310 620,310 120,210 220,310 320,210 420,310 520,410 620,410" stroke="#000" stroke-width="2" fill="none" />
  <circle cx="120" cy="210" r="20" fill
```
> Crashed😢 before the line where there was the second polyline. Then got a timeout. 

## Colors
```SVG
<svg width="250" height="250">
  <rect x="0" y="0" width="50" height="50" fill="#FFB6C1"/>
  <rect x="50" y="0" width="50" height="50" fill="#F08080"/>
  <rect x="100" y="0" width="50" height="50" fill="#CD5C5C"/>
  <rect x="150" y="0" width="50" height="50" fill="#FF4500"/>
  <rect x="200" y="0" width="50" height="50" fill="#8B2500"/>
  
  <rect x="0" y="50" width="50" height="50" fill="#FFFFE0"/>
  <rect x="50" y="50" width="50" height="50" fill="#FFFACD"/>
  <rect x="100" y="50" width="50" height="50" fill="#FFEFD5"/>
  <rect x="150" y="50" width="50" height="50" fill="#FFE4B5"/>
  <rect x="200" y="50" width="50" height="50" fill="#FFDAB9"/>
  
  <rect x="0" y="100" width="50" height="50" fill="#F0E68C"/>
  <rect x="50" y="100" width="50" height="50" fill="#EEE8AA"/>
  <rect x="100" y="100" width="50" height="50" fill="#BDB76B"/>
  <rect x="150" y="100" width="50" height="50" fill="#9ACD32"/>
  <rect x="200" y="100" width="50" height="50" fill="#6B8E23"/>
  
  <rect x="0" y="150" width="50" height="50" fill="#00FF7F"/>
  <rect x="50" y="150" width="50" height="50" fill="#7CFC00"/>
  <rect x="100" y="150" width="50" height="50" fill="#7FFFD4"/>
  <rect x="150" y="150" width="50" height="50" fill="#66CDAA"/>
  <rect x="200" y="150" width="50" height="50" fill="#00FFFF"/>
  
  <rect x="0" y="200" width="50" height="50" fill="#00BFFF"/>
  <rect x="50" y="200" width="50" height="50" fill="#87CEFA"/>
  <rect x="100" y="200" width="50" height="50" fill="#ADD8E6"/>
  <rect x="150" y="200" width="50" height="50" fill="#B0C4DE"/>
  <rect x="200" y="200" width="50" height="50" fill="#87CEEB"/>
</svg>
```
![cp](https://res.cloudinary.com/ds574fco0/image/upload/v1671547772/live/santa-dashboard/cp_qhnmil.svg)  

### can you create couple of gradients in SVG for Christmas
Sure! Here are a couple of gradients that you can use in your SVG graphics for Christmas:   

1. A gradient going from red to green:  
```SVG
<svg width="250" height="250">
  <linearGradient id="gradient1" x1="0" y1="0" x2="100%" y2="0">
    <stop offset="0" stop-color="#FF0000"/>
    <stop offset="100%" stop-color="#00FF00"/>
  </linearGradient>
  <rect x="50" y="50" width="150" height="150" fill="url(#gradient1)"/>
</svg>
```
![g1](https://res.cloudinary.com/ds574fco0/image/upload/v1671548055/live/santa-dashboard/g1_xfzghn.svg)       
2. A gradient going from white to silver:  
```SVG
<svg width="250" height="250">
  <linearGradient id="gradient2" x1="0" y1="0" x2="100%" y2="0">
    <stop offset="0" stop-color="#FFFFFF"/>
    <stop offset="100%" stop-color="#C0C0C0"/>
  </linearGradient>
  <rect x="50" y="50" width="150" height="150" fill="url(#gradient2)"/>
</svg>
```
![g2](https://res.cloudinary.com/ds574fco0/image/upload/v1671548158/live/santa-dashboard/g2_a4tsvn.svg)   

## Ornaments

### can you create a Christmas decoration in SVG
```SVG
<svg width="250" height="250">
  <!-- Christmas tree -->
  <path d="M125 200 L100 50 L150 50 L125 200 Z" fill="#006400"/>
  
  <!-- Ornaments -->
  <circle cx="112.5" cy="75" r="12.5" fill="#FFA500"/>
  <circle cx="137.5" cy="75" r="12.5" fill="#FFA500"/>
  <circle cx="125" cy="112.5" r="12.5" fill="#FFA500"/>
  
  <!-- Star on top of tree -->
  <polygon points="125 25, 137.5 50, 150 25, 162.5 50, 125 50, 87.5 50, 100 25, 112.5 50" fill="#FFFF00"/>
</svg>
```
![tree](https://res.cloudinary.com/ds574fco0/image/upload/v1671548516/live/santa-dashboard/t1_ege6kn.svg)     
This SVG graphic includes a Christmas tree, three ornaments, and a star on top of the tree. You can customize this decoration by adjusting the colors, sizes, and shapes of the different elements. For example, you could add more ornaments or lights to the tree, or change the shape of the star. You can also add additional elements like presents or a Christmas wreath to create a more complete scene.  
### awesome! can  you create another that is not a Christmas tree

```SVG
<svg width="250" height="250">
  <!-- Snowman -->
  <circle cx="125" cy="100" r="50" fill="#FFFFFF"/>
  <circle cx="125" cy="200" r="40" fill="#FFFFFF"/>
  <circle cx="125" cy="250" r="30" fill="#FFFFFF"/>
  
  <!-- Eyes and nose -->
  <circle cx="110" cy="240" r="5" fill="#000000"/>
  <circle cx="140" cy="240" r="5" fill="#000000"/>
  <rect x="123" y="230" width="4" height="10" fill="#FF4500"/>
  
  <!-- Hat -->
  <rect x="105" y="210" width="40" height="20" fill="#000000"/>
  <rect x="115" y="200" width="20" height="10" fill="#000000"/>
  
  <!-- Scarf -->
  <rect x="105" y="160" width="40" height="40" fill="#0000FF"/>
</svg>
```
![snowman](https://res.cloudinary.com/ds574fco0/image/upload/v1671548726/live/santa-dashboard/snowman_slbczk.svg)      
This SVG graphic includes a snowman with a hat, scarf, and facial features. You can customize this graphic by adjusting the colors, sizes, and shapes of the different elements. For example, you could add a carrot nose or buttons to the snowman, or give him a different hat or scarf. You can also add additional elements like snowflakes or a background scene to create a more complete image.

### can you create a Santa in SVG
```SVG
<svg width="100" height="100">
  <circle cx="50" cy="50" r="50" fill="#FFB6C1"/>
  <rect x="30" y="65" width="40" height="30" fill="#000000"/>
  <circle cx="35" cy="35" r="10" fill="#FFFFFF"/>
  <circle cx="65" cy="35" r="10" fill="#FFFFFF"/>
  <path d="M 50,80 A 20,20 0 0,1 70,80" stroke="#000000" stroke-width="2" fill="none"/>
</svg>
```
![santa](https://res.cloudinary.com/ds574fco0/image/upload/v1671549873/santa_t2tq84.svg)  

## Logic
### can you create 4 blue circles and 2 red circles on a line in SVG where same colors are next to each other
```SVG
<svg width="200" height="50">
  <circle cx="25" cy="25" r="20" fill="#0000FF"/>
  <circle cx="50" cy="25" r="20" fill="#0000FF"/>
  <circle cx="75" cy="25" r="20" fill="#FF0000"/>
  <circle cx="100" cy="25" r="20" fill="#FF0000"/>
  <circle cx="125" cy="25" r="20" fill="#0000FF"/>
  <circle cx="150" cy="25" r="20" fill="#0000FF"/>
</svg>
```
![t1](https://res.cloudinary.com/ds574fco0/image/upload/v1671550135/live/santa-dashboard/color_1_hwtxpm.svg)    

### can you create 4 green circles and 3 yellow circles on a line in SVG where same colors are not next to each other   
```SVG
<svg width="225" height="50">
  <circle cx="25" cy="25" r="20" fill="#00FF00"/>
  <circle cx="50" cy="25" r="20" fill="#FFFF00"/>
  <circle cx="75" cy="25" r="20" fill="#00FF00"/>
  <circle cx="100" cy="25" r="20" fill="#FFFF00"/>
  <circle cx="125" cy="25" r="20" fill="#00FF00"/>
  <circle cx="150" cy="25" r="20" fill="#FFFF00"/>
  <circle cx="175" cy="25" r="20" fill="#FFFF00"/>
</svg>

```
![t2](https://res.cloudinary.com/ds574fco0/image/upload/v1671550365/live/santa-dashboard/t2_brmknh.svg)    
This code will create an SVG image that is 225 pixels wide and 50 pixels tall. It will contain seven circles arranged in a line, with four green circles interspersed with three yellow circles. The circles are positioned horizontally along the x-axis, with the x-coordinate of each circle's center point increasing by 25 pixels. The y-coordinate of each circle's center point is 25 pixels, which positions them vertically along the y-axis. 

### create an octagon in SVG and add a different color circle or triangle at each vertex
```SVG
<svg width="200" height="200">
  <polygon points="100,0 150,38 150,62 100,100 50,62 50,38" fill="#EEEEEE"/>
  <circle cx="100" cy="0" r="12" fill="#0000FF"/>
  <circle cx="150" cy="38" r="12" fill="#00FF00"/>
  <circle cx="150" cy="62" r="12" fill="#FFFF00"/>
  <circle cx="100" cy="100" r="12" fill="#FF0000"/>
  <circle cx="50" cy="62" r="12" fill="#FF00FF"/>
  <circle cx="50" cy="38" r="12" fill="#00FFFF"/>
  <polygon points="88,12 112,12 125,25 112,38 88,38 75,25" fill="#000000"/>
</svg>
```
![o1](https://res.cloudinary.com/ds574fco0/image/upload/v1671550678/live/santa-dashboard/o1_ue9a9b.svg)   
This code will create an SVG image that is 200 pixels wide and 200 pixels tall. It will contain an octagon, with a different colored circle or triangle at each vertex. The octagon is created using a polygon element, with the points attribute specifying the x- and y-coordinates of each vertex. The circles are positioned at the vertices of the octagon using the cx and cy attributes to specify the x- and y-coordinates of the center point. The triangles are created using another polygon element, with the points attribute specifying the x- and y-coordinates of each vertex.    
### create an octagon in SVG and add a different color circle or triangle at each edge  
```SVG
<svg width="200" height="200">
  <polygon points="100,0 150,38 150,62 100,100 50,62 50,38" fill="#EEEEEE"/>
  <circle cx="125" cy="19" r="12" fill="#0000FF"/>
  <circle cx="150" cy="50" r="12" fill="#00FF00"/>
  <circle cx="125" cy="81" r="12" fill="#FFFF00"/>
  <circle cx="75" cy="81" r="12" fill="#FF0000"/>
  <circle cx="50" cy="50" r="12" fill="#FF00FF"/>
  <circle cx="75" cy="19" r="12" fill="#00FFFF"/>
  <polygon points="88,12 112,12 125,25 112,38 88,38 75,25" fill="#000000"/>
</svg>
```
![o2](https://res.cloudinary.com/ds574fco0/image/upload/v1671550866/live/santa-dashboard/o2_wyztwy.svg)
