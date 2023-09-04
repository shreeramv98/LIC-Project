# LIC-Project

OBJECTIVE:

The DC MOTOR SPEED CONTROL CIRCUIT is primarily a 555 IC based PWM (Pulse Width Modulation) circuit developed to get variable voltage over constant voltage.

ABSTRACT/WORKING:

When power is supplied, 555 TIMER generates PWM signal with a duty ratio based on the pot resistance ratio. Because of the pot and the diode pair, here the capacitor (which triggers the output) must charge and discharge through a different set of resistance and because of this, the capacitor takes a different time to charge and discharge. Since the output will be high when the capacitor is charging and is low when the capacitor is discharging, we get a difference between high output and low output, and thus the PWM occurs.
This modulated output of timer is fed to the signal pin of L239D H-bridge to drive the DC motor. With the varying PWM ratio we get varying RMS terminal voltage and so we obtain the speed. To change the direction of rotation, the PWM output of timer is connected to the second signal pin.
