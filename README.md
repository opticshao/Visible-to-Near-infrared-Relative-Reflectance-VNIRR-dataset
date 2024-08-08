# Visible to Near-infrared Relative Spectral Reflectance (VNIRSR) dataset

We use the GaiaField-V10 HR hyperspectral imager produced by Dualix to capture the spectral dataset. 
This spectral imager can capture a spectral data cube with dimensions of ${936 \times 960 \times 360}$, where ${936 \times 960}$ represents the spatial resolution and ${360}$ represents the number of spectral channels, covering a spectral range from ${382.30\ nm}$ to ${997.38\ nm}$, with a spectral sampling interval of approximately ${1.55\ nm \sim 1.88\ nm}$.

We select spectral data within the range of ${400\ nm}$ to ${900\ nm}$, and merge the spectral channels to obtain a spectral data cube with a spectral interval of ${10\ nm}$.
A standard whiteboard with a reflectance of approximately 99% at all wavelengths is used to convert the intensity information of the scene to spectral reflectance.

Here are some parameters of the dataset：
* Spatial resolution: ${936 \times 960}$
* Spectral range: ${400\ nm \sim 900\ nm}$
* Spectral interval: ${10\ nm}$
* Number of channels: 51
* 217 artificially constructed scenes and 113 outdoor scenes, totaling 330 spectral data cubes.

Below are some examples in the VNIRSR dataset.
![image](https://github.com/opticshao/Visible-to-Near-infrared-Relative-Spectral-Reflectance-VNIRSR-dataset/blob/main/SpectralDataset.png)
