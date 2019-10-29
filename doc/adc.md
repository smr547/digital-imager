# Analogue to digital converter

The Analogue to digital converter (ADC) component is responsible for converting the signal output by the CCD into a digital format
suitable for storage a processing on a computer. 

Our camera is based on the [AD9826](https://www.analog.com/media/en/technical-documentation/data-sheets/AD9826.pdf) chip.
A video signal processor developed by Sony. This ADC can operate at a rate of 15MSPS with a resolution of 16 bits. 
With this chip we sould be able to achieve a readout time of less than 10 seconds for even the lagest of sensors that 
we might employ in this project.

The chip is capable of 3 channel operation at speeds of up to 30 MSPS. However we will use only a single channel to process
all pixels on the CCD.

