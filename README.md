# Extracting vocal and instrumental
- Using UVR to extract WAV version of instrumental and vocal
- MDX-Net, segment 4000, overlap Default, Model MDSX23C-Karaoke 2 for the best results


# Removing Reverb/Echo
- Using UVR with De-Echo-DeReverb model.

# Pre-processing vocal files using Audacity
- Audacity: open vocal > Effect > Noise Reduction, Effect > Repeat Noise Reduction
- Audacity: open all vocal files, Ctrl + A, Effect > Normalization
- Audacity: open all vocal files, Effect > Truncate Silence (Option: Compress Excess Silence, Threshold -45 dB, duration 0.25, truncate to 0.05)
