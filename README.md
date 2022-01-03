 # Guitar-Fuzz-Pedal
Hi in this project we will make our own effect pedal for both bass and electric guitar. If you know basic circuitry you can play around with the components and modify your pedal.


### **SIDE NOTE !** 
Before moving forward I would like to inform you the problems you might ran into. If you are planning to build this circuit on a breadboard it could caught some hums and noise from the jumper cables, power supply, other components and such. My advice is to built the pedal on a perfboard after testing on a breadboard, and keep the cables short as possible, because we are dealing with auido signals they are very sensitive to noise.


# ![tumblr_moz33qQZbk1rb40pco1_500](https://user-images.githubusercontent.com/88151522/140549379-20ec19a7-656e-47d0-a674-833537668868.gif) 
 
 



# Components

⦿ TL082CP OP-Amp

⦿ 6.3mm Female Jack Plug (X2)
### R͟e͟s͟i͟s͟t͟o͟r͟s͟
⦿ 2.2kΩ

⦿ 10kΩ (X5)

⦿ 47kΩ

⦿ 1MΩ

⦿ 100kΩ Potentiometer
### C͟a͟p͟a͟c͟i͟t͟o͟r͟s͟

⦿ 47µF Electrolytic Capacitor

⦿ 1µF Ceramic Capacitor

⦿ 500µF Ceramic Capacitor (X2) 

⦿ 695µF Ceramic Capacitor

### T͟r͟a͟n͟s͟i͟s͟t͟o͟r͟s͟ a͟n͟d͟ D͟i͟o͟d͟e͟
⦿ 2N3904 NPN Transistor (X3)

⦿ 1N4148 Diode


## HOW IT WORKS ?

When an input signal is applied, which is generally around 20mV to 70mV peak-to-peak, it first amplified with an Op-amp. You can use transistors to make an Op-amp but an IC chip would make it easy. This is the pre-amp section, it amplifies our signal to a point where we can work on it. Than there is a filtering capacitor to get rid of potentiol DC signal comes from our guitar or power supply. 

After there is a diode which is what makes the fuzz effect or the "clipping" in technical terms. The diode clips half cycle of the signal, the other half cycle trigers the first transistor's base and transistor biases. After transistor 1 is biased, it conducts and the current flows from 9VDC power supply which is connected to transistor's collector terminal with a current limiting resistor. 

Than comes to a circuit configuration called "Astable Oscillator". [Here](https://www.electronics-tutorials.ws/waveforms/astable.html) you can find more details about the circuit. 

And finally there is a 100kΩ potentiometer between the amplified input and directly to the output. This gives us to control the tone but an improvment in the tone control can be made with adding potentiometrs or changing the location of the current one.


## SOUND SAMPLE

[PLAY ME 🔊](https://drive.google.com/file/d/1Uqip_gwYu2IV7IQHH9KoIrQLA92Qiu3O/view?usp=sharing)




![siyah](https://user-images.githubusercontent.com/88151522/140613144-f5aaffcb-3181-45e8-aebc-bd96dc6349b8.gif)



## CONTACT INFORMATIONS

If you have any questions or any suggestions about the pedal just mail me at efeoral@gmail.com
