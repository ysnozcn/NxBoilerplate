# NX Boilerplate Project

This is a comprehensive monorepo boilerplate built with NX, featuring Next.js, NestJS, and React Native applications. The project uses Biome for code formatting and linting, providing a modern and efficient development environment.

## 🚀 Features

- **Monorepo Management**: Powered by NX for efficient workspace management and build optimization
- **Modern Tooling**: Uses Biome for fast, efficient code formatting and linting
- **Multiple Applications**: Includes web, API, and mobile applications
- **Type Safety**: Full TypeScript support across all applications
- **Testing**: Integrated Playwright for E2E testing

## 📦 Project Structure

The project consists of the following applications:

```
apps/
├── web-app/        # Next.js web application
├── web-api/        # NestJS backend API
└── mobile-app/     # React Native mobile application
```

### Web Application (Next.js)
- Built with Next.js 14
- Modern React development with TypeScript
- CSS styling with Tailwind CSS
- Server-side rendering capabilities

### Backend API (NestJS)
- Built with NestJS framework
- RESTful API architecture
- TypeScript-based backend development
- Express.js integration

### Mobile Application (React Native)
- Cross-platform mobile development
- Native UI components
- SVG support with react-native-svg
- Shared business logic with other applications

## 🛠 Technology Stack

- **Build System**: NX
- **Code Quality**:
  - Biome (Formatting & Linting)
  - TypeScript
- **Frontend**:
  - Next.js 14
  - React 18
  - Tailwind CSS
- **Backend**:
  - NestJS
  - Express
- **Mobile**:
  - React Native
  - React Native SVG
- **Testing**:
  - Playwright

## 🚦 Getting Started

1. **Clone the repository**
```bash
git clone [repository-url]
cd nx-boilerplate
```

2. **Install dependencies**
```bash
npm install
```

3. **Start development servers**

For web application:
```bash
nx serve web-app
```

For API server:
```bash
nx serve web-api
```

For mobile application:
```bash
nx serve mobile-app
```

## 📝 Development Workflow

### Code Formatting and Linting
The project uses Biome for code formatting and linting. Run the following commands:

```bash
# Format code
npm run format

# Lint code
npm run lint

# Check and auto-fix issues
npm run check
```

### Building Applications

```bash
# Build web application
nx build web-app

# Build API server
nx build web-api

# Build mobile application
nx build mobile-app
```

### Running Tests

```bash
# Run E2E tests
nx e2e [app-name]
```

## 🏗 Project Architecture

### NX Workspace
- Optimized build system with computation caching
- Efficient dependency management
- Shared code and libraries between applications
- Integrated tooling and plugins

### Code Organization
- Modular architecture
- Shared types and utilities
- Consistent coding standards across applications
- Easy to scale and maintain

## 🔧 Configuration

The project includes several configuration files:

- `nx.json`: NX workspace configuration
- `package.json`: Project dependencies and scripts
- `biome.json`: Biome configuration for formatting and linting
- Application-specific configurations in their respective directories

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
