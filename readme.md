# Pixel Sorter (Web)

minimalist pixel sorter inspired by powdertoy and applications of pixel sorting in glitch art

## Key Features

* **High-Fidelity Recording**: Generates "Pure" WebM files at up to 80Mbps bitrate to eliminate compression artifacts.

* **Smart Color Sorting**: Uses a specialized (Value + Hue Bias) weight formula to prevent thick sediment layers and create clean color transitions.

* **Resolution Handling**: Supports up to 4K images with a smart workspace detector that suggests optimal scaling for real-time performance.

* **Alternating Gravity**: Physics toggle between vertical and horizontal passes every frame to ensure complex 2D gradients.

* **Process Statistics**: Live tracking of render times, average frame duration, and estimated FPS.

## Usage

1. Open the page in any modern web browser (Chrome or Edge recommended for best WebM codec support).

2. Drag and drop an image or click the workspace to upload.

3. Choose to **"Scale to Screen"** for maximum performance or **"Keep Original"** for high-res exports.

4. Click **"Start Sort"** to preview the effect.

5. Click **"Record Sort"** to generate a video file including 1-second static intro/outro buffers.

6. Hover over the status bar during or after the process to view detailed performance statistics.

## Tech Stack

* **Frontend**: HTML5 / Tailwind CSS

* **Icons**: Lucide-React

* **Logic**: Vanilla JavaScript (ES6+)

* **API**: MediaRecorder API (Video), Canvas API (Rendering)

## License

MIT - Feel free to use, modify, and distribute for any creative project.
