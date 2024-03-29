// The analogWrite command works through PWM - pulse width modulation 
// When viewed through an oscilloscope, it shows that when using decimal values, the way an LED displays 
// the value is by simulating for ex 2.5 volts by switching between 5 and 0 volts, each respectively for half the
// time that your circuit runs 

// This is an 'under the hood' look at how the logic works in the hardware itself.  For ex if you were to have a brightness
// of .25, an oscilloscope would show a very brief amount of time at 5 volts for the measured amount of time, brief enough to 
// average .25v for the 4 second window. 
