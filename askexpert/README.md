# AskExpert Platform 🧠

> AI-powered expert consultation platform that connects knowledge seekers with domain experts

## 🚀 Live Demo
- **Frontend:** [View Live Demo](https://your-demo-link.netlify.app)
- **GitHub:** [Source Code](https://github.com/yourusername/askexpert-platform)

## 📋 Overview

AskExpert is a modern web platform that allows domain experts to register their expertise and provide AI-enhanced consultations. Users can ask questions to specific experts, and the platform uses Google's Gemini AI to generate contextual responses based on the expert's pre-defined FAQs and knowledge base.

## ✨ Features

### For Experts
- 📝 **Expert Registration** - Create profiles with expertise areas and bio
- ❓ **FAQ Management** - Add frequently asked questions and answers
- 📊 **Question Tracking** - Monitor questions asked by users
- 🤖 **AI Enhancement** - Responses generated using Gemini AI based on expert's knowledge

### For Users
- 🔍 **Expert Discovery** - Browse and select experts by expertise area
- 💬 **Question Submission** - Ask questions to specific experts
- ⚡ **Instant Responses** - Get AI-generated answers in expert's style
- 📱 **Responsive Design** - Works seamlessly on all devices

## 🛠️ Tech Stack

### Frontend
- **React 18** with TypeScript
- **Axios** for API calls
- **CSS3** with modern styling
- **Responsive Design**

### Backend
- **Node.js** with Express
- **TypeScript** for type safety
- **Google Gemini AI API** for response generation
- **CORS** enabled for cross-origin requests

### Storage
- **In-memory storage** (easily replaceable with MongoDB)
- **RESTful API** design

## 🏗️ Architecture

```
askexpert-platform/
├── client/                 # React frontend
│   ├── src/
│   │   ├── App.tsx        # Main application component
│   │   ├── App.css        # Styling
│   │   └── ...
│   └── package.json
├── server/                 # Node.js backend
│   ├── src/
│   │   ├── server.ts      # Express server
│   │   └── ...
│   └── package.json
└── README.md
```

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Google Gemini API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/askexpert-platform.git
   cd askexpert-platform
   ```

2. **Setup Backend**
   ```bash
   cd server
   npm install
   
   # Create .env file
   echo "GEMINI_API_KEY=your_api_key_here" > .env
   
   # Start server
   npm run dev
   ```

3. **Setup Frontend**
   ```bash
   cd ../client
   npm install
   npm start
   ```

4. **Access the application**
   - Frontend: http://localhost:3000
   - Backend: http://localhost:5000

## 🔧 Configuration

### Environment Variables
Create a `.env` file in the server directory:
```env
GEMINI_API_KEY=your_google_gemini_api_key
PORT=5000
```

### API Endpoints
- `POST /api/experts` - Register new expert
- `GET /api/experts` - Get all experts
- `POST /api/ask` - Ask question to expert
- `GET /api/questions/:expertId` - Get questions for specific expert

## 📱 Usage

### For Experts
1. Click "Become an Expert"
2. Fill in your details and expertise area
3. Add as many frequently asked questions with answers
4. Submit registration

### For Users
1. Browse available experts on the homepage
2. Click "Ask Question" on any expert card
3. Enter your email and question
4. Get instant AI-powered response

## 🎨 Screenshots

### Expert Registration
![Expert Registration](./screenshots/expert-registration.png)

### Expert Dashboard
![Expert Dashboard](./screenshots/expert-dashboard.png)

### Question Interface
![Question Interface](./screenshots/question-interface.png)

## 🔮 Future Enhancements

- [ ] **User Authentication** - JWT-based login system
- [ ] **Payment Integration** - Stripe for paid consultations
- [ ] **Real-time Chat** - WebSocket integration
- [ ] **Expert Ratings** - User feedback system
- [ ] **MongoDB Integration** - Persistent data storage
- [ ] **Email Notifications** - Question alerts for experts
- [ ] **Advanced Search** - Filter experts by skills, ratings, price
- [ ] **Mobile App** - React Native implementation

## 🧪 Testing

```bash
# Run frontend tests
cd client
npm test

# Run backend tests
cd server
npm test
```

## 🚀 Deployment

### Frontend (Netlify)
```bash
cd client
npm run build
# Deploy build folder to Netlify
```

### Backend (Railway/Render)
```bash
cd server
npm run build
# Deploy to Railway or Render
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Your Name**
- GitHub: [@nakravineet](https://github.com/nakravineet)
- LinkedIn: [vineetnakra](https://linkedin.com/in/vineetnakra)
- Email: nakravineet3@gmail.com

## 🙏 Acknowledgments

- Google Gemini AI for powering the intelligent responses
- React community for excellent documentation
- Express.js for the robust backend framework

---

⭐ **Star this repository if you found it helpful!**
