# Demodulating Batman WalkeTalkies
For Christmas 2019, my preschooler received a pair of Batman WalkeTalkies.  They were loud and annoying, but presented an opportunity to play with some SDR tools

![Devices in Question](images/image1.jpg "WalkeTalkies")


I have an RTLSDR and a LimeSDR Mini, so went about frequency searching


![Top Level GNURadio Scanner](images/image2.jpg "Radio Scanner")


I got lucky and happened to find the signal at ~50MHz.  Eyeballing it it appeared to be an AM signal.  Like Batman would ever use an AM radio! Unencrypted! 


![Spectrum](images/image3.jpg "Spectral Analysis")


We captured my son singing and then put it through an AM demodulator.  He enjoyed watching the spectrum jump around, and I'm happy to know I can probably jam these if they become too annoying


![AM Demodulator](images/image4.jpg "AM Demodulator")
