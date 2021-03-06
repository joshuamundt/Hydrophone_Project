### Joshua Mundt
### 03/14/2020
### Project 4



This project asks students to obtain raw data from OOI broadband hydrophone website for Oregon Shelf and Oregon Offshore. Then, plot power spectral density in (dB) with respect to frequency for the following four different cases: when it doesn’t ran and it is not windy, when it does not rain and it is windy, when it rains and it is not windy, and when it rains and it is windy. Afterwards, make analysis on how wind and rain affect the spectral level. The next objective is to plot spectrogram for airgun, marine mammals, and earthquake noise from the same website. Then compare those three signal with Wenz Curve, and draw a conclusion on whether they are consistent with the bandwidth on the Wenz Curve. 


### Project Statement 

### Part 1) Wind and Rain Noise

1. In each site and for each category that you identified in step 3, plot 𝑃𝑆𝐷𝑑𝐵 vs frequency.

2. Compare the spectral levels and answer these questions: 

a) What is the effect of wind and rain on underwater noise? Explain any behavior you observe in your result. 

b) Which one has the highest impact? Rain or wind? 

c) What are the main reasons for observing different spectral levels in Oregon shelf compared to Oregon offshore? 
attenuation loss


### Part 2) Airgun, Marine Mammals, Earthquake Noise

1.	Find a short time period that there is a marine mammal vocalization in recorded data and plot its spectrogram

2.	Find a short time period that there is an airgun noise in recorded data and plot its spectrogram

3.	Find a short time period that there is an earthquake or a volcano eruption in recorded data and plot its spectrogram.

4.	Compare the bandwidth of these three signals. Are they consistent with what is shown in the Wenz curve (refer to the Ocean Noise slides)?

### Part 1 solutions ) Wind and Rain Noise

1. In each site and for each category that you identified in step 3, plot 𝑃𝑆𝐷𝑑𝐵 vs frequency.

![](proj4image/NRNW_OS.png)

      Figure 1: 𝑃𝑆𝐷𝑑𝐵 vs frequency at Oregon Shelf in July 06, 2019
      
![](proj4image/WNR_OS.png)

      Figure 2: 𝑃𝑆𝐷𝑑𝐵 vs frequency at Oregon Shelf in April 06, 2019

![](proj4image/RNW_OS.png)

      Figure 3:𝑃𝑆𝐷𝑑𝐵 vs frequency at Oregon Shelf in March 06, 2019

![](proj4image/RW_OS.png)

      Figure 4:𝑃𝑆𝐷𝑑𝐵 vs frequency at Oregon Shelf in March 01, 2019

![](proj4image/NRNW_OF.png)

      Figure 5:𝑃𝑆𝐷𝑑𝐵 vs frequency at Oregon Offshore in Nov 16, 2018

![](proj4image/WNR_OF.png)
      
      Figure 6:𝑃𝑆𝐷𝑑𝐵 vs frequency at Oregon Offshore in Feb 27, 2019

![](proj4image/RNW_OF.png)
      
      Figure 7:𝑃𝑆𝐷𝑑𝐵 vs frequency at Oregon Offshore in Sep 01, 2018

![](proj4image/RW_OF.png)
      
      Figure 8:𝑃𝑆𝐷𝑑𝐵 vs frequency at Oregon Offshore in Feb 10, 2019
      
2. Compare the spectral levels and answer these questions: 

a) What is the effect of wind and rain on underwater noise? Explain any behavior you observe in your result. 

In the Oregon Shelf site, it is evident that the spectral level is higher in figure 4, when there is rain and wind at lower and higher frequency compare to figure 1, during the period of no wind and no rain or during the period of only rain or only wind, as show in figure 3 and 2.

b) Which one has the highest impact? Rain or wind? 

The rain has the highest impact when looking at both Oregon Offshore and Oregon Shelf sites. The power spectral density level starts from bout 80, as shown in figure 6 and the 𝑃𝑆𝐷𝑑𝐵 decreases at a faster rate as the frequency increases. Whereas when there is only rain, as show in figure 7, the initial power spectral density level is similar at lower frequency but when the frequency increase, it doesn’t decrease as fast.


c) What are the main reasons for observing different spectral levels in Oregon shelf compared to Oregon offshore? 

The instruments at Oregon Shelf is closer to the shore and shallower compare to Oregon Offshore, thus the spectral levels in Oregon Shelf is higher for being closer close to the surface and having less attenuation loss. Since they are at different depths and locations, the distinct ambient noises can be identified.

### Part 2 solutions ) Airgun, Marine Mammals, Earthquake Noise

1.	A short time period that there is a marine mammal vocalization in recorded data and plot its spectrogram

![](proj4image/MH.png)

      Figure 9: Spectrogram of Marine mammal at Oregon Slope Base in Oct 06, 2017

2.	A short time period that there is an airgun noise in recorded data and plot its spectrogram

![](proj4image/AH.png)

      Figure 10: Spectrogram of Airgun at Axial Base Seafloor in Aug 01, 2019

3.	A short time period that there is an earthquake or a volcano eruption in recorded data and plot its spectrogram.

![](proj4image/EH.png)

      Figure 11: Spectrogram of Earthquake at Axial Seamount in Aug 16, 2019
      
![](proj4image/WC.png)

      Figure 12: Wenz Curve [1]


4.	Compare the bandwidth of these three signals. Are they consistent with what is shown in the Wenz curve?

#### Marnie Mammals
In figure 9, a marine mammal vocalization frequency is found in a small-time window, and the bandwidth range from 800Hz to 5000Hz. One can claim that it comes from baleen whales because according to Geoxpro, the hearing bandwidth for baleen whales is believed to range from 5 Hz to above 20 kHz [2]. It is consistent with the bandwidth of biologics in the Wenz Curve shown in figure 12.

#### Airgun
Figure 10 shows the spectrogram of airgun at Axial Base Seafloor, and the frequency ranges from 0 to about 4,000 Hz and most of the energy is at lower frequency not to interfere with marine mammals' communication and navigation. A source claims that an airgun bandwidth can range from 200 to 22,000 Hz [3], therefore the signal found can be from a seismic airgun. Also, it is consistent with the bandwidth of ships and industrial activity on the Wenz Curve.



#### Eathquake
According to the Wenz Curve, figure  12, the earthequake frequency can range from 0 to 100 Hz. Similarly, figure 11 depicts the spectrogram of earthquake and the bandwidth is between 0 and 85 Hz. Therefore, it is certain that the signal comes from earthquakes because it has higher frequency than the ambient frequency and doesn't exceed 100 Hz.


## References

[1] https://dosits.org/science/sounds-in-the-sea/what-are-common-underwater-sounds/

[2]https://www.geoexpro.com/articles/2010/06/marine-seismic-sources-part-v-the-hearing-of-marine-mammals

[3]http://filesrodadas.anp.gov.br/round9/arquivos_r9/guias_R9/sismica_R9/Bibliografia/Goold%20and%20Fish%201998%20-%20broadband%20spectra.pdf

