# My First Coolify App

A simple Node.js web application deployed using Coolify for self-hosted services.

## 🚀 Features

- **Express.js** web server
- **Static file serving** for frontend assets
- **RESTful API endpoints** for health checks and app info
- **Responsive design** with modern UI
- **Easy deployment** with Coolify
- **Auto-restart** capabilities

## 📋 Prerequisites

- Node.js (version 18 or higher)
- npm (comes with Node.js)
- Git
- Coolify installed on your server

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/my-first-coolify-app.git
   cd my-first-coolify-app
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the application**:
   ```bash
   npm start
   ```

4. **Open in browser**:
   Navigate to `http://localhost:3000`

## 🔧 Development

### Running in Development Mode
```bash
npm run dev
```

### Environment Variables
The app uses the following environment variables:
- `PORT` - Port number (default: 3000)
- `NODE_ENV` - Environment mode (development/production)

## 📡 API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/` | GET | Main application page |
| `/api/health` | GET | Health check endpoint |
| `/api/info` | GET | Application information |

### Example API Responses

**Health Check** (`/api/health`):
```json
{
  "status": "healthy",
  "timestamp": "2025-07-08T10:30:00.000Z",
  "uptime": 3600
}
```

**App Info** (`/api/info`):
```json
{
  "name": "My First Coolify App",
  "version": "1.0.0",
  "description": "A simple Node.js app deployed with Coolify",
  "author": "Your Name"
}
```

## 🚀 Deployment with Coolify

1. **Push your code to GitHub**:
   ```bash
   git add .
   git commit -m "Deploy to Coolify"
   git push origin main
   ```

2. **In Coolify Dashboard**:
   - Create new resource → Application
   - Select "Public Repository"
   - Enter your GitHub repository URL
   - Set build command: `npm install`
   - Set start command: `npm start`
   - Deploy!

3. **Environment Configuration**:
   - Coolify will automatically detect this as a Node.js app
   - The app will use the PORT environment variable provided by Coolify
   - No additional configuration needed

## 📁 Project Structure

```
my-first-coolify-app/
├── public/
│   └── index.html          # Frontend HTML page
├── server.js               # Main Express server
├── package.json            # Dependencies and scripts
├── README.md              # This file
├── .gitignore             # Git ignore rules
└── .env.example           # Environment variables example
```

## 🔧 Configuration

### Port Configuration
The app automatically uses the PORT environment variable provided by Coolify. For local development, it defaults to port 3000.

### Static Files
Static files are served from the `public/` directory and are accessible at the root path.

## 🐛 Troubleshooting

### Common Issues

1. **Port already in use**:
   ```bash
   # Kill process using port 3000
   npx kill-port 3000
   ```

2. **Dependencies not installing**:
   ```bash
   # Clear npm cache and reinstall
   npm cache clean --force
   rm -rf node_modules package-lock.json
   npm install
   ```

3. **App not accessible externally**:
   - Ensure your app listens on `0.0.0.0` (handled automatically)
   - Check firewall settings on your server
   - Verify Coolify port configuration

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Express.js](https://expressjs.com/) for the web framework
- [Coolify](https://coolify.io/) for the deployment platform
- [Node.js](https://nodejs.org/) for the runtime environment

## 📞 Support

If you encounter any issues:
1. Check the [troubleshooting section](#-troubleshooting)
2. Look at the Coolify logs for deployment issues
3. Create an issue in this repository

## 🔄 Updates

To update your deployment:
1. Make changes to your code
2. Commit and push to GitHub
3. Coolify will automatically redeploy (if auto-deployment is enabled)

---

**Happy Self-Hosting!** 🎉
