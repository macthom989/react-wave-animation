# 🌊 React Wave Animation Component

A modern, customizable wave animation component built with React, TypeScript, Framer Motion, and Tailwind CSS. Perfect for creating engaging section dividers, hero backgrounds, and decorative elements in your web applications.

## 🎥 Demo

[View Live Demo]("#") - Replace with your demo URL

![Wave Animation Preview](preview-image-url)

## ✨ Features

- 🎨 Fully customizable colors, speed, and wave patterns
- 📱 Responsive design that adapts to any screen size
- 🚀 Optimized performance using SVG animations
- 💪 Built with TypeScript for better development experience
- 🛠️ Easy integration with any React/Next.js project
- 🎯 Zero configuration required
- 📦 Lightweight with minimal dependencies

## 📦 Installation

```bash
# Using npm
npm install framer-motion

# Using yarn
yarn add framer-motion
```

## 🚀 Quick Start

```tsx
import WaveAnimation from './components/WaveAnimation';

function App() {
  return (
    <WaveAnimation 
      waveColor="#3B82F6"
      backgroundColor="#1E40AF"
      height={200}
    />
  );
}
```

## 🎨 Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `waveColor` | `string` | `'#3B82F6'` | The color of the waves |
| `backgroundColor` | `string` | `'#1E40AF'` | Background color |
| `height` | `number` | `200` | Height in pixels |
| `waves` | `number` | `3` | Number of wave layers |
| `speed` | `number` | `1.5` | Animation speed in seconds |
| `amplitude` | `number` | `20` | Wave height |
| `frequency` | `number` | `0.08` | Wave density |
| `className` | `string` | `''` | Additional CSS classes |

## 💡 Usage Examples

### Basic Wave
```tsx
<WaveAnimation />
```

### Custom Styled Wave
```tsx
<WaveAnimation 
  waveColor="#22c55e"
  backgroundColor="#064e3b"
  height={150}
  waves={2}
/>
```

### Section Divider
```tsx
<section className="bg-blue-900">
  <div className="container mx-auto py-20">
    <h2>Your Content</h2>
  </div>
  <WaveAnimation 
    waveColor="#ffffff"
    backgroundColor="transparent"
    height={100}
  />
</section>
```

### Animated Footer
```tsx
<footer>
  <WaveAnimation 
    waveColor="#1f2937"
    backgroundColor="transparent"
    height={80}
    speed={1.8}
  />
  <div className="bg-gray-900 text-white py-12">
    Footer content
  </div>
</footer>
```

## 🛠️ Development

```bash
# Clone the repository
git clone https://github.com/macthom989/react-wave-animation.git

# Install dependencies
cd react-wave-animation
npm install

# Run the development server
npm run dev

# Build for production
npm run build
```

## ⚡ Performance Tips

1. **Optimize Wave Count**
   - Use 2-3 waves for better performance
   - Increase waves only when needed for visual effect

2. **Animation Speed**
   - Adjust speed based on use case
   - Slower animations (1.5-2s) work best for backgrounds
   - Faster animations (0.8-1.2s) work well for interactive elements

3. **Mobile Considerations**
   - Reduce height on mobile devices
   - Consider fewer waves on mobile
   - Test performance on various devices

## 🤝 Contributing

Contributions are always welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙌 Support

- Create an [Issue](https://github.com/macthom989/react-wave-animation/issues)
- Send a [Pull Request](https://github.com/macthom989/react-wave-animation/pulls)
- Star the repository if you like it!

Made with ❤️ by [Mac Thom](https://github.com/macthom989)
