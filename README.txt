=========Andrew=Faradays=====================================================
=========Website=Analytics===================================================
=========Music=====Generator=================================================

The idea behind this patch comes from two simple premises:

* Google analytics can export data about my website traffic
* Data + Pure Data = Digital Art

So I played around with my analytics data to bring it into a Pd readable form
and set about sonifying. Playing the data from one website parallel to the 
other in order to have the two hit counters playing a duet. A little visual
data and the effect is completed, almost 3 months of analytics producing some 
interesting patterns and melodies. 

The main variation factor is the pre-mtof multiplication factors, which you can
play with at the top right of the patch. Although I found the data import is a
good start for live coding, giving useful data who's usage you can manipulate 
with the patch.

To open (font is specific to linux machines, unsure of the result on windows):
* Make sure you have pure data installed
* Unzip these three files to a single folder:
  * tahoma.ttf
  * Jointreport.csv
  * WebsiteMusic.pd
* Open WebsiteMusic.pd
* Click the toggle marked 'Start playback'
* To see visualisations, click the bang marked 'Start vis'

================================================================================

Future Aims: 
I would like to see more websites analytics data played through this or similar
patches. Any csv analytics dumps would be most welcome. 

A re-structure of this patch to make it more adaptable may one day be in order,
an abstraction for both synth and gem elements for each dataset would be the next
step.

================================================================================

This is an open source pure data project, if anyone wishes to use it in any form
they are welcome to, although in this case I would like to be acknoledged...
 
Patch started on Friday 23rd September by Andrew James Faraday
