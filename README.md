# Joaquin Cerrano

I make audio software. Plug-ins first, then whatever the studio needs around them.

## 🛸 OVNI Audio

Free audio tools: spatial plug-ins, a visual synth, an analyser — and an app and plug-in that read your DAW project for your AI. Simple interfaces, and manuals that describe the actual DSP.

**[ORBIT](https://ovniaudio.com/orbit)** — binaural movement engine. Place a sound around your head, orbit it, or fly it past with real Doppler. VST3/AU on macOS, VST3 on Windows.

**[SUPERNOVA](https://ovniaudio.com/supernova)** — audio-reactive visual synth. An image or a video becomes 262,144 GPU particles that move with the sound. Bit-exact audio pass-through: it never touches your signal. macOS.

**[TELESCOPE](https://ovniaudio.com/telescope)** — an analyser that measures a mix and writes down what it found. VST3/AU on macOS, VST3 on Windows.

**[EYEPIECE](https://ovniaudio.com/eyepiece)** — a Mac app and, from 0.2, a VST3/AU plug-in (on Windows, the VST3 plug-in only) that reads your DAW project and writes a text snapshot for your AI. It doesn't listen to the audio and has no AI inside.

**[The catalog](https://ovniaudio.com/plugins)** — PULSAR, NEBULA, DUST, HALO, HORIZON and AURORA, coming back out in waves.

Free, with no deadline. The macOS builds are signed and notarized by Apple.

## How it's built

C++ and JUCE for the plug-ins — CMake, universal binaries (`arm64` + `x86_64`), `pluginval` and `auval` gated in CI, macOS and Windows on every release. Python, TypeScript and Node for everything around them: tooling, automation, web.

I come at this from the studio side — production and mixing — which is most of the reason the plug-ins have three knobs instead of thirty.

---

**[ovniaudio.com](https://ovniaudio.com)** · [@ovniaudio](https://github.com/ovniaudio) · hello@ovniaudio.com
