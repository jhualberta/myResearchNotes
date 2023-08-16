**$^{39}$Ar life time**

#gurpreet #deap #analysis #lifetime

Gurpreet thesis

eventTime 
The trigger time parameter measures the time of the first main pulse
peak trigger in the waveform. The studies show that the typical well-calibrated trigger
in the DEAP-3600 DAQ occurs around 2500 ns, thus a trigger time cut between the
time values between 2250 to 2700 ns is suggested to select good physics triggers. The
lower cut at 2250 ns is the pre-trigger pile-up cut which basically means removing
the tail of the previous triggers which have been missed by other pile-up cuts like
numEarlyPulses and deltat cut. The upper time limit at 2700 ns is defined to remove
any post-trigger pile-up cut. The function of trigger time is strongly correlated to the
subeventN cut.


39Ar triggeres
1\. (!(calcut&0x31f8))
2\. (!(dtmTrigSrc&0x82))
3\. fmaxpe≤0.4
4\. fprompt≤0.41

**Cuts used to select the triggers containing Cherenkov light**
1\. (!(calcut&0x31f8))
2\. (!(dtmTrigSrc&0x82))
3\. fmaxpe>0.4
4\. fprompt>0.8
5\. subeventN == 1
6\. deltat≥20000
7\. numEarlyPulses≤3
8\. eventTime \[2250,2700\]


