## Sound

This little application samples and visualizes the input from the sound card.
Additionally, it shows the spectrum of the incoming signal and displays the frequency of the maximum span.

### Screenshots

![alt tag](data/screen1.png)
![alt tag](data/screen2.png)

### Dependencies
You need the following libraries:
- OpenCV to visualize the sound input and spectrum
- OpenAL to access the sound card
- FFTW to apply fourrier transformations

### Installation
Set the correct pathes for the dependencies, then perform this:
```
mkdir build; cd build;
cmake ..; build -j;
```
