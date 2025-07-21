# Business Nexus - Professional Networking Platform

A full-stack web application connecting entrepreneurs and investors through real-time communication, collaboration requests, and professional networking features.

## 🚀 Live Demo

Professional networking platform is ready!

## ✨ Key Features

### Authentication & Security
- JWT-based authentication system
- Secure password hashing
- Role-based access control (Investor/Entrepreneur)
- Protected routes and middleware

### User Dashboards
- **Investor Dashboard**: Browse entrepreneurs, send collaboration requests, track portfolio
- **Entrepreneur Dashboard**: Manage collaboration requests, view startup metrics, edit profiles
- Real-time statistics and activity feeds

### Real-Time Communication
- WebSocket-powered chat system
- Instant messaging between connected users
- Message history and timestamps
- Online status indicators

### Collaboration System
- Send/receive investment collaboration requests
- Accept/decline request functionality
- Status tracking (pending, accepted, rejected)
- Automated notifications

### Professional Profiles
- Detailed user profiles with company information
- Industry and funding stage categorization
- Portfolio companies and investment interests
- Skills and experience tracking

### Modern UI/UX
- Responsive design for all devices
- Professional styling with Tailwind CSS
- Smooth animations and transitions
- Intuitive navigation and user experience

## 🛠️ Technology Stack

### Frontend
- **React 18** with TypeScript
- **Vite** for fast development and builds
- **Tailwind CSS** for styling
- **Radix UI** components for accessibility
- **TanStack Query** for state management
- **Wouter** for routing

### Backend
- **Node.js** with Express.js
- **TypeScript** for type safety
- **WebSocket** for real-time communication
- **JWT** for authentication
- **bcrypt** for password security

### Database & Storage
- **PostgreSQL** with Drizzle ORM
- In-memory storage for development
- Type-safe database operations

## 📱 User Flows

### For Entrepreneurs
1. Register as entrepreneur
2. Complete profile with startup details
3. Browse potential investors
4. Receive collaboration requests
5. Chat with interested investors

### For Investors
1. Register as investor
2. Set up investment profile
3. Discover promising startups
4. Send collaboration requests
5. Communicate with entrepreneurs

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

## 📁 Project Structure

```
business-nexus/
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/         # Route components
│   │   ├── hooks/         # Custom React hooks
│   │   └── lib/           # Utilities and configurations
├── server/                # Backend Express server
│   ├── routes.ts         # API routes and WebSocket
│   ├── storage.ts        # Data storage layer
│   └── index.ts          # Server entry point
├── shared/               # Shared type definitions
└── package.json         # Dependencies and scripts
```

## 🌐 Deployment

See `DEPLOYMENT_GUIDE.md` for detailed deployment instructions to Vercel and Railway.

## 📈 Metrics & Analytics

The platform includes built-in analytics for:
- User engagement tracking
- Collaboration request success rates
- Message activity monitoring
- Profile view statistics

## 🔒 Security Features

- Password hashing with bcrypt
- JWT token authentication
- Input validation and sanitization
- SQL injection prevention
- XSS protection

## 🎯 Target Audience

- **Entrepreneurs** seeking investment and mentorship
- **Angel Investors** looking for promising startups
- **Venture Capitalists** expanding their deal flow
- **Business Accelerators** connecting their network

---

**Perfect for HR presentations and client demonstrations!**

Built with modern web technologies for scalability, security, and user experience.
