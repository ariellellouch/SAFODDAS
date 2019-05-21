# DAS

Earthquake records are float32 binary. Their size is [800,1250].
800 channels [fast axis]
1250 time samples [slow axis]
Channel spacing - 1 m
Sampling frequency - 250 Hz (dt = 4 ms)

Cross-correlated waveforms available as .mseed file

Maps, shot locations and receiver locations are provided for the conventional geophone survey. Data are float32 binary, of size [2001,80]
2001 time samples [fast axis]
80 channels [slow axis]
Channel spacing - see geometry file PGSIarray_rec_coords_pos1.txt, nominal ~15m
Sampling frequency - 4 Khz (dt = 0.25 ms)
