# Sample Roll

A piano roll that plays your own audio files. Import MP3s into the pool, click the grid, and each note plays the sample repitched to that key.

- Press **+** on the home screen to start a song. Songs, including their imported audio, are saved in your browser (IndexedDB) on this device.
- Sample root notes are detected automatically (YIN pitch detection). You can override the root per sample.
- Snap to 1/4, 1/8, 1/16 or 1/32. Hold **Shift** to place notes freely, and press **Q** to quantize.
- **Export WAV** renders the song offline.

It's a single static `index.html` with no build step. To run it locally:

```bash
python -m http.server 5173
```
