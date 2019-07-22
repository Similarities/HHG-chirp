# HHG-chirp
atto second pulse train, discrete calculation fringe pattern


original equation form PHD Thesis of Daniel von der Bruegge
here modified for an chirped input pulse. 

A driving laser emitts an as pulse once per period. If the point of
emission is shifted in space during the laser pulse duration, the
emitted as pulse train will suffer from enlarged or shortened perodicity 
in its delay between each pulse. This introduces a phase relation 
between the successive emitted pulses. They are detected as an 
integrated signal on a grating - which means I(w). 
The periodicity of the pulse train, as well as it deviation from 
periodic delays - can be seen in I(w): as a HHG signal. 

The calculation approaches to calculate I(w) for a shifted 
HHG emission source (dopplershift) and a chirped driving laser
pulse in order to check, if the phase relation could be 
pre-compensated with the chirp (GVD correction). One has to 
note, the GVD corrected leads to an enlargement of the laser
pulse duration, which seems to affect the HHG spectrum significantly.

Mathematica 11
