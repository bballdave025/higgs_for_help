# higgs_for-help

I'm putting this repo together for a Physics StackExchange Question.
I've run into some problems with my attempts to analyze the 4-lepton data
from the Higgs search (2011 and 2012 runs). I'm going on to look at the
spectra of the of the particles and do a rediscovery of the Higgs. However,
I decided to do something different and look at the invariant mass of one 
of the daughter particles, with the idea of finding the invariant energy of
each of the four daughter leptons. However, I'm not getting close to 
0.0005 GeV/c^2 with the first particle of the first event, neither am I
with any of the other electrons in the first event. I'm not sure what the
error bars are, but I'm pretty sure they're not on the order of 10 GeV/c^2.

I'm putting together a notebook with just the basics of the computation, 
with more physics and more look at the numbers for individual particles in
individual events. I highlight questions about the radicand in the invariant
mass formula, i.e. the $E^2 - \lvert \textbf{p} \rvert^2$ part of the whole
$m_0 = \sqrt{E^2 - \lvert \textbf{p} \rvert^2}$. Part of my question is to ask 
if I'm handling things right when $\lvert \textbf{p} \rvert^2  >  E^2$.

I am also looking at the invariant mass of the system of particles to double
check its invariant mass (and thus the invariant mass of the parent particle)
as a sort of sanity check on the whole invariant mass thing. I won't inclde
the mass histogram, Monte Carlo events, analysis of Higgs in the mass
regime, etc. in the notebook here.

The text of the Physics StackExchange question will be the last section
of the notebook. If you are here because of that question, feel free to make
coments (and especially to point out mistakes you see) here on GitHub.
