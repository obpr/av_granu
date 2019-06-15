# AVGRANU

Play music with video samples.
Realize live montages and generative installations.
Choose sounds and vidéos and build interactions between 
- Two audio/video tracks 
- Sound analyse modules,  
- Time stresh modules 
- Synthetizers 
- Step Sequencers

(https://obpr.balik.network)



# Step sequencers 

Two Step sequencers generating number sequence
according to


- A number sequence of time
- A number sequence of itération
- A number sequence of progressivity
- A number sequence to be added or subtract

Apply the datas to:
- The position of the loop (4)
- The Pitch and the speed simultaneously (5)
- The speed only (5) to the pitch only (6)
- Synthetizers (7)

# `$` = value, each step got a value
 
# [=IT]
- Play all `$` of time (all `$` of Step sequencerT)
at each value of the general Step Sequencer (top line) ... allT $ / G $
- If it is not triggered = Play a $ of the Step sequencerT
at every `$` of the general sequencer Step ... T $ / G $

# [≠IT]
- Change steps on the step sequencer (s) in accordance with a fixed $ of time (1000) by default).
- + Column still on the right: go to the value gradually (1000) by default)

# [%T]
- Divides time by the $ from Step Sequencer IT ... T $% IT

# [/Tb/]
Receive the time of Step sequencer B

# [A]
On/off

# [next]
Step forward

# [ø]
Reverse steps off and steps on

# [><]
Send a step on two opposite values

# [>>]
Move linearly on the sequence.
- One step all 6.25$ (100%16 = 6.25)
- if the tempo = loop lenght of the sequence%10

# [O]
Turn this step mute


## Selectors and modulation

Choose position(s) to the starting point of the loop
- Add value to this position(s)
- Move the postion(s) along the whole sequence
- Apply enveloppe to sound track and opacity to video layer


## Gate
Set the position of the playhead where to start the playback loop

# [raw]
raw data  A or B                 

# [A@]
Make a loop on the fly and change position with Step sequencers

# [@re]
Call back the loop made in [A@]* 

# *When released, read what is after the loop chronologically
or with the [@A] mode go back where you were  
at your last [@re]

# [>ø]
Press on, press off (midi mod)

# [loc]
Lock selected source (midi mod)

If you choose to send files triggered by A or B or randomly with [BB](A) or[ BB1](B) the sample sent will be played at its beginning

#  [Trg] and [Bng]
Auto-receive On/off step and send enveloppe to
the sound selected.

# [Trg]
On/off step 

# [Bng]
send enveloppe to
the sound selected

# [<<<]
Send on/off step and set enveloppe from sources selected in 
s&p, speed, or pitch

# [ø]
Trigger the Step sequencer [A] or [B] as selected in
s&p, speed, or pitch


## Audio modulations

- Speed and pitch (50 = 0= stop, 75= go forward , 25= go back)
- Speed only (50 = 0= stop, 75= go forward , 25= go back)
- Pitch only (0 = default)

Left ’s 2 columns
- select data source

# [bck]
Back to default $ after selection released 

# [O] 
Go back to default $
# slider
set value

Choose data source 
# [A], [B], [‘’a] or [‘’b]

Right’s 2 columns
- Module data from the left ’s 2 columns

# [44]
choose between 44100/88200 hz

# [O] 
Go back to default $
slider: set  modulation value

Choose data source 
# [A], [B], [‘’a] or [‘’b]


## Time stretching until drone

Advance your number sequence, pattern, over the entire sample

Make the pattern you are making with Stepseq A or B sliding along the loop lenght more a less rapidly.
- Select entry point in the sample
- Select exit point
- Select strecthing value

Analyse silences and attacks in the  audio signal of sampler or synthetizer
- Send the values as 
# [‘’a] or [‘’b] 
Select a source
# [A]
track AV left 
# [C]
upper synthetiser in purewave-synth
# [sctch]
Mode scratch
suite de valeurs opposées 0-100, 25-75 etc
Sensibility
Progressivity
# [stp]
Mode steps
numbers sequence
number of step$ 1 to 5


## Files selection

Select audio and vidéo loop
- Call bank or single audio and vidéo files.

- Data bank video
- Data bank AV
- Data bank audio
- Link A&V selection

- Select the file number..
- Open browser
- Select the file with A or B
- One random selection
- One random selection
under the speed of Step sequencer [BB](A) or[ BB1](B)
- clear Drop down menu
- Open browser
- Drop down menu


## Video settings

Set video specifications
- dimension, frame rate, incrustations and image modulations

- Threshold: Turn pixel transparent according to the color
- Change height and width
- Change only width
- Change only height
- Change ratio height/width
- Get dimension of the video sample
- Change XYZ
- Contrast
- Saturation
- Motion blur

On/off
Receive On/off
Invert color
Audio control opacity
 
 
 # trop-simple
## Un projet simple

- Alors tu fais le malin!?
- C'est dur? Tu veux dire duRE!?
- D'écrire 
- Comme çà ?


## Écrire un manuel en Markdown

- C'est pas
- Si compliqué

## Tout le monde peut participer

- Parce que c'est trop simple

# La syntaxe ?

- Elle est décrite [dans les spécifications de Markdown](https://daringfireball.net/projects/markdown/syntax) (y'en a pour 25 minutes de lecture)

# Comment participer ?

- Il faut cliquer sur [le stylo là haut pour éditer la page](https://github.com/smonff/trop-simple/edit/master/README.md)
- Il ne faut pas hésiter à regarder [le code source](https://raw.githubusercontent.com/smonff/trop-simple/master/README.md)
- Il est possible décrire [des livres entiers en utilisant ce principe](https://github.com/progit/progit2/tree/master/book)

