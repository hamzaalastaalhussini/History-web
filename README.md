# Echoes of Change

An interactive educational timeline showcasing major historical inventions and their impact on society. This project features 3D models and AR experiences for key historical artifacts.

## Features

- Interactive timeline of historical inventions
- 3D model viewer for each invention
- AR (Augmented Reality) support for mobile devices
- Responsive design for all screen sizes
- Detailed historical information and context

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Google's Model Viewer for 3D/AR visualization
- WebXR for AR experiences

## Getting Started

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Open the project in your local server:
```bash
python -m http.server 8000
```

3. Access the website at `http://localhost:8000`

## AR Experience

To use the AR features:
1. Access the website on a mobile device
2. Click on any invention's AR button
3. Allow camera access when prompted
4. Point your camera at a flat surface
5. Tap to place the 3D model in your space

Note: AR works best on Android (Chrome) or iOS (Safari) devices.

## Project Structure

```
├── index.html          # Main timeline page
├── styles.css          # Global styles
├── ar/                 # AR experience pages
│   ├── spinning-jenny.html
│   ├── telephone.html
│   ├── lightbulb.html
│   └── ...
└── models/            # 3D model files
    ├── spinning-jenny.glb
    ├── telephone.glb
    └── ...
```

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details. 