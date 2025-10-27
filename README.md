<div align="center">

# 🏡 Gold
### Seamlessly Connecting Guests with Shortlet Apartment Owners

</div>

## 📖 Overview

**Goldapp** is a web application that connects people looking for short-term apartment rentals with verified apartment owners.  
It makes finding and booking shortlets easy, secure, and transparent — providing a bridge between **guests** who want comfort and **owners** who want visibility.

The goal of Goldapp is to make short-term accommodation booking simple, reliable, and people-focused.

---

## 🚀 Key Features

### 👤 For Guests
- Browse and search available shortlet apartments by **location**, **price**, or **amenities**
- View detailed apartment information including images, reviews, and pricing
- Connect directly with verified owners through in-app chat
- Book apartments securely and receive instant confirmations
- Leave reviews and ratings after your stay

### 🏠 For Apartment Owners
- Create and manage property listings
- Add pricing, availability, and amenities
- Receive direct booking requests or messages from guests
- Manage reservations and respond to guest inquiries quickly

### 🛡️ Platform-Wide
- Secure authentication and user management
- Real-time messaging between guests and owners
- Admin dashboard for moderation and analytics
- Mobile-friendly interface for ease of access

---

## 🧱 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | React.js / Next.js |
| **Backend** | Node.js with Express.js |
| **Database** | MongoDB / PostgreSQL |
| **Authentication** | JWT (JSON Web Tokens) |
| **Real-Time Communication** | Socket.io or Pusher |
| **Hosting / Deployment** | Vercel / Render / AWS |
| **File Storage (Images)** | Cloudinary or AWS S3 |

---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js (v18+)
- npm or yarn
- MongoDB or PostgreSQL instance
- Cloudinary (for images)

### Steps

```bash
# Clone the repository
git clone https://github.com/yourusername/shortletconnect.git

# Navigate to the project
cd shortletconnect

# Install backend dependencies
cd backend
npm install

# Create and configure your environment file
cp .env.example .env
# Add your credentials and connection strings

# Run backend server
npm run dev
