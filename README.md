
# albs DAC-MOS II 500

albs DAC-MOS II 500 audio power amplifier module (mono single channel)  
using double die lateral MOSFETs
### Marketing-text: 
The DAC-MOS II 500 module is built on the same base board as all other [DAC-MOS II modules](https://github.com/analoghifi/albs-DAC-MOS-II-360-240-120) and thus has the same pin assignment.  
  
In order to exploit the full performance, a power supply voltage of ±75 to ±80V is required, whereby a low-impedance / high load capacity power supply unit must be used.  
Only a power supply with ≥80000µF/85V using our toroidal transformers RK-75M, RK-95M or RK-55M is suitable.  
For cooling, the module must be attached to a heat sink with a thermal resistance of at least 0.2 to 0.3 K/W (kelvins per watt).  
  
The main advantage over the [DAC-MOS II 360](https://github.com/analoghifi/albs-DAC-MOS-II-360-240-120) is that this module can also be operated at impedances around 1 Ohm, i.e. wherever high output currents are required.  
  
When power is drawn from approx. 350 watts and above, forced cooling with a fan is absolutely necessary, because otherwise sufficient heat dissipation from the cooling angle is not possible.  
  
Each of the TO-3 MOSFET transistor housings contains 2 power chips with max. 8A and 125W power dissipation each. These 6 pairs of mosfets with max. 48A generate up to 750 watts of power dissipation in a very small space, which of course has to be dissipated. This can only be done by forced cooling.  
  
The parallel connection of the mosfets results in a high damping factor, i.e. a low internal resistance at the loudspeaker connection, which is particularly advantageous for low-impedance loudspeakers with high current requirements. If it is not about high output power but about high current consumption, it always makes more sense to work with a low operating voltage in order to keep the heat losses caused by the quiescent current low.  
#### The features described below illustrate the high technical standard of this module series: 
* Balanced audio input (unbalanced input possible as well)  
* fully DC-coupled  
* Bridge Mode (BTL) possible (using two modules) resulting in multiple power and double slew rate, no matter if a balanced or unbalanced input is used (without the need of additional circuits)  
* With inverting control via input B, an active control circuit (feedback) for loudspeakers is possible.  
* 6dB-filters (C<sub>HA</sub>, C<sub>HB</sub>, C<sub>TA</sub>, C<sub>TB</sub>) can be used as crossover for tweeter, woofer or midrange. This means that no additional crossover is required to activate loudspeaker cabinets with 1st order filters.  
* A mono mixer amplifier can be realised via inputs B and C (e.g. as a final stage for mono sub-bass).  
* With the resistor R<sub>VU</sub> any gain from 0 to +3.6dB can be set. (With unbalanced control via input A, B connected to M).  
* Via the resistors R<sub>VA</sub>, R<sub>VB</sub>, R<sub>VC</sub> as well as R<sub>TA</sub> and R<sub>TBC</sub> almost any input resistance can be realised. The input sensitivity of the module can also be freely selected via integrated voltage dividers. (R<sub>VA</sub>, R<sub>VB</sub> are series resistors, R<sub>TA</sub>, R<sub>TBC</sub> are divider resistors).  
* The preamplifier is fully balanced with a high-quality op amp from Burr-Brown (in metal case TO-99) and is insensitive to temperature influences and mechanical shocks. It is also decoupled from the operating voltages and protected against reverse polarity.  
* An extremely linear current mirror driver operates in Class A mode and is cooled by 2 finned heat sinks.  
* The composite pre- and driver stage can be supplied via separate operating voltages. Since in this case the supply voltages of the pre- and driver stage are higher than those of the output stage transistors, a better modulation capability in connection with a higher signal slew rate results, while the power dissipation of the output stage transistors is reduced. The input circuit is supplied via Zener diodes.  
* The pre- and driver stage is equipped with 220µF/100V electrolytic capacitors and 0.22µF/100V film capacitors.  
* All signal affecting capacitors are foil types.  
* All operating voltage inputs and the star-wired earth connections are fitted with nickel-plated brass M4 screw bolts, the audio inputs and all other necessary connections are fitted with silver-plated pins.  
* The loudspeaker output can be tapped either via three 16 amp relays connected in parallel or directly at nickel-plated brass M4 bolts, bypassing the relays.  
* The hermetically sealed relays guarantee a long-lasting, low-impedance contact transition and a constant, high damping factor at the loudspeaker connection.  
* Overvoltage protection of the power amp transistors against voltage peaks with inductive loads is realised with fast 6 A diodes.  
* A partly completely revised, partly new protection circuit ensures immediate disconnection of the loudspeaker if internal or external faults occur. The following functions are integrated:  
    * Switch-on delay of the loudspeaker of 5 sec. to avoid switch-on noises in the loudspeaker.  
    * Immediate disconnection of the loudspeaker in case of mains failure longer than 0.3 sec. and when switching off.  
    * Shutdown if DC voltage or extreme proportions of infrasound occur in the output signal.  
    * Shutdown in case of failure of any operating voltage of preamplifier, driver or output stage.  
    * Frequency-independent, delayed shutdown when a presettable output voltage is reached (power limitation).  
    * Delay-free switch-off when a presettable switch-off point is reached in the event of oscillation, extreme HF components in the output signal or clipping. (high-frequency protection).  
    * Shutdown when the permissible temperature range of max. 90°C is exceeded at the cooling angle.  
    * The protection circuit also controls the delayed, but abrupt switch-on of the relays when the fault at the output is eliminated.  
* The PCB is made of 2.0mm FR-4 base material and coated on both sides with 70µ copper. The solder and component side have a solder mask, the component side also has a position imprint.  
* The large ground planes as well as the double-guided wide + and - supply voltage conductor tracks enable subsequent enlargement of the conductor track cross-sections as a modification by means of tin-plated cut-outs.  
* Additional modification options:  
All 4 supply voltages (±/+VTS/-VTS) can be filtered against ground with MKP capacitors (min. 4.7µF) on the solder side of the module.  
* Practical 5-pole audio input connector for all control variants.  
* For active concepts, bridge or stereo power amplifiers, the ± and ground connections can be electrically connected with spacer bolts when the modules are arranged one above the other and thus mechanically fixed.  

----

### used double-die lateral MOSFETs:  
first generation: Semelab BUZ900D / BUZ905D (160V / 16A / 250W) TO-3  
first generation "HV"-version: Semelab BUZ901D / BUZ906D (200V / 16A / 250W) TO-3  
second generation: Exicon ECF20N20 / ECF20P20 (200V / 16A / 250W) TO-3  
third generation: Exicon ECW20N20 / ECW20P20 (200V / 16A / 250W) **TO-264  not yet released**  

----

## Pictures:
#### first generation:  
T.B.D.  

  
#### second generation:  
<img src="/Pics/Albs_DAC-MOS_500__Exicon_1.png">  
  
<img src="/Pics/Albs_DAC-MOS_500__Exicon_2.png">
  
----
  
you can still buy it (the second generation) on ebay (as of 2023 Aug 01):  
* DAC-MOS II 500 -> https://www.ebay.com/itm/254110259549  

or directly from the manufacturer: -> https://albs.de  
