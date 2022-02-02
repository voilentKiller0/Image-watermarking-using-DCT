# Image-watermarking-using-DCT

Digital watermarking is a technology using which one can ensure copyright protection of
digital media, data authentications and security. It is the act of hiding a message related to
a signal into the signal itself. This process is a little similar to steganography.
Watermarking tries to hide a message related to the actual content of the digital signal,
while in steganography the digital signal has no relation to the message, and it is merely
used as a cover to hide its existence. 

![image](https://user-images.githubusercontent.com/55941465/152234698-dbc15834-ee34-46b1-87ca-96ba492c8394.png)

-----------------------------------------------
## How it Works

### Haar Transform
A 1D, 1-level Haar transform is performed on a signal,
 f = (f1, f2, f3, f4,..., fN-1, fN)
f-> a^1 | d^1
[-] a^1 is called the trend or running average, and d^1 is called fluctuation or running difference.
[-] This process can be repeated until there ceases to be an even number of averages.
[-] Performing an inverse transform only to the trend sub-signal would allow an
approximation of the original signal.


### Watermarking using DCT
The discrete cosine transform (DCT) helps separate the image into parts (or spectral subbands) of differing importance (with respect to the image's visual quality). 
The DCT is similar to the discrete Fourier transform: it transforms a signal or image from the spatial domain to the frequency domain

![image](https://user-images.githubusercontent.com/55941465/152234845-70262734-db4e-41c1-9f38-51f09973bf8c.png)

The general equation for a 1D (N data items) DCT is defined by the following equation:

![image](https://user-images.githubusercontent.com/55941465/152234899-eff72c75-3903-44f3-8430-6dfba11d9751.png)

The corresponding inverse 1D DCT transform is simple F^-1(u), i.e.: where

![image](https://user-images.githubusercontent.com/55941465/152234964-0f197378-62a9-4629-b3a2-b78675ce1767.png)

![image](https://user-images.githubusercontent.com/55941465/152234978-d998e730-48c1-4a2f-a0c8-4ddfaa78b204.png)

![image](https://user-images.githubusercontent.com/55941465/152235083-ca307ecc-b589-4550-b910-14394a2b1be8.png)

-----------------------------------------------

## Demo

![image](https://user-images.githubusercontent.com/55941465/152235230-4a7788f9-eb4e-4ce1-8728-b0dcb187c27d.png)

## Getting Started

### Prerequisites

* Haar Transform
* Discrete Cosine Transform

### Setup

1. Open Google colab
2. Execute below command
```
$!git clone https://github.com/voilentKiller0/Image-watermarking-using-DCT.git

```
3. Open "/content/Image-watermarking-using-DCT/Image Watermarking.ipynb"
4. Run the Test headline command.

