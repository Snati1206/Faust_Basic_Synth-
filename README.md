# Faust_Basic_Synth
## Faust Synth
This is a Synth created in Faust where I explored a little and added the following features:
  ## Detune
  I created a variable that added a value of (+2Hz) and (-2Hz) to the frequencies of the oscillators #1 and #2.

  <img width="495" alt="Captura de Pantalla 2023-10-11 a la(s) 16 06 10" src="https://github.com/Snati1206/Faust_Basic_Synth-/assets/94990891/a9fd53bc-c1c5-4e57-a2ab-075c7eb521e1">

  ## AutoWah
  I used the existing AutoWah effect. You can control either the Dry/Wet of the Wah and an LFO who modules the intensity of the effect.
 
  <img width="435" alt="Captura de Pantalla 2023-10-11 a la(s) 16 04 17" src="https://github.com/Snati1206/Faust_Basic_Synth-/assets/94990891/4b9cd631-afd8-4206-94df-8a36ef2b5332">

  ## Wavetype selector
  You have 3 oscillators that work independently, and for each one of them, you can select a different type of waveform (Sin, Triangle, Sawtooth)
  Each oscillator also has a different gain slider.

  <img width="563" alt="Captura de Pantalla 2023-10-11 a la(s) 16 07 53" src="https://github.com/Snati1206/Faust_Basic_Synth-/assets/94990891/d356f364-c2fd-4fdd-8283-3161ca3b7bae">

  
  ## LP filter
  Inbuilt LP filter with a resonance (Q). (The Q and Filter Gain Values still doesn't work as planned)
  
  ## Envelope for the amplitude values
  Here you have an ADSR envelope that controls the amplitude levels (at,dt,sl,rt)
  ## Harmonizer (4 octaves)
  I applied the 12 TET equation to be able to change the frequency of each oscillator within the range of 4 octave from -24 to +24 semi-tones (n1,n2,n3) resulting   in an harmonizer.

+  ![image](https://github.com/Snati1206/Faust_Basic_Synth-/assets/94990891/0b0a3147-32a8-42c9-a187-4e5c43bfb5a3)
+  <img width="364" alt="Captura de Pantalla 2023-10-11 a la(s) 16 18 20" src="https://github.com/Snati1206/Faust_Basic_Synth-/assets/94990891/78afdf8c-1f37-4b2f-80e8-72862e2731f7">
+  <img width="91" alt="Captura de Pantalla 2023-10-11 a la(s) 16 19 20" src="https://github.com/Snati1206/Faust_Basic_Synth-/assets/94990891/9c925ec1-4b93-4f89-bdd7-7d43e6225498">
 
  
