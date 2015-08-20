# Guitar Circuits

A place for my guitar-related circuits. 

For the moment, I just made some simple circuits to help me in the process of building guitar effects. But, my plans are add more complex circuits, like pedals, on board effects or, even, full amps, in the future.

All of the circuits in this repo are made using the freeware version of the [EAGLE CAD software](http://www.cadsoftusa.com/), which is cross-platform and has no cost for a hobbyist use. You could download it from the [EAGLE download page](http://www.cadsoftusa.com/download-eagle/)

To configure EAGLE I just add the paths of where the repo is cloned to the project and libraries directories in the *Options* > *Directories* menu. Remember, directories are colon separated in EAGLE. A configuration sample is (it is my current configuration ;-) ):

Libraries:
<pre><code>
$EAGLEDIR/lbr:$HOME/Documents/circuits/guitar-circuits/libs/
</pre></code>

Projects:
<pre><code>
$HOME/Documents/circuits:$EAGLEDIR/projects/examples
</pre></code>


## Circuits

### gm-lbr
This is not a circuit it is a library got form [Gaussmarkov website](http://gaussmarkov.net/) (very cool site, check it out). I’m using it because it is oriented to create pedals and fits my needs very well. It is free, but, all the copyrights belongs to Gaussmarkov as he says in his [About page](http://gaussmarkov.net/wordpress/about/).


### true-bypass
This is a tiny board intended to be attached to a heavy duty foot switch and where you connect all the parts of the circuit (effect board, jacks, led, battery clip and power supply). I made it to avoid to have a mess of wires inside of the pedal case. It is a single sided board, and it is very easy to develop at home.

### true-bypass-2.0
This board is based on the previous one but adds the feature of disconect the power supply when the output jack is unpluged. A stereo jack at the output is needed to take that advantadge.

