# Biospin-Highpass-Filter
contains the source code high pass filter at 586 Hz - 863 Hz

## Analysis of FFT with the FFT IFFT equation





## Analysis Of Signal 
**1. Signal X**

code:

x = np.sin(2 * np.pi * 586 * t) 

plt.plot(t,x)

**analysis** : From the equation signal x produces a signal that has a slightly tenuous wave, because the signal frequency x is smaller
![WhatsApp Image 2021-03-23 at 21 56 54](https://user-images.githubusercontent.com/81221913/112158068-c82b7500-8c22-11eb-9563-7eba12a86f72.jpeg)


**2. Signal Y**

Code: 

y = np.sin(2 * np.pi * 863 * t)
plt.plot(t,y)

**analysis** : From the equation, a signal that produces a signal that has a dense wave. because the signal frequency y is large
![WhatsApp Image 2021-03-23 at 22 05 04](https://user-images.githubusercontent.com/81221913/112159233-e3e34b00-8c23-11eb-9d43-21860a77b7e7.jpeg)

**3. Signal Z**
Code:

z = x+y
plt.plot(t,z)

**analysis** : if we combine the two signals, a z signal is formed which is a combination of signal x and signal y
![WhatsApp Image 2021-03-23 at 21 35 48](https://user-images.githubusercontent.com/81221913/112155764-96191380-8c20-11eb-8e59-061c37df874f.jpeg)

