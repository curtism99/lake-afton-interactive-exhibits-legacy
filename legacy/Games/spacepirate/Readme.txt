*****************************
This file is intended to be read by the observatory staff to make changes in the software.
*****************************

This file is for the Planet Trek game.
There are few zillion jpg with Planet Trek game.
1.jpg ThumbNail of Mercury
2.jpg ThumbNail of Venus
3.jpg ThumbNail of Earth
4.jpg ThumbNail of Mars
5.jpg ThumbNail of Jupiter
6.jpg ThumbNail of Saturn
7.jpg ThumbNail of Uranus
8.jpg ThumbNail of Neptune
9.jpg ThumbNail of Pluto

The game works with the file .../installation_location/DataFiles/Features.txt
The format of the Features.txt file is as follows
Line1:Short Name of the feature say ManyMoons for the Feature "Has more than five moons"
Line2:Complete Name of the feature, say "Has more than five moons", this line qill appeart in the question and the user will be asked to choose a planet which has this feature
Line3:Numbering of planets on which these features are found 134 would mean Mercury, Earth and Mars.
Line4:Comment that appears when a feature is shown to the player.
This pattern is repeated for each feature
Suppose there are 19 features:
This file should have 19*4 =76 lines

Suppose that feature 1 is present on 3 planets, feature 2 is present on 5 planets and so on.
Let us assume that the average number of planets on which a feature is 3.
And there are 19 features. Then there should be 19*3 .jpg files each one showing the feature on the planet.

The naming convention for the jpg is:
the first two letters of the planets name + the short name of the feature + .jpg

The first two letters are
Me for Mercury
Ve for Venus
Ea for Earth
Ma for Mars
Ju for Jupiter
Sa for Saturn
Ur for Uranus
Ne for Neptune
Pt for Pluto

The short name for each feature is as follows:
Water for Liquid Water
Craters for Craters
CarbonDioxide for Carbon dioxide atmosphere
Cold for Temperatures less than -300 degrees F
Hot for Temperatures greater than 600 degrees F
Small for Same size as earth or smaller
AcidClouds for Sulfuric acid clouds
Rocky for Solid, rocky planet
Gaseous for Gaseous Planet
OneMoon for Has at least one moon
ManyMoons for Has more than five moons
Mountains for Mountains
DenseAtmosphere for Dense Atmosphere
Rings for Has Rings
Largest for Largest Planet
Smallest for Smallest Planet
Volcanoes for Volcanoes
FreeOxygen for Free oxygen in atmosphere
OrbitsInLessThanYear for Orbits the Sun in less than one year
OrbitsInMoreThanYear for Orbits the Sun in more than one year
MagneticField for Significant magnetic field
Winds for 1800 kilometer per hour winds
Lightning for Lightining in atmosphere
PolarCaps for Polar caps
ReleaseEnergy for Gives off more energy than receives from the Sun
LargeMoon for Has a moon larger than Mercury
EarthLike for Earth like planet
JupiterLike for Jupiter like planet
NoAtmosphere for Has no atmosphere
Life for Best suited for life
NoMoon for Has no moons
Aurora for Has Aurora (Northern Lghts)
Shrinking for Shrinking a little bit every year
RotatesSlowest for Rotates on its axis slowest
MoonAtmosphere for Has a moon with an atmosphere
LargerEarth for Larger than earth
Seasons for Has noticable seasons
ElongatedOrbit for Elongated orbit
Visited for Visited by earth satellite
Landed for Landed on by earth satellite
RotatesTenHours for Rotates on its axis in about ten hours
RotatesOpposite for Rotates in opposite direction of its orbit
MostMoons for Has more moon than any other planet
LessMoons for Has less than five moons
NeverVisited for Has never been visited by earth satellite
OrbitsSide for Orbits on it's side


*******************************************************************
The line above shows that the scanning portion is differentt from the game
It works with 9 different files
Mercury.txt, Venus.txt, Earth.txt, Mars.txt, Jupiter.txt, Saturn.txt, Uranus.txt, Neptune.txt and Pluto.txt
The format of each file is the same, when we append .jpg to the the first line we get the name of the picture to be loaded.
The next line is the comment that is shown while the scan is going on.
So if you add a new feature add it in the feature.txt file and in all the corrosponding Planet.txt files also.
Similarly if you remove a feature remove it from the features.txt file and also fromt he corrosponding Planet.txt file
********************************************************************

