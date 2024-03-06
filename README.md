Hi! It's me, la Tsakap ke za zit, a.k.a. Wallflower, a.k.a la slari plise, a.k.a. la tepmlimlatu, a.k.a. jan Pilomena,...

Anyway, it looks like you're interested in Xextan, and speech synthesis, particularly synthesis of Xextan speech.
Well you've come to the right girl!
As far as I know, I am the first and only person to have achieved such feats as you are about to witness.
J/k, it's all pretty straight-forward when you break it down.
Just do these steps:

### INSTRUCTIONS ###

This package contains instructions for eSpeak to read Xextan text, 
and has also been prepared to optionally be used with the MBROLA synthesizer.

FIRST: You'll need to have eSpeak and eSpeakedit installed.
eSpeak is an open source software that can be acquired from:
https://espeak.sourceforge.net/

OPTIONALLY: If you would like higher quality audio output, you'll need to have MBROLA installed. 
MBROLA is a formerly noncommercial freeware software that was released as open source in 2018.
Unfortunately, there haven't been any official releases since then, so you'll either have to compile the source yourself, or use an old standalone (freeware) version.
Source can be obtained here:
https://github.com/numediart/MBROLA

SECOND: All the data files must be copied into their proper folders.
Each file should be copied into the folder of the same name in your eSpeak installation directory.

THIRD: Now that all your software and data is in order, open eSpeakedit.
From the top menu, select "Voice, Select voice...", then choose /test/xex.txt in the file selector.
From the top menu, select "Compile, Compile dictionary 'xex'"
Now you may test the voice. Type any Xextan text in the textbox at the top left of the window.
Press the "Translate" button. SAMPA format data should appear in the box below.
Now press the "Speak" button. You should hear the text being spoken by the eSpeak formant synth.
All good? Congrats, it worked! Optionally, there are voice variant settings under "Voice, Select voice variant..." that will alter the timbre of the synth.

OPTIONALLY for MBROLA: Now that the eSpeak backend is primed, 
Select "Compile, Compile mbrola phonemes list...". 
Choose ptbrxex.txt. Now do the same for ptbr4 
Now select "Voice, Select voice...", then choose /mb/mb-br4-xex.
Now you can test the voice. Did it work? I hope so. 

I threw all this together haphazardly, and I'm still making small optimizations.
I'm also planning on trying to create a version that will work without having to be compiled from scratch. 
Maybe some day Xextan will come packaged with screen readers and other TTS apps by default!
That'd be something, huh?

Anyways, hope you enjoy!

-Filomena




