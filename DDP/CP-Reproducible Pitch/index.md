---
title       : Course Project - Simple Reproducible Pitch in Slidify
subtitle    : Coursera-Developing Data Products
author      : Alexander Calzadilla Mendez
job         : Data Entry Analyst at Community Health of South Florida
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, quiz, bootstrap] # {mathjax, quiz, bootstrap}
ext_widgets : {rCharts: [libraries/nvd3]}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

---

## Introduction

This is a very simple demonstrative work about the use of Slidify with differents
examples, in this case useful for interactive education, very easy for to play with the presentation in an interactive manner.
Two slides, is about simple math, the next two slides is about science (physics)





Press space bar or any arrow key to continue or go back


---&radio

## from the "Prince of Mathematicians"

Simple Math for very smart kids, try to solve this in less than 2 minutes

What is 1 + 2 + 3 + 4 + 5 + .........+ 96 + 97 + 98 + 99 + 100?

1. 3195

2. 2300

3. _5050_

4. 4350



Press space bar or any arrow key to continue or go back


***.hint
First try for pairs 1+99, 2+98, 3+97,....51+49.. and hopfully find the way to solve.

***.explanation
Carl Friedrich Gauss is sometimes referred to as the "Prince of Mathematicians" was a child prodigy. There are many anecdotes concerning his precocity as a child, and he made his first ground-breaking mathematical discoveries while still a teenager. 
At the age of 7, he is reported to have amazed his teachers by summing the integers from 1 to 100 almost instantly (having quickly spotted that the sum was actually 50 pairs of numbers, with each pair summing to 101, total 5,050). By the age of 12, he was already attending gymnasium and criticizing Euclid's geometry.

---
## simple R code that is evaluated when slidify


```r
## With this simple R code we can sum all number in the previus slide
sum(1:100)
```

```
## [1] 5050
```

```r
## a formula to do the manual calculations is ( N*(N+1)/2 ) with N the last number in the serie:

100*(101)/2
```

```
## [1] 5050
```



--- .class #id, &radio

## Simple cuadratic equations

Try to solve the following equation of second degree.

$$3 x^2 - 2 x - 8 = 0$$

Solutions:

1. x1= 1 , x2= 3

2. x1= 1/2, x2= 2

3. _x1= 2, x2= -4/3_


Press space bar or any arrow key to continue or go back




***.hint
 use the following formula to solve $$x1,2= \frac{-b\pm\sqrt{b^2 - 4 a c}}{2a}$$

***.explanation
In elementary algebra, a quadratic equation is any equation having the form

    a x^2 + b x + c = 0

where x represents an unknown, and a, b, and c represent known numbers such that a is not equal to 0. If a = 0, then the equation is linear, not quadratic. The numbers a, b, and c are the coefficients of the equation, and may be distinguished by calling them, respectively, the quadratic coefficient, the linear coefficient and the constant or free term.

---&radio

## Science Quizzes for Kids

Light from the Sun reaches us in nearly

1.  2 minutes

2.  4 minutes

3. _8 minutes_

4. 16 minutes



Press space bar or any arrow key to continue or go back


(data: The average distance between the Sun and the Earth is about  S = 92 935 700 miles, use for the speed of light, V = 670 616 629 miles per hour)

***.hint
Use for the calculation the formula  Velocity = Space / time  (V = S / t)

***.explanation

Consult the following link: "http://www.speed-light.info/measure/speed_of_light_history.htm"



---&radio

## Science Quizzes for Kids

Why is the sky blue?

1. because the sunlight was reflected in the atmosphere by the sea.

2. because is the most beatiful color

3. _because molecules in the air scatter blue light from the sun more than they scatter red light._


Press space bar or any arrow key to continue or go back

***.hint
The white light from the sun is a mixture of all colours of the rainbow.  This was demonstrated by Isaac Newton, who used a prism to separate the different colours and so form a spectrum.  The colours of light are distinguished by their different wavelengths.  The visible part of the spectrum ranges from red light with a wavelength of about 720 nm, to violet with a wavelength of about 380 nm, with orange, yellow, green, blue and indigo between.  The three different types of colour receptors in the retina of the human eye respond most strongly to red, green and blue wavelengths, giving us our colour vision.

***.explanation
The first steps towards correctly explaining the colour of the sky were taken by John Tyndall in 1859.  He discovered that when light passes through a clear fluid holding small particles in suspension, the shorter blue wavelengths are scattered more strongly than the red.  This can be demonstrated by shining a beam of white light through a tank of water with a little milk or soap mixed in.  From the side, the beam can be seen by the blue light it scatters; but the light seen directly from the end is reddened after it has passed through the tank.  The scattered light can also be shown to be polarised using a filter of polarised light, just as the sky appears a deeper blue through polaroid sun glasses.

This is most correctly called the Tyndall effect, but it is more commonly known to physicists as Rayleigh scattering-after Lord Rayleigh, who studied it in more detail a few years later.  He showed that the amount of light scattered is inversely proportional to the fourth power of wavelength for sufficiently small particles.

Tyndall and Rayleigh thought that the blue colour of the sky must be due to small particles of dust and droplets of water vapour in the atmosphere.  Even today, people sometimes incorrectly say that this is the case.  Later scientists realised that if this were true, there would be more variation of sky colour with humidity or haze conditions than was actually observed, so they supposed correctly that the molecules of oxygen and nitrogen in the air are sufficient to account for the scattering.  The case was finally settled by Einstein in 1911, who calculated the detailed formula for the scattering of light from molecules; and this was found to be in agreement with experiment.  He was even able to use the calculation as a further verification of Avogadro's number when compared with observation.  The molecules are able to scatter light because the electromagnetic field of the light waves induces electric dipole moments in the molecules.




