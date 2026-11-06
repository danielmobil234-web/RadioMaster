# RadioMaster

A small, self-contained loop studio for Windows and modern desktop browsers. It includes a four-bar arranger, browser-generated sample layers, per-track mute/solo/volume controls, tempo and master volume, and microphone recording that adds a take as a looping track.

## Run it

Open `index.html` in Microsoft Edge or another current browser. Most features work locally; microphone recording requires a secure context, so use `http://localhost` or HTTPS and allow microphone access when prompted. No install or external audio files are required.

For a quick local server, open PowerShell in this folder and run:

```powershell
py -m http.server 8000
```

Then visit `http://localhost:8000`.

## Use it

- Press **Play** to start the four-bar loop; press **Stop** to return to the beginning.
- Change BPM or the master slider in the transport.
- Use **Add layer** to add generated drum, bass, keys, pad, percussion, or synth loops.
- Use **M** and **S** to mute or solo a layer; adjust its volume with the slider.
- Press **Record**, allow microphone access, then press **Stop recording**. The take is added as a loop layer.
- Press **Space** to toggle playback.

Sessions and recordings are held in browser memory and are not saved after closing or reloading the page.
