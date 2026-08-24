# 25W-PA-for-Tetra
This is a second stage of RF amplifier where the first stage is PA with the TQP7M9106.
- PA Operational freq. 380MHz - 460MHz
- Tetra up to 10W.

- To run the PA properly the RF input must be up to 18~19dB, if the rf power is above that value then you need attenuator after TQP7M9106-PA RF output and this PA RF input.
- The RF in/out capacitors must be with tolerance up to 0.5% max. You can find the values for each one in the BOM file.
- The schematic is taken from AMPLEON-BLP9LA25S datasheet, the PCB is identical from the datasheet with added BIAS power supply with voltage adjustment and current limiting.
- Testing the PA, the RF-in not connected, connect proper dummy load on RF-out, Power supply 12V~13.6V/5A, adjust the BIAS voltage to 1.8V.
- Connect the PA RF-in to TQP7M9106-PA RF output, run Tetra BS and monitor the RF signal (easy way with sdr-receiver and sdr++ with tetra demodulator, follow the signal quality and constellation)...
- ... if needs any corrections first try with BIAS voltage adj. and if needs more adjustments then add the attenuator to low the dB input and again with BIAS adj.

- This PA is OPEN PROJECT and is not tested yet but you can try to build and test it, if works then will be usable for radio-amateur community and specially for Tetra.

- Z32IT
