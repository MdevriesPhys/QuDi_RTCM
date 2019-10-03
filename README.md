			      QuDi_RTCM
____________________________________________________________________________

Initial file for RMIT CNBP's Room Temperature Confocal Microscope (RTCM).
This will allow for full control and integration of the different lasers, spectrometers and microwaves etc.

This repo will be for modification both at the RTCM control computer, and on private computers - pull from repo to update at start of RTCM sessions.

____PLANS____

--V0--

	+ *.0* LaserQuantum GEM 532 as only laser DONE

	+ *.1* Photon counting - one APD DONE

	+ *.2* Basic confocal controls - scanning, control of positioner DONE

    + *.3* Fix issues with confocal (don't need to close counter)

    + *.4* Create popup saving box

--V1--

g2 capabilities

	+ *.0* Two APDs

	+ *.1* Coincidence measurements

--V2--

	+ *.0* SMIQ

	+ *.1* Pulse shaping

	+ *.2* ODMR

	+ *.3* T1

--V3--

	+ *.0* Spectrometer integration

		Control and readout

		Display through QuDi

--V4--

LaserHW as individual selection through config file

	+ *.0* HeNe (633nm) CW

	+ *.1* Diode (405nm) CW

	+ *.2* Fianium (410-2400nm) Pulse

--V5--

Quality of life updates

	+ *.0* Selection of laser through QuDi GUI, rather than config files