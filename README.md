# CareerLearn AI - AI-Powered Career Learning Platform

CareerLearn AI is a modern web application that provides personalized learning paths and mentorship opportunities for various tech careers. The platform leverages AI to generate customized learning content and connects learners with industry professionals.


<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/d6d68c88-eb5d-47ae-94bd-9dc6dd4442e6" width="250"/></td>
    <td><img src="https://github.com/user-attachments/assets/bb6ba1ae-10bc-4ee6-988d-3a191f443a17" width="250"/></td>
    <td><img src="https://github.com/user-attachments/assets/cbd053c9-36be-47f3-9318-98044492aba3" width="250"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/7d0deee7-029e-4e6d-ac86-fee807beb392" width="250"/></td>
    <td><img src="https://github.com/user-attachments/assets/e9f5fd48-9c2e-456e-9816-503760757ee3" width="250"/></td>
    <td><img src="https://github.com/user-attachments/assets/fb85d63b-6940-4445-8aab-59a5801b48fd" width="250"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/4a2c5cdf-658c-4762-9910-a117712bb66a" width="250"/></td>
    <td><img src="https://github.com/user-attachments/assets/830fcc0a-93e1-4a48-b9d8-f9914aeb9637" width="250"/></td>
    <td></td>
  </tr>
</table>




## Features

### 🎯 Personalized Learning Paths
- AI-generated curriculum based on career goals
- Custom career path generation
- Progress tracking and milestones
- Interactive learning modules

### 💳 Payment Integration
- Secure payment processing with PaymanAI-SDK
- Subscription management for premium features
- Multi-currency support
- Automated invoicing system

### 👥 Expert Mentorship
- Connect with industry professionals
- Book mentoring sessions
- Real-time feedback on projects
- Career guidance from experts

## Technology Stack

- **Frontend Framework**: Next.js 14
- **Styling**: Tailwind CSS
- **AI Integration**: Google Gemini AI
- **Payment**: PaymanAI-SDK v2.0
- **Icons**: Lucide React
- **Authentication**: PaymanAI-OAUTH
- **Backend**: node websocket server

## Getting Started

### Prerequisites

- Node.js 18+ installed
- PaymanAI-SDK API credentials
- Google Gemini API key

### Environment Setup

1. Create a `.env` file in the root directory:
```env
NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_api_key_here
PAYMAN_API_KEY=your_payman_api_key_here
PAYMAN_SECRET_KEY=your_payman_secret_key_here
PAYMAN_WEBHOOK_SECRET=your_webhook_secret_here
```

### Payment Setup

1. Install PaymanAI-SDK:
```bash
npm install @payman/sdk @payman/oauth
```

2. Initialize PaymanAI in your project:
```typescript
import { PaymanSDK } from '@payman/sdk';

const payman = new PaymanSDK({
  apiKey: process.env.PAYMAN_API_KEY,
  secretKey: process.env.PAYMAN_SECRET_KEY
});
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/eduCareerAI.git
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure

```
src/
├── app/              # Next.js app directory
├── components/       # React components
│   ├── LearningPath/
│   ├── MentorList/
│   └── PaymentForm/  # Payment integration
├── hooks/           # Custom React hooks
│   └── usePayman/   # Payment hooks
└── types/           # TypeScript type definitions
```

## Key Components

### Learning Path Generator
- AI-powered curriculum generation
- Custom career path input
- Progress tracking
- Interactive content

### Payment Integration
- Secure payment processing
- Subscription management
- Transaction handling
- Payment analytics

### Mentor Marketplace
- Expert profiles
- Booking system
- Payment integration
- Session management

## Subscription Plans

### Free Tier
- Basic learning paths
- Community access
- Limited content access

### Premium Tier ($19.99/month)
- Full learning paths
- Priority support
- Unlimited content access

### Professional Tier ($49.99/month)
- Everything in Premium
- 1-on-1 mentoring sessions
- Career coaching
- Certification preparation

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- PaymanAI for payment infrastructure
- Google Gemini AI for content generation
- Unsplash for stock images
