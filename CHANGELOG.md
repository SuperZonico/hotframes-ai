v1.0.0 — 2026-06-23

Initial Release

Core Features


AI upscaling 2x / 4x via RealESRGAN (cinematic, anime, detail modes)
Frame interpolation 2x / 4x / 8x via RIFE v4.6 with scene detection
Color Grading AI — LOG → Rec.709 for 14+ camera profiles
Noise reduction with luma, chroma, shadow, and highlight controls
Deblur engine — lens blur, motion blur, edge recovery, micro contrast
Film grain intelligence — preserve, rebuild, or custom grain profiles
HDR enhancement — SDR → HDR, highlight recovery, detail boost


Interface


Split-screen before/after comparator with draggable divider
Frame scrubber with timecode and playback controls
Sidebar with 7 collapsible module cards
Real-time GPU/CPU monitor in topbar
Preset system — save and load your configurations
Info bar tooltips for every control


Performance


NVENC hardware encoding (H.264, H.265)
fp16 half-precision for maximum GPU throughput
VRAM-adaptive tile sizing (no OOM crashes)
Producer/consumer threading for parallel encode
Intel NPU offload for scene detection and noise profiling


Export


H.264 / H.265 via NVENC (hardware)
ProRes 4444 for DaVinci Resolve round-trip
.cube LUT export from Color Grading settings
Automatic audio preservation from source


Compatibility


Windows 11
NVIDIA RTX 3060 and above
Tested on RTX 5080 Laptop GPU



© 2026 SuperZónico. All rights reserved.
