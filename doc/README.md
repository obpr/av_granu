# AV_GRANU




Play music with video samples.
Realize live montages and generative installations.
Choose sounds and vidéos and build interactions between:
- Two audio/video tracks (right:A left:B)
- (1) Sound analyse modules
- (2) Time stresh modules
- (3) Step Sequencers
- (4) Synthetizers


(https://obpr.balik.network)


- [AV_GRANU](#av_granu)
  - [Step sequencers](#step-sequencers)
    - [`[=IT]`](#it)
    - [`[≠IT]`](#it-1)
    - [`[%T]`](#t)
    - [`[/Tb/]`](#tb)
    - [`[A]`](#a)
    - [`[next]`](#next)
    - [`[ø]`](#)
    - [`[><]`](#-1)
    - [`[>>]`](#-2)
    - [`[O]`](#o)
  - [Selectors and modulations](#selectors-and-modulations)
    - [Gate](#gate)
    - [`[raw]`](#raw)
    - [`[A@]`](#a-1)
    - [`[@re]`](#re)
    - [`[>ø]`](#-3)
    - [`[loc]`](#loc)
    - [ `[Trg]` and `[Bng]`](#-trg-and-bng)
    - [`[Trg]`](#trg)
    - [`[Bng]`](#bng)
    - [`[<<<]`](#-4)
    - [`[ø]`](#-5)
  - [Audio modulations](#audio-modulations)
    - [Left’s 2 columns:](#lefts-2-columns)
      - [Select data source](#select-data-source)
        - [`[bck]`](#bck)
        - [[O]](#o-1)
        - [slider](#slider)
      - [Choose data source](#choose-data-source)
        - [`[A]`, `[B]`, `[‘’a]` or `[‘’b]`](#a-b-a-or-b)
    - [Right’s 2 columns](#rights-2-columns)
      - [Module data from the left ’s 2 columns](#module-data-from-the-left-s-2-columns)
        - [`[44]`](#44)
        - [`[O]`](#o-2)
      - [Choose data source](#choose-data-source-1)
        - [`[A]`, `[B]`, `[‘’a]` or `[‘’b]`](#a-b-a-or-b-1)
  - [Time stretching until drone](#time-stretching-until-drone)
  - [Audio analysis](#audio-analysis)
    - [Select a source](#select-a-source)
      - [`[A]`](#a-2)
      - [`[C]`](#c)
      - [`Mode scratch` / `[sctch]`](#mode-scratch--sctch)
      - [Sensibility](#sensibility)
      - [Progressivity](#progressivity)
      - [[stp]](#stp)
  - [Files selection](#files-selection)
  - [Video settings](#video-settings)
  - [Conventions employées dans la documentation](#conventions-employes-dans-la-documentation)
    - [La syntaxe ?](#la-syntaxe-)
    - [Comment participer ?](#comment-participer-)

## Step sequencers
(3)

Two Step sequencers called A and B generating number sequence according to:

- (5) A number sequence of time
- (6) A number sequence of iteration
- (7) A number sequence of progressivity
- (8) A number sequence to be added or subtract

Apply the datas to:

- (9) The position of the loop
- (10) The Pitch and the speed simultaneously
- (11) The speed only
- (12) To the pitch only
- (13) Synthetizers

*`$` = value, each step got a value*

### `[=IT]`
- Play all `$` of time (all `$` of Step sequencerT)
at each value of the general Step Sequencer (top line) ... allT `$ / G $`
- If it is not triggered = Play a `$` of the Step sequencerT at every `$` of the general sequencer Step ... `T $ / G $`

### `[≠IT]`
- Change steps on the step sequencer (s) in accordance with a fixed $ of time (1000) by default).
- Column still on the right: go to the value gradually (1000) by default)

### `[%T]`
- Divides time by the `$` from Step Sequencer `IT` ... `T` `$% IT`

### `[/Tb/]`
Receive the time of Step sequencer B

### `[A]`
On/off

### `[next]`
Step forward

### `[ø]`
Reverse steps off and steps on

### `[><]`
Send a step on two opposite values

### `[>>]`
Move linearly on the sequence.
- One step all 6.25`$` (100%16 = 6.25)
- if the tempo = loop length of the sequence%10

### `[O]`
Turn this step mute


## Selectors and modulations

Choose position(s) to the starting point of the loop:

- Add value to this position(s)
- Move the position(s) along the whole sequence
- Apply enveloppe to sound track and opacity to video layer


### Gate
(14)
Set the position of the playhead where to start the playback loop

### `[raw]`
Raw data  A or B

### `[A@]`
Make a loop on the fly and change position with Step sequencers

### `[@re]`
Call back the loop made in `[A@]`. When released, read what is after the loop chronologically or with the `[@A]` mode go back where you were at your last `[@re]`

### `[>ø]`
Press on, press off (*midi mod*)

### `[loc]`
Lock selected source (*midi mod*)

If you choose to send files triggered by A or B or randomly with `[BB](A)` or `[_BB1](B)` the sample sent will be played at its beginning

###  `[Trg]` and `[Bng]`
Auto-receive On/off step and send enveloppe to
the sound selected.

### `[Trg]`
On/off step

### `[Bng]`
Send enveloppe to the sound selected (16)

### `[<<<]`
Send on/off step and set enveloppe from sources selected in
s&p, speed, or pitch

### `[ø]`
Trigger the Step sequencer `[A]` or `[B]` as selected in
s&p, speed, or pitch


## Audio modulations

- (10) Speed and pitch 50 = 0= stop, 75= go forward , 25= go back
- (11) Speed only 50 = 0= stop, 75= go forward , 25= go back
- (12) Pitch only 0 = default

### Left’s 2 columns:

#### Select data source

##### `[bck]`
Back to default `$` after selection released

##### [O]
Go back to default `$`

##### slider
set value

#### Choose data source

##### `[A]`, `[B]`, `[‘’a]` or `[‘’b]`

### Right’s 2 columns

#### Module data from the left ’s 2 columns

##### `[44]`

Choose between `44100`/`88200` hz

##### `[O]`

- Go back to default `$`
- Slider: set  modulation value

#### Choose data source
##### `[A]`, `[B]`, `[‘’a]` or `[‘’b]`


## Time stretching until drone
(2)
Advance your number sequence, pattern, over the entire sample.

Make the pattern you are making with Stepseq `A` or `B` sliding along the loop lenght more a less rapidly:

- Select entry point in the sample
- Select exit point
- Select stretching value

## Audio analysis
(1)

Analyze silences and attacks in the audio signal of sampler or synthesizer. Send the values as `[‘’a]` or `[‘’b]`

### Select a source
#### `[A]`
Track AV left

#### `[C]`
Upper synthetiser in purewave-synth

#### `Mode scratch` / `[sctch]`
Suite de valeurs opposées `0-100`, `25-75`, etc.

#### Sensibility

#### Progressivity

#### [stp]
- Mode steps: numbers of sequence
- number of step$ 1 to 5


## Files selection
(14)

Select audio and vidéo loop. Call bank or single audio and video files:

- Data bank video
- Data bank AV
- Data bank audio
- Link A&V selection

- Select the file number..
- Open browser
- Select the file with `A` or `B`
- One random selection
- One random selection
under the speed of Step sequencer `[BB](A)` or `[ BB1](B)`
- clear Drop down menu
- Open browser
- Drop down menu


## Video settings
(15)

Set video specifications. Dimension, frame rate, incrustations and image modulations

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
- On/off
- Receive On/off
- Invert color
- Audio control opacity

## Conventions employées dans la documentation
### La syntaxe ?

- Elle est décrite [dans les spécifications de Markdown](https://daringfireball.net/projects/markdown/syntax) (y'en a pour 25 minutes de lecture)
- TOC made with [nGitHubTOC](https://imthenachoman.github.io/nGitHubTOC/)

### Comment participer ?

- Il faut cliquer sur [le stylo là haut pour éditer la page](https://github.com/smonff/trop-simple/edit/master/README.md)
- Il ne faut pas hésiter à regarder [le code source](https://raw.githubusercontent.com/smonff/trop-simple/master/README.md)
- Il est possible décrire [des livres entiers en utilisant ce principe](https://github.com/progit/progit2/tree/master/book)
