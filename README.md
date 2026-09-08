# Joaquin Cerrano

I make audio software. Plug-ins first, then whatever the studio needs around them.

## 🛸 OVNI Audio

Free, open-source spatial audio plug-ins — and one visual synth. Simple interfaces, pro sound backed by real physics: HRTF, Doppler, physical reverberation. No "3D" we can't hear.

**[ORBIT](https://github.com/ovniaudio/orbita)** — binaural movement engine. Place a sound around your head, orbit it, or fly it past with real Doppler. VST3/AU on macOS, VST3 on Windows.

**[SUPERNOVA](https://ovniaudio.com/supernova)** — audio-reactive visual synth. An image or a video becomes 262,144 GPU particles that move with the sound. Bit-exact audio pass-through: it never touches your signal. macOS.

**[The catalog](https://github.com/ovniaudio/ovni)** — PULSAR, NEBULA, DUST, HALO, HORIZON and AURORA, coming back out in waves.

AGPLv3, forever. The macOS builds are signed and notarized by Apple.

## How it's built

C++ and JUCE for the plug-ins — CMake, universal binaries (`arm64` + `x86_64`), `pluginval` and `auval` gated in CI, macOS and Windows on every release. Python, TypeScript and Node for everything around them: tooling, automation, web.

I come at this from the studio side — production and mixing — which is most of the reason the plug-ins have three knobs instead of thirty.

---

**[ovniaudio.com](https://ovniaudio.com)** · [@ovniaudio](https://github.com/ovniaudio) · hello@ovniaudio.com · Argentina
