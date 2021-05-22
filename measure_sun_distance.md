# How to measure a distance between earth and the sun
  * 3rd-century BC Aristarchus used half illuminated Moon (indicating that it formed a right triangle with the Earth and the Sun) and triangulation to estimate the distance)
  * 1653 Christiaan Huygens used triangulation of sun, venus, and earth. Again he used half illuminated venus.
    * src: http://www.badastronomy.com/mad/1996/au.html 
  * 1672 Giovanni Casini used parallax on Mars from Paris and Cayenne, French Guiana.
  
  * Attempt of the Royal Society leading to Captain Cook expedition 1769-1779 in Tahiti
    * C. Herdendorf, Captain James Cook and the transits of mercury and venus. Journal of Pacific History 1986
    * How could transit of Venus helps solve a distance between earth and the sun
      * "To use the transits as an accurate measure of the distance from the Earth to the Sun, observations had to be made from widely-spaced locations."
      * "Edmond Halley was the first to develop a method for making the complex calculations. He published his most important paper on the transit of Venus in 1716, knowing he would not live long enough to witness the next transit in 1761."
      * "The favoured instruments of the major British expeditions of the 18th century were reflecting telescopes, which use a mirror rather than a lens as the primary optical component. The preferred supplier was James Short, who specialised exclusively in the manufacture of reflectors."
      * "The telescopes were used together with an expeditions clocks to see and time the key moments of a transit. By adding a micrometer, a telescope could also be converted into a measuring instrument, so that small angles such as the diameter of Venus could be accurately determined."
      * "Those observers sent on expeditions were travelling to sites selected primarily for their geographical position." 
      * "But factors such as climate and the current relations with indigenous peoples and other European nations were also factors in the process of selection. War between Britain and France disrupted the plans of some observers in 1761." 
      * "Beyond their astronomical mission, the larger expeditions provided opportunities for more extensive exploration. The botanist Joseph Banks launched his career as a natural historian on Captain Cook’s voyage, returning as a celebrity with new species and dramatic tales of discovery."
      * "... Rather than converging towards a single value for the distance from the Earth to the Sun, different astronomers arrived at slightly different results. This spread of values left the sense that “the most noble problem in nature” was yet to be conclusively settled.
      * "Edmond Halley had envisaged a method in which observers could agree on the timing of a transit to the precise second." 
      * "The most crucial moment was “internal contact”, when Venus should have been a perfect circle touching the edge of the Sun. Instead, it often appeared elongated and distorted. How could a precise instant of contact be established when Venus was afflicted with this problem of the “black drop”?"
      * "Even if an expedition’s observers could reconcile their own results, there was the further problem of comparing them with others from around the world."
      * "Working with a mass of data required not just mathematical proficiency and stamina, but the ability to select. Precision astronomy here depended ultimately on individual judgement."
      * "**The current value of the Earth-Sun distance is based on radar measurements**, with a precision and accuracy undreamt of by earlier investigators."
      * src: https://www.mhs.ox.ac.uk/venus/html/exhibition/expeditions.htm
      * 
      * "Recording the exact moment of the phases proved to be impossible due to a phenomenon called the Black drop effect. ...  ... Recent studies now reveal that it is actually turbulence in the Earth's atmosphere that leads to the smearing of the image of Venus."
      * src: https://en.wikipedia.org/wiki/1769_transit_of_Venus_observed_from_Tahiti#Choosing_an_island,_a_ship_and_a_Captain
      * 
      
      > "In these methods you will compare tracks of Mercury across the disc of the Sun as seen from two different observing sites. Using the two sets of tracks you can determine the angular shift, or parallax, (in seconds of arc, between the two tracks at one particular time). The distance between the Earth and the Sun can be determined with, the value of the angular shift and the distance between the two observing sites.

      > Whilst the mathematics simply involves trigonometry, the conceptualization of what is happening and what needs to be taken into account is not trivial, therefore to help if needed, a spreadsheet has also been provided that will compute the result for you."
      * src: https://sci.esa.int/web/education/-/57806-calculating-the-earth-sun-distance-from-transits

      > "The Sun must never be viewed directly, and you must never look through the eyepiece of a telescope to view the Sun.
      > The safest way to view the transit of Mercury is to project the Sun onto a shaded white surface using a telescope or a pair of binoculars.
      * src: http://www.esa.int/Education/Teachers_Corner/Observing_tips

