
Projects around or involving bikes/bicycles.

I worked for 6 years a bike salesman and mechanic at
Din Sykkel / [Sykkellåven](http://www.sykkellaven.no/) in Tønsberg while studying.

Tools
=====

Casette removal tool
---------------------

For Shimano, CS-HS80-9 and similar.


Ideas
=====

Electricity generator
-----------------------

To keep in shape while being on the computer, and make the electricity useful instead of just going to.

Coupling:

Store-bought generators/loads are often coupled onto the tyre.
This wears a lot on the tyre, is not suitable for mountain-bike type tyres.
Instead we propose a replacement "wheel", where the generator is coupled 
onto the hub/casette or using a replacement hub.
Depending on motor/generator, gearing might be neccesary.

Motor:

Motor can be a 12/24V alternator from car/MC, sourced or recycled locally.
[Biltema](http://www.biltema.no/no/Bil---MC/Bilreservedeler/Elektrisk-anlegg/Dynamo/)
Alternative is to use brushless motor from RC/multicopter,
potentially requiring more complex charge control. HobbyKing etc.
Or ultimately, to be able to 3d-print the motor itself.

Many of the thing learned here could be useful for similar systems,
off-grid solutions like human powered water pumps etc.
Or to make an electric bicycle, or dual-purpose system,
which can both for excercise/generation and for transportation/motor.


TODO:

* Design initial concept models


3d-printed tools
-------------------

Exists Thingiverse

* Pedal wrench 15mm [1](http://www.thingiverse.com/thing:90605)
* Pads for keeping hydraulic brakes safe when disc is out. [1](http://www.thingiverse.com/thing:471166)
* Crank bolt tool [1](http://www.thingiverse.com/thing:92353)
* Ratchet/thumb-screw 1/4" bits (for 8,9,10mm bolts) [1](http://www.thingiverse.com/thing:207389)

TODO

* thumb-screw for 1/4" bits 

3d-printed parts
------------------

With the eventual goal of being able to print, everything needed for a practical bike.
On a standard 20x20x20cm RepRap-style printer, not specialized machine.
Bigger structural elements like the frame, is considered a separate project, see below.

Some things are quite safety critical, like brake, propulsion and steering system.



Exists on Thingiverse, by other people:

* Chain protection rings

Thingiverse searches:

* [Shimano](http://www.thingiverse.com/search/page:1?q=shimano&sa=)
* [Bike](http://www.thingiverse.com/search?q=bike&sa=)
* [Bicycle](http://www.thingiverse.com/search?q=bicycle&sa=)

TODO:

* Replacement covers for Shimano shifters
* Indexed Shimano/STI shifter.
* Drop-out. Hugely beneficial to 3d-print, due to hundreds of variations
* Casette offset ring, for fitting 6-7gear casette on 8/9/10 hub
* Remotes for suspension-forks
* Hub, using standard ball bearings. 608Z with M8 threaded rod axel?
* Freehub/wheel, using some ratchet mechanism. Inspiration: [1](http://www.thingiverse.com/thing:28805)
* Belt-based power transmission

Work by other people:

* [3d-printed friction gear lever](https://www.youtube.com/watch?v=fLMA-8aSsDM)

Research:

* Shimano patent on sprokets [US patent no 4889521](http://www.google.com/patents/US4889521) expired in 2008.
* Bike [chains](http://en.wikipedia.org/wiki/Bicycle_chain#Sizes)/[sprokets](http://www.gizmology.net/sprockets.htm)
are #40 of ISO, 12.7mm pitch, 7.65mm roller diam, roller width 1/8" or 3/32", extern thickness depending on N-speed
* [Rear deraillurs](http://en.wikipedia.org/wiki/Derailleur_gears#Rear_derailleurs)
* Radius of sproked with N teeth of given pitch: r=(N*pitch)/(2*pi)
* [Indexed shifting reference](http://en.wikibooks.org/wiki/Bicycles/Maintenance_and_Repair/Gear-changing_Dimensions)
* Rachet+prawl, mechanism to convert rotation->linear action:
[Thingiverse](http://www.thingiverse.com/search?q=Ratchet&sa=)
[Wikipedia](http://en.wikipedia.org/wiki/Ratchet_(device))
* [Belt-driven bicycle](http://en.wikipedia.org/wiki/Belt-driven_bicycle)
* Looks like a drop-out is 10-25 USD to 3d-print in plastic (Shapeoko, Ponoko, Sculpteo)

3d-printed bicycle structure
----------------

Bigger structural elements are particularly challenging to 3d-print on a
standard ~20x20x20cm RepRap-style printer.
Both due to the sizes of the objects, and requirements for structural integrity.

Several plastic-based (usually injection molded) bikes have been attempted,
[most failed](http://en.wikipedia.org/wiki/Plastic_bicycle).

Ideas:

* Use glass/carbon/bio fiber+resin reinforcement on 3d-printed shell.
Vacuum-bag-form for production speed.

Parts:

* Frame
* Wheels
* Fork for frontwheel
* Seatpost
* Handlebars and stem
* Crank-arms

Crank-arms:

A conceptual sketch of a 175mm crank-arm (25 mm tall), using the simplest possible geometry,
estimated to 2-3 hours print time on an Ultimaker.
In addition to the strength of the arm itself,
the connections to both the bottom bracket and the pedals are challenging.
On the bottom bracket side, a system like ISIS with higher surface area might
be preferrable over the typical 4-sided press-fit.

Pedal connections could be enforced with a steel insert with threads,
as found on commercial composite crankarms. 
Preferably one could thread directly in printed part.
Using custom pedals, one could put the bearings into the crank arm instead of pedal,
allowing to avoid threads in the arm.

Due to problems with poor layer bonding, making Hollowtech style cranks seems very hard.


Frame:

A medium (54cps) frame standard hybrid frame is approx 2.7 meters of tubing, front-fork excluded.
2800mm/200mm = 14 pieces.
Assuming a 60 mm outer diameter for all tubes, with single wall takes approx 1.5 hour per piece,
for a total of 14*1.5 = 21 hours printing time, or ~6 hours on 4 printers.

Here is couple of videos of failed headtube design
[1](https://www.youtube.com/watch?v=4stXilZLl7o),
[2](https://www.youtube.com/watch?v=OgAwC1GCYJQ)


Wheels:

A standard 26" inch wheel (559mm) would require approx 9 pieces.
Can be done with just one joint between center piece and the rim.
A 622mm wheel would probably require 16, and require multiple joints, and thus much less suitable.
With semi-slim tyres ~1.75"/47mm, the rim width for a clincher profile should be 19-25mm.

* http://en.wikipedia.org/wiki/ISO_5775
* [Clincer rim profile](http://en.wikipedia.org/wiki/Bicycle_tire#/media/File:Sezione_cerchione_bicicletta.svg)
* [Carbon MTB wheel profile, DT Swiss](http://en.wikipedia.org/wiki/File:Carbon_composite_MTB_wheel.JPG)


