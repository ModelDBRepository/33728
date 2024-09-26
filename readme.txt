Model of recurrent cyclic inhibition as described on p.119 of Friesen and
Friesen (1994), which was slightly modified from Szekely's model (1965).
The conditions for oscillation are:
(1) the loop must contain an odd number of neurons,
(2) each of which can significantly inhibit its target,
and (3) the excitatory drive must be strong enough so the
   loop neurons will spike when released from inhibition
 
In the SpikePlot, the bottom three trains show the alternating activity of
the loop neurons.  The top three trains are the afferent excitatory streams.
 
To launch a new simulation, press Init & Run in the RunControl panel
 
For questions about this implementation, contact ted.carnevale@yale.edu
 
REFERENCES
Szekely, G..  Logical network for controlling limb movements in urodela.
  Acta Physiologica Academiae Scientiarum Hungaricae 27:285-289, 1965.
Kling, U. and Szekely, G..  Simulation of rhythmic nervous activities. 
I. Function of networks with cyclic inhibitions.
  Kybernetik 5:89-103, 1968.
Friesen, W.O. and Friesen, J.A..  NeuroDynamix.  New York: Oxford
  University Press, 1994.

Updates

20240226 Use noiseFromRandom123 for result identity between 8.2 and 9.0
  Each launch now produces same result independent of NEURON version.
  However each press of the Init&Run button show statistically independent
  results.
