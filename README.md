# Roland 909 Drum Machine Emulator

[title](https://arditti93.github.io/909-drum-machine/)

## 909 drum machine emulator with JQuery, Vanilla JavaScript, HTML and CSS 

### Approach 
I used HTML global data attributes. Each sequencer key has a "data-index" attribute which corresponds to the index it represents in the audio sequencer arrays. Each audio sample also has its own "data-note" attribute. When any of the sequencer keys are toggled in the user controls, they perform two actions. First, they toggle a CSS class on that key to indicate that whether its "active" or not. Second, a function takes the "data-index" value of the sequencer key and looks for the corresponding step in the user's sequencer array. Then, depending on whether that key is "active", it either pushes or pops an audio sample's "data" value to/from the array at that index.

### Sequencer Instructions 
1. To programme a simple beat, start with selecting the KICK 1 button then click on the numbers '1', '5', '9' and '13', then click play
2. To change the BPM press stop and increase/decrease the tempo using the arrows. Once a BPM is selcted, press the enter key, then click play.  Your sequence will now be playing at the new tempo.
3. Select the CLAP and click on the numbers '5' and '13', then select the OPEN HAT and click numbers '3', '7', '11' and '15'.
4. To programme different beats, change which numbers and drums are selected.
5. The key controls are listed on the orange pannel.


