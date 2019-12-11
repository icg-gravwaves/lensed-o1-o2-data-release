For each of the binary black hole events from GWTC-1 three files are supplied:

- {EVENT}_results.csv
- {EVENTS}_2hours_injections.csv
- {EVENTS}_32days_injections.csv




{EVENT}_results.csv : a list of candidates produced by the search for lensed
counterparts to {EVENT}.
The columns are as follows:

Is known event
  - The name of an event if there is a previously published detection
  at this time.

End time
  - The end time of the signal given in GPS seconds.

Time diff
  - The absolute value of the time difference between the new candidate
  and {EVENT}, given in seconds.

Inverse false alarm rate
  - The inverse of the false alarm rate, the rate of events with equal
  or greater detection statistic values, given in seconds.

Delay-weighted p-value
  - The false alarm probability using a delay-weighted ranking statistic given
  by: Inverse false alarm rate / Time diff.




{EVENTS}_2hours_injections.csv : contains details of injections in a 2 hour
window either side of {EVENT}.
{EVENTS}_32days_injections.csv : contains the same information for a set of
injections in a 32 day window either side of {EVENT}.
The columns are as follows:

mass1
  - Then mass of the first component used for the injection,
  given in solar masses.

mass2
  - The mass of the second component used for the injection,
  given in solar masses.

spin1x
  - The x component of the dimensionless spin for the first component.

spin1y
  - The y component of the dimensionless spin for the first component.

spin1z
  - The z component of the dimensionless spin for the first component.

spin2x
  - The x component of the dimensionless spin for the second component.

spin2y
  - The y component of the dimensionless spin for the second component.

spin2z
  - The z component of the dimensionless spin for the second component.

inclination
  - The angle between the total angular momentum of the binary
  and the observer's line of sight, given in radians.

distance
  - The luminosity distance from the observer to the source, given in Mpc.

longitude
  - The longitude of the injected signal.

latitude
  - The latitude of the injected signal.

coa_phase
  - The phase of the binary at coalescence, given in radians.

polarization
  - The polarization angle of the binary.

End time
  - The end time of the signal, given in GPS seconds.

Time diff
  - The absolute value of the time difference between the new candidate
  and {EVENT}, given in seconds.

Scale factor
  - The amplitude of the injected signal is divided by this value,
  equivalent to multiplying the distance by this scale factor
  (squareroot of the lensing magnification).

Found after vetoes
  - True if a candidate was found at the time of the injection.

Inverse false alarm rate
  - The inverse of the false alarm rate, the rate of events with equal or
  greater detection statistic values, given in seconds.

Delay-weighted p-value
  - The false alarm probability using a delay-weighted ranking statistic given
  by: Inverse false alarm rate / Time diff.
