RTL-SDR IQ Viewer (Flutter Desktop for Windows)
Current release: v1.3.0

A real-time viewer for raw IQ data from RTL-SDR dongles (RTL2832U + R820T2 / R860), built with Flutter Desktop for Windows and the rtlsdr Dart package (FFI bindings to librtlsdr).

Two ways to look at raw IQ:

Live — the app detects the dongle, opens it, tunes it, streams raw IQ samples continuously and displays them live: a real-time FFT spectrum + waterfall with automatic signal detection and classification, separate I/Q waveform charts, a table of the most recent raw samples (unsigned 0–255 and signed −128..127), plus live statistics (samples received, data rate in MB/s, elapsed time).
Inspection — the Data Source card picks what to inspect: any raw IQ capture from disk (rtl_sdr dumps, cs16/cf32, SigMF, …) or the live stream itself, and opens it in a separate IQ Packet Viewer window that breaks the data into packets and shows exactly what is inside each one.
