# modernmart-ecommerce
A full-stack MERN e-commerce application with modern features including real-time updates, PWA capabilities, and Stripe payment integration.

## Dependencies
- ES7+ React/Redux/React-Native snippets
- Prettier - Code formatter
- ESLint
- Thunder Client (API testing)
- MongoDB for VS Code
- GitLens
- Auto Rename Tag
- Bracket Pair Color DLW

## 🚀 Features
- User authentication with JWT
- Product catalog with search and filtering
- Shopping cart and wishlist
- Stripe payment integration
- Admin dashboard
- Real-time inventory updates
- PWA with offline functionality

## 🛠️ Tech Stack
- **Frontend:** React 18, Context API, React Router v6
- **Backend:** Node.js, Express.js, MongoDB
- **Payment:** Stripe
- **Authentication:** JWT
- **Real-time:** Socket.io
- **Deployment:** Vercel/Railway

## 📁 Project Structure
modernmart-ecommerce/
├── client/          # React frontend
├── server/          # Node.js backend
├── shared/          # Shared utilities/types
└── docs/            # Documentation

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- MongoDB Atlas account
- Stripe account

### Installation
```bash
# Clone repository
git clone https://github.com/yourusername/modernmart-ecommerce.git

# Install dependencies
npm run install-all

# Set up environment variables
cp .env.example .env
# Edit .env with your values

# Run development servers
npm run dev