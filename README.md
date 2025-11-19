# 🚗 MobilityHub - Digital Mobility Platform

A modern, interactive React application for a premium vehicle showroom with advanced features including virtual showroom, AR experience, booking system, secure payments, and live chat support.

## 🎨 Design Theme

**Blood Red, Black & Golden Theme:**

- **Blood Red** (`#B22234`): Primary backgrounds and branding
- **Deep Black** (`#111111`): Text, cards, and overlays
- **Golden** (`#FFD700`, `#FFC300`): Buttons, highlights, and accents
- **Typography**: Montserrat, Roboto for modern elegance
- **UI Style**: Rounded buttons, modern icons, elegant transitions

## 📱 Features

### 1. **Virtual Showroom**

- Premium vehicle gallery with 6 luxury cars
- Detailed specifications and pricing
- Interactive vehicle cards with hover effects
- Feature tags and pricing display
- Direct booking integration

### 2. **Augmented Reality (AR) Experience**

- Simulated AR vehicle viewer
- Interactive controls (rotate, zoom, scale)
- Vehicle selection panel
- Real-time AR session status
- Mobile AR support information

### 3. **Smart Booking System**

- Multi-step booking process (3 steps)
- Service type selection (Test Drive/Service)
- Personal information collection
- Scheduling with date/time/location
- Booking summary and confirmation

### 4. **Secure Payment Gateway**

- Multiple payment methods (Card/Digital Wallet)
- Real-time form validation
- Billing address management
- Card number formatting
- Payment processing simulation
- Transaction confirmation with receipt

### 5. **Live Chat Support**

- AI Assistant (Alex) with intelligent responses
- Human agent transfer option
- Quick reply suggestions
- Real-time typing indicators
- Support status dashboard
- FAQ quick access

## 🛠 Technology Stack

- **Frontend**: React 19.2.0
- **UI Components**: Material-UI (MUI) 7.3.5
- **Icons**: Material Icons
- **Styling**: Custom CSS with CSS Variables
- **State Management**: React Hooks (useState, useEffect)
- **Development Server**: React Scripts 5.0.1

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation & Setup

1. **Navigate to Project**

   ```bash
   cd d:/iitgwt_hackathon/mobility-app
   ```

2. **Install Dependencies** (Already done)

   ```bash
   npm install
   ```

3. **Start Development Server**

   ```bash
   npm start
   ```

4. **Open Application**
   - Browser automatically opens at `http://localhost:3000`
   - Or manually visit the URL

## 📁 Project Structure

```
mobility-app/
├── public/
├── src/
│   ├── components/
│   │   ├── Showroom.js      # Vehicle gallery & specs
│   │   ├── ARScreen.js      # Augmented reality viewer
│   │   ├── Booking.js       # Multi-step booking form
│   │   ├── Payment.js       # Secure payment processing
│   │   └── Chat.js          # Live chat support
│   ├── styles/
│   │   └── theme.css        # Global theme & variables
│   ├── App.js               # Main app with navigation
│   └── index.js             # React app entry point
├── package.json
└── README.md
```

## 🎯 Key Components

### Navigation

- **Responsive navbar** with logo and navigation links
- **Active page highlighting** with golden accents
- **Mobile-friendly** navigation design

### Theme System

- **CSS Variables** for consistent theming
- **Responsive design** with mobile breakpoints
- **Smooth transitions** and hover effects
- **Accessibility** compliant color contrasts

### Interactive Elements

- **Card-based layouts** with hover animations
- **Form validation** with real-time feedback
- **Loading states** and progress indicators
- **Icon integration** with Material-UI

## 🌟 Highlights

1. **Modern UI/UX**: Clean, professional design with golden accents
2. **Fully Responsive**: Works seamlessly on desktop and mobile
3. **Interactive Features**: AR simulation, live chat, payment processing
4. **Accessibility**: Proper ARIA labels and keyboard navigation
5. **Performance**: Optimized React components with efficient state management

## 📱 Features in Detail

### Showroom

- 6 premium vehicles (Tesla Model S, BMW M3, Audi e-tron GT, Mercedes AMG GT, Porsche Taycan, Lamborghini Huracán)
- Price ranges from $72,800 to $206,295
- Feature tags and specifications display
- Direct booking and AR view integration

### AR Experience

- Vehicle selection and color visualization
- Interactive controls (rotate, zoom, scale)
- Simulated AR grid and overlays
- Fullscreen mode support

### Booking System

- 3-step process with progress indicator
- Service type selection and validation
- Personal information collection
- Date/time/location scheduling
- Confirmation and email notifications

### Payment Gateway

- Card and digital wallet options
- Form validation and error handling
- Billing address collection
- Secure transaction processing
- Receipt generation and download

### Chat Support

- AI assistant with contextual responses
- Human agent transfer capability
- Quick reply buttons for common questions
- Typing indicators and message timestamps
- Support status and contact information

## 🎨 Customization

The app uses CSS variables for easy theming. Modify colors in `/src/styles/theme.css`:

```css
:root {
  --blood-red: #b22234;
  --deep-black: #111111;
  --golden: #ffd700;
  --golden-alt: #ffc300;
}
```

---

## 📋 Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

---

**Built for iitgwt_hackathon** - A premium digital mobility experience with modern React technology and elegant design.

🚗 **Ready to drive the future of car shopping!** 🌟
#   c a r d e s i g n _ i i t g w t h a c k a t h o n  
 