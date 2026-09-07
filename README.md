# 🎨 OmniForge 1.1 - AI Image Generator

An elegant, modern web-based AI image generation tool powered by **Flux** and **Gemini** image models. Create stunning artwork with intuitive controls and real-time preview.

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-green.svg)

## ✨ Features

- **Multiple AI Models**: Choose from Flux, Flux Realism, Turbo, or Gemini Flash
- **Flexible Aspect Ratios**: Support for 1:1, 16:9, 9:16, and 4:3 formats
- **Beautiful UI**: Dark-themed, modern interface with gradient accents and smooth animations
- **Image Gallery**: Local browser storage for generated images
- **Watermarking**: Optional watermark feature to stamp "OmniForge" on created artwork
- **Responsive Design**: Optimized for desktop and mobile devices
- **Quick Actions**: Download and fullscreen viewing options
- **Real-time Preview**: Watch your images generate with live status updates

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for API calls to AI models
- No installation required!

### Usage

1. **Open the Application**
   - Open `index.html` in your web browser

2. **Generate Images**
   - Type your image description in the prompt field
   - Press `Enter` or click the generate button
   - Select your preferred AI model and aspect ratio in settings
   - Wait for your artwork to be created

3. **Customize Settings**
   - Click the settings icon (⚙️) to access generation options
   - Choose between different AI models
   - Select desired aspect ratio
   - Toggle watermark on/off

4. **Manage Generated Images**
   - View your image gallery (Gallery button)
   - Download images with the download button
   - View fullscreen with the expand button
   - Clear gallery history when needed

## 🎯 AI Models

| Model | Description | Best For |
|-------|-------------|----------|
| **Flux** | Default model with balanced quality and speed | General use |
| **Flux Realism** | Enhanced for photorealistic images | Realistic artwork |
| **Turbo** | Fast generation with good quality | Quick iterations |
| **Gemini Flash** | Google's fast generative model | Diverse styles |

## 🎨 Customization

### Aspect Ratios

- **1:1** (Square) - 1024×1024px
- **16:9** (Widescreen) - 1280×720px
- **9:16** (Portrait) - 720×1280px
- **4:3** (Classic) - 1024×768px

## 🔧 Technical Details

### Built With

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with gradients and animations
- **JavaScript (Vanilla)**: Client-side logic and state management
- **Tailwind CSS**: Utility-first CSS framework
- **Font Awesome**: Icon library

### Key Components

- **Image Display Container**: Canvas-based image rendering with overlay controls
- **Settings Modal**: Model and aspect ratio selection
- **Gallery Modal**: Local storage management for generated images
- **Fullscreen Viewer**: Enhanced image viewing experience
- **Responsive Layout**: Mobile-friendly design

### Browser Storage

- Gallery data is stored locally using `localStorage`
- Key: `omniforge_gallery`
- Format: JSON array of image objects

## 📱 Keyboard Shortcuts

- **Enter** in prompt field: Generate image
- **Shift + Enter**: New line in prompt
- **Escape**: Close modals (if implemented)

## 🎨 UI Design Features

- **Gradient Backgrounds**: Custom dark theme with subtle gradients
- **Animated Elements**: Pulsing glow effects and smooth transitions
- **Glassmorphism**: Frosted glass effects on cards
- **Custom Scrollbars**: Styled scrollbars matching the theme
- **Responsive Typography**: Inter font family for modern look

## ⚙️ Configuration

Settings can be adjusted in the JavaScript state object:

```javascript
const state = {
    selectedModel: 'flux',        // AI model to use
    selectedRatio: '1:1',         // Aspect ratio
    watermarkEnabled: true,       // Add watermark to images
    isGenerating: false,          // Generation status
    gallery: []                   // Generated images storage
}
```

## 📋 Requirements

- API access to AI image generation services (Flux/Gemini)
- Active internet connection
- Modern JavaScript support (ES6+)

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs and issues
- Suggest new features
- Improve UI/UX design
- Optimize performance

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](./LICENSE) file for details.

## 🐛 Troubleshooting

### Images not generating?
- Check your internet connection
- Verify API endpoints are accessible
- Clear browser cache and try again

### Gallery not saving?
- Ensure localStorage is enabled in browser settings
- Check browser storage isn't full
- Try a different browser if issue persists

### Performance issues?
- Reduce image resolution
- Close other browser tabs
- Clear browser cache
- Try a different AI model (Turbo is fastest)

## 📞 Support

For issues and questions:
- Check existing GitHub issues
- Review the code comments for technical details
- Test in different browsers for compatibility

## 🌟 Features Roadmap

- [ ] User accounts and cloud sync
- [ ] Advanced prompt templates
- [ ] Batch generation
- [ ] Image editing tools
- [ ] Social sharing features
- [ ] API integration documentation

---

**Made with ❤️ by hashes030692-beep**

Enjoy creating amazing AI-generated artwork with OmniForge! 🚀
