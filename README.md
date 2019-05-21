# DAS

Earthquake records are float32 binary. Their size is [800,1250].
800 channels [fast axis]
1250 time samples [slow axis]
Channel spacing - 1 m
Sampling frequency - 250 Hz (dt = 4 ms)

Cross-correlated waveforms available in the zip file. This include an .mseed file as well as python .npy arrays. The filename indicates the depth of the central receiver used for estimation. These traces are a stack of 7 different one-day correlations. 

Maps, shot locations and receiver locations are provided for the conventional geophone survey. Only the first 2 shots are used (SP1 and SP2). Data are float32 binary, of size [2001,80]
2001 time samples [fast axis]
80 channels [slow axis]
Channel spacing - see geometry file PGSIarray_rec_coords_pos1.txt, nominal ~15m
Sampling frequency - 4 Khz (dt = 0.25 ms)

**All data are unprocessed - trace editing is required.**
