# mandelbrotSet
Quick and dirty Mandelbrot Set made in java. What is the Mandelbrot Set and how is it generated? The Mandlebrot Set is a set of points 
in the complex plane and is generated using the equation f(z) = z^2 + c, where c is an imaginary(complex) number. The image is generated by 
taking each pixel as a coordinate and plugging it into this equation and seeing how quickly the point blows up. Points that diverge to 
infinity are not in the set and colored based on how quickly they blow up, points that converge are inside the set and colored black.

You can get a zoom of about e^-11 before reaching a doubles decimal precision limit. To zoom further more advanced methods must be used.

# Screenshots: 

https://imgur.com/a/8GnFv

# Controls:

Arrow Keys: Move around

Comma and Period (< and >): Zoom out and in respectively.

F and R: decreases and increases the horizontal shift increment. (By a factor of 10)

G and T: decreases and increases the vertical shift increment. (By a factor of 10)

Y and H: decreases and increases the accuracy of how quickly a point diverges. (By a factor of 2)

J and U: decreases and increases the number of interations. (By 25)

K and L: changes color

I and O: changes saturation

P: saves and picture of currently rendered image

Z: toggles information

C: Resets program

# IMPROVEMENTS:

Multi-Threaded

Ditch swing and replace with javafx

Clean up readibility and programming style a bit, document

Find a way to get a better decimal precision than a double (?)
