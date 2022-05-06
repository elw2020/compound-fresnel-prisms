# compound-fresnel-prisms
_What is this project and what is it's purpose?_

This is a program I wrote with VBA (Visual Basic for Applications) for the University of Michigan Kellogg Eye Center Optical Department. The purpose of this application is to aid optical professionals in orienting compound fresnel prisms. 

_Why was this program written?_

The genesis of this idea came from the challenges myself (a former optician) and my colleagues were having orienting compound fresnel prisms on spectacle lenses. There exists no automated solution to do this. Manually, the process involves drawing a right-angle triangle using the prism power values given to you on a prescription. The values of the legs of the triangle reference the vertical and horizontal prism power values. Now, with the hypotenuse of the triangle, one needs to figure out how to orient the fresnel prism against the 180° line that is drawn on the lens in advance. The typical errors that occur with this process are: getting the direction of the fresnel wrong; drawing an accurate triangle by hand; calculating Pythagorean's therom incorrectly (yes, this happens often).

This program takes all of the guesswork out of this process. After entering the data from the prescription, the application calculates Pythagorean's therom, which generates the correct prism strength fresnel to pull. It takes the ratio of both of the triangle legs and returns the corresponding angle. With this base angle, depending on which eye and direction combination selected, the program will then output a line inside of a fresnel template. This line shows you which direction to position your lens on the fresnel.

_What is a fresnel prism anyway?_

A fresnel prism is a thin, transparent plastic sheet, which induces a prismatic effect (it alters the direction of the image entering the eye). Simply put, it bends light. One side consists of a series of angular grooves (prisms) and the other smooth side attaches to the lens of your glasses.

_What does a fresnel prism do in a spectacle lens?_

It helps to correct several visual disorders.