![Richmond Venus Transit](https://github.com/tatpongkatanyukul/Adventures-of-CPG-in-The-World-of-Problem-Solving/raw/main/RichmondExplain_transit_trig.gif)

> The simple example which follows is intended only to give you a flavor for the method; real astronomers in the eighteenth and nineteenth centuries included a host of complications and subtleties in their observations, measurements and analysis.

![Richmond Venus Transit](https://github.com/tatpongkatanyukul/Adventures-of-CPG-in-The-World-of-Problem-Solving/raw/main/RichmondExplain_two_paths.gif)

> Measure the parallax angle: "Just how large is the apparent shift in the position of Venus? This shift is called the "parallax angle", or "parallax" for short."

> "To be precise, the diameter of the Sun during this transit is 1891 arcseconds. There are 60 arcseconds in one arcminute, and 60 arcminutes in one degree, which means 3600 arcseconds in one degree. Astronomers use arcseconds to measure small angles; it's more convenient to write '10 arcseconds' than '0.00277 degrees.'"

  * "Use the Sun as a yardstick: it is 1891 arcseconds in diameter"
  * "Measure the north-south shift of Venus as seen from the two locations"
  * "Express this shift in arcseconds and in degrees"

> "As you may recall, Kepler and other astronomers had figured out the relative sizes of the planetary orbits:"

| Planet    | Orbital period (years)|  Orbital semi-major axis (AU)| 
|-----------|----------------|--------------------------|
|  Mercury  |   0.241        |       0.387              |
|  Venus    |   0.615        |       0.723              |    
|  Earth    |   1.0          |       1.0                |
|  Mars     |   1.88         |       1.52               |
|  Jupiter  |  11.86         |       5.20               |
|  Saturn   |  29.46         |       9.55               |

  * "Based on your value for the Earth-Venus distance, and the orbital radii shown above, calculate the size of the Astronomical Unit."
    * That is, AU * 0.615 = x, where x is the distance between earth and Venus: x = d/(2 arctan(theta/2)) when d is a distance between 2 observation points (e.g., Tahiti and Norway) and theta is the parallax angle. 

src: [Michael Richmond. Using a transit of Venus to determine the Astronomical Unit: a simple example. June 7, 2004 (retrieved May 22, 2021)](http://spiff.rit.edu/classes/phys445/gettys/venus_ex/venus_ex.html)
  * Good! but my itches now are:
    * 1. How do they come up with "the diameter of the Sun during this transit is 1891 arcseconds"?
      * "The angular diameter of an object is the angle the object makes (subtends) as seen by an observer. This is demonstrated in the diagram below, where the angular diameter of the object appears larger to an observer at A (closer to the object) than to an observer at B."
      * ![angular diameter](https://github.com/tatpongkatanyukul/Adventures-of-CPG-in-The-World-of-Problem-Solving/raw/main/angulardiameterA.gif)
      * For an observer on the Earth, the angular diameter of the Moon and the Sun are quite similar ( ~ 0.5 degree = 30 arcmin). In reality, the Sun’s physical diameter is 400 times bigger than the Moon, while the Moon is ~ 400 times closer to the Earth.
      * src: https://astronomy.swin.edu.au/cosmos/a/Angular+Diameter
        * OK! Clear! We can build an apparatus to measure it, e.g., having an object close to the telescope that shadow the sun, move the shadow edge to edge of the sun and measure the distance of the move and the distance between the object and the telescope. Then, we can work out the angle. 
    * 2. How do Kepler come up with a relation between orbital period and AU?
      * Perhaps, triangulation with the half-illuminated planet, e.g., venus.

![Venus Triangulation](https://github.com/tatpongkatanyukul/Adventures-of-CPG-in-The-World-of-Problem-Solving/raw/main/triangulation_dx.png)

# Parallax

## Introduction to Triangulation

Suppose you were trying to measure the width of a canyon from your side to the distant canyon wall. You couldn't pace the distance. Could you come up with a way to make this measurement safely?

Surveyors and geologists encounter this kind of problem all the time, and over the course of centuries, they have found a simple way to sole this problem. They use a method called 'triangulation'. Here's how it works:

![Triangulation](https://github.com/tatpongkatanyukul/Adventures-of-CPG-in-The-World-of-Problem-Solving/raw/main/triangulation.jpg)

In ordinary land surveying, imagine a distant mountain peak and two observers are located at 'A' and 'B' separated by a few miles (the length 'S'). The base angles at A and B can be measured with an instrument called a theodolite. By knowing the base distance A to B, and the baseline distance S, the distance to the peak can be worked out with a simple scaled drawing or with trigonometry.

## Introduction to Parallax

Suppose it was hard for you to measure the two base angles in the triangulation method. This could easily happen if the object were so far away that your instrument could not accurately discern that these angles were different than 90 degrees. For example, if the object is 10 miles away, and your baseline is only 5 feet long, the two base angles would have a measure of 89.9946 degrees. This angle differs from 90 degrees by only 0.0044 degrees which equals 16 seconds of arc (there are 60 minutes or arc/degree x 60 seconds of arc/minute of arc = 3600 seconds of arc per degree!) This would be a very difficult angle to measure even with very expensive modern surveying equipment!

Astronomers run into this problem all the time. To solve this problem, they don't bother measuring the base angles at all. Instead, they measure the vertex angle in the triangle. It turns out that this angle is very easily measured using photographic techniques. The method is called trigonometric parallax or just 'parallax' for short. Here's how it works:


Extend your arm in front of you, hold your thumb up, and alternately open and close your eyes. You will see your thumb's position move against the more distant background in front of you. Astronomers call this the parallax shift angle as the figure below illustrates:

![Parallax](https://github.com/tatpongkatanyukul/Adventures-of-CPG-in-The-World-of-Problem-Solving/raw/main/parallax.gif)


From the above figure, by knowing the distance from your nose to one of your eyes, R, and this Parallax Shift angle in degrees, you can calculate the distance to your thumb (D)! The formula that you use is: tan(P/2) = R / D

Note ... **The Parallax Shift angle** is actually twice as large as the angle used in computing the Tangent of R/D.

"... Kepler's Third Law' which states that the orbital period-squared equals the distance to the sun-cubed."

> In 1663, Rev. James Gregory who was an astronomer and mathematician considered, suggested that a more accurate measurement of the Earth-Sun distance could be made. He showed how this distance could be measured from observations of the transit of Venus made from various widely separate geographical locations.  A few years later, Sir Edmund Halley, made the same suggestion in 1677, and published the details of this technique in 1716. Sir Edmund Halley described in detail how scientists from various nations could observe the upcoming 1761 and 1769 transits of Venus from many parts of the world. From the parallax shifts they would measure, they would be able to measure this distance from the Earth to Venus and the sun with near-perfect accuracy.


The TRACE satellite orbits Earth and has its sensors trained on the surface of the Sun to search for solar flares. The changing perspective of the location of Venus in its orbit also leads to a parallax shift. Here is a close-up of the consecutive images of Venus as it traveled across the sun on June 8, 2004:

![Venus Trace](https://github.com/tatpongkatanyukul/Adventures-of-CPG-in-The-World-of-Problem-Solving/raw/main/nasa_Venus_Trace2004.gif)

The composite shows the position of Venus roughly every 450 seconds.

Teacher Note: By counting the number of exposures from peak to peak (about 13) students can calculate that the orbit period for this satellite is 5850 seconds = 97.5 minutes, which is typical for satellites orbiting within a few hundred kilometers of earth's surface.

### Method 2: Parallax calculation using image analysis

We can also use the TRACE Venus Transit image to determine the distance to Venus. To do this, we first have to determine the scale of the print so we can measure the parallax angle q. 

#### Procedure:
Step 1: Print the TRACE image above on a separate piece of paper.

Step 2: Cut the image out, and carefully tape it by its outer edge to a large sheet of paper. To give yourself room for Step 2, place the image above the center of the page, half way to its top edge.

Step 3: Through trial and error using a string, a tack and a pencil, draw a circle whose perimeter passes exactly across the edges of the solar disk shown in the picture. Measure the diameter of this solar circle in millimeters. A value near 287 millimeters is reasonable if you are working from the normal print version of the above image.

Step 4: At the time of the transit, the angular diameter of the sun is known by astronomers to be 0.53 degrees (1891 arcseconds) . Calculate the scale of the solar circle in degrees per millimeter by dividing 0.53 degrees by the measured diameter of the sun circle (287 millimeters) . Call this number 'A'. A value near 0.0018 degrees per millimeter is appropriate.

src: https://spacemath.gsfc.nasa.gov/transits/TRACEvenus.html
