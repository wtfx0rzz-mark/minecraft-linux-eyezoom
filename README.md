# minecraft-linux-eyezoom
Minecraft Eyezoom for Linux.


Made with GPT Astra

**Eye Ruler — Requirements and compatibility**

* **Requires:** Minecraft Java **1.16.1**, Fabric Loader **0.15.11+**, and Java **8+**. Install only one Eye Ruler JAR. Other Minecraft versions are unsupported.
* **Graphics:** Use **Fast or Fancy** graphics in first person. Fabulous graphics and post-processing shaders are unsupported. Rendering-mod compatibility is not guaranteed.
* **Dependencies:** Fabric API, OBS, an external capture application, and a physically tall monitor are **not required**.
* **Controls:** **Z** toggles the live overlay. **O** toggles precision sensitivity (`0.012727597`) and restores the previous value. Both bindings are configurable.
* **Ninjabrain Bot:** Select **Tall resolution**, set its height to **16384**, and manually match its boat sensitivity to `0.012727597` when precision mode is active. O does not update Ninbot automatically. Enable precision before recording a fresh boat reset and keep sensitivity unchanged throughout the measurement. See the [boat measurement guide](https://github.com/Ninjabrain1/Ninjabrain-Bot/wiki/Boat-measurements).
* **Displays:** Layout adapts to the game’s framebuffer size. External monitors are not specifically excluded, but mixed-DPI/fractional-scaling configurations are unverified. Smaller windows may show fewer ruler divisions. **16384 is the virtual calibration height**, not your monitor resolution.https://www.virustotal.com/gui/file/3deee9a50bc3fe20883fa635d1b1d764d69e67e3a33aada6e796152977c0f8be?nocache=1
* **Performance:** The overlay performs an additional world-render pass and may reduce FPS. No minimum CPU/GPU specification or universal performance guarantee has been established.
* **Compatibility:** Tested through user gameplay on Linux; Windows/macOS and arbitrary modpacks are not fully validated. Mods that change sensitivity, including StandardSettings, may override precision mode—check the live sensitivity shown in the overlay.
* **Behavior:** Both views remain live. No automatic aiming, frozen-image inspection, or game pausing. Camera bob, hurt shake, and nausea distortion are suppressed while the overlay is active.
* **Configuration:** `config/eye-ruler.json`; restart Minecraft after editing.

VirusTotal Scans:

https://www.virustotal.com/gui/file/3deee9a50bc3fe20883fa635d1b1d764d69e67e3a33aada6e796152977c0f8be?nocache=1

https://www.virustotal.com/gui/file/579ab3c094731f675df79c56d8123c576d4fd43e260ebe22481ce5df43d48c1f?nocache=1
