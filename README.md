# maxiInstruments-template

A template for maxiInstruments 0.7.2 sample loading

This template shows you how to use the threaded audio worklet for loading audio files in a CORS enabled way, using the shared array buffer in the worklet for custom DSP. The reason for using custom DSP is...er.. it is custom. Also there's a built in sequencer and a bunch of other stuff that is compatible with magenta etc. if you are interested in that stuff. But basically, if you want real DSP in a browser that can be served in git pages in 2023, this is it. 

Demo is here:

https://ual-cci.github.io/maxiInstruments-template/

maxiInstruments is written and maintained by louismac as part of the machine learning lib for creatives, learner.js, which was created as part of the mimic project, funded by UKRI. maxiInstruments makes my Maximilian library much easier to use in js, for which I am eternally grateful.

https://github.com/Louismac/learnerjs

www.mimicproject.com

p.s. you might ask yourself why on earth is this important. I appreciate that as a demo it just seems like some stupid drum pattern. However, as anyone who has tried to do custom DSP using the shared array buffer and serve it remotely can tell you, this used to be super easy and has been made way harder than it needs to be by people who are definitely being paid to much to worry too hard about ridiculous edge cases that are highly unlikely to ever happen. As a result of these people, you are not allowed to load your own custom dsp in to your own web page with your own sounds without an absolutely collosal engineering effort defying all reason. Yeah and the MIMIC team who led the effort in getting some of it done got a best paper award at the web audio conference. Go figure.
