# Smart Agriculture Dashboard 🌱

A modern IoT-powered smart agriculture dashboard built with React, TypeScript, and Tailwind CSS. This application helps farmers optimize water usage, monitor crop health, and make data-driven decisions for sustainable farming.

## 🚀 Features

### 🌾 Crop Management
- **Multi-crop support**: Wheat, Rice, Corn, Tomato, Potato, Cotton, Sugarcane, Onion, Soybean, Chilli
- **AI-powered crop stage detection**: Upload crop images to automatically detect growth stages
- **Growth stage tracking**: Germination, Vegetative, Flowering, Fruiting, Harvest Ready

### 💧 Smart Irrigation System
- **Real-time soil moisture monitoring**: Live IoT sensor data
- **Automated pump control**: Smart irrigation based on moisture levels and weather conditions
- **Weather integration**: Automatic irrigation halt during rain detection
- **Water conservation tracking**: Monitor water usage and savings

### 📊 Analytics & Reporting
- **Real-time dashboard**: Live monitoring of all farm parameters
- **Water usage analytics**: Track consumption and conservation metrics
- **CSV report generation**: Export data for further analysis
- **Conservation rate calculation**: Measure water-saving efficiency

### 🎯 Additional Features
- **Multi-language support**: English, Hindi, Tamil, Telugu
- **Dark/Light mode**: Customizable UI theme
- **Voice input integration**: Voice commands for hands-free operation
- **Responsive design**: Works on desktop, tablet, and mobile devices
- **Real-time notifications**: Instant alerts for critical conditions

## 🛠️ Technology Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS + shadcn/ui components
- **State Management**: React Hooks + TanStack Query
- **Routing**: React Router DOM
- **Icons**: Lucide React
- **Charts**: Recharts
- **Build Tool**: Vite
- **Package Manager**: npm/bun

## 📦 Installation

### Prerequisites
- Node.js (v18 or higher)
- npm or bun package manager

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd smart-agriculture-dashboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   bun install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   bun dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

## 🏗️ Build for Production

```bash
npm run build
# or
bun run build
```

The built files will be in the `dist` directory.

## 📁 Project Structure

```
src/
├── components/           # Reusable UI components
│   ├── ui/              # shadcn/ui components
│   ├── Dashboard.tsx    # Main dashboard component
│   ├── Navbar.tsx       # Navigation component
│   ├── Awareness.tsx    # Educational content
│   ├── DiseaseFinder.tsx # Disease detection
│   └── VoiceModal.tsx   # Voice input modal
├── pages/               # Page components
│   ├── Index.tsx        # Main page
│   └── NotFound.tsx     # 404 page
├── hooks/               # Custom React hooks
├── lib/                 # Utility functions
├── App.tsx              # Main app component
├── main.tsx             # App entry point
└── index.css            # Global styles
```

## 🎨 UI Components

This project uses [shadcn/ui](https://ui.shadcn.com/) for consistent, accessible UI components:

- **Cards**: Display data in organized sections
- **Buttons**: Interactive elements with various styles
- **Select**: Dropdown menus for crop selection
- **Dialogs**: Modal windows for voice input
- **Alerts**: Notification components
- **Charts**: Data visualization components

## 🌐 IoT Integration

The dashboard simulates IoT sensor data including:

- **Soil Moisture Sensors**: Real-time moisture percentage
- **Weather Sensors**: Rain detection and weather status
- **Pump Controllers**: Automated irrigation system control
- **Water Flow Meters**: Usage and conservation tracking

## 📱 Responsive Design

The application is fully responsive and works across:
- **Desktop**: Full dashboard experience
- **Tablet**: Optimized layout for medium screens
- **Mobile**: Touch-friendly interface for smartphones

## 🔧 Configuration

### Environment Variables
Create a `.env` file in the root directory for any environment-specific configurations:

```env
VITE_API_URL=your_api_endpoint
VITE_IOT_ENDPOINT=your_iot_endpoint
```

### Customization
- **Colors**: Modify `tailwind.config.ts` for custom color schemes
- **Components**: Extend or modify components in `src/components/`
- **Crops**: Add new crop types in `src/components/Dashboard.tsx`

## 🚀 Deployment

### Vercel (Recommended)
1. Connect your GitHub repository to Vercel
2. Configure build settings:
   - Build Command: `npm run build`
   - Output Directory: `dist`
3. Deploy automatically on push

### Netlify
1. Connect your repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `dist`

### Other Platforms
The built files in `dist/` can be deployed to any static hosting service.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/new-feature`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature/new-feature`
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **shadcn/ui** for the beautiful UI components
- **Lucide** for the comprehensive icon set
- **Tailwind CSS** for the utility-first CSS framework
- **React** team for the amazing framework

## 📞 Support

For support, email rsrivatsan16@gmail.com or create an issue in the repository.

---

**Built with ❤️ for sustainable agriculture and water conservation**
