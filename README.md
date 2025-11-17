# AI Life Companion

> AI powered life companion app for Indian professionals - unified calendar, mood tracking, productivity feed, and smart AI suggestions

## 🎯 Overview

AI Life Companion is a context aware productivity and wellness app designed specifically for Indian solopreneurs and working professionals. It combines:

- **Smart Calendar Integration** - Unified view of Google/Outlook/LinkedIn calendars
- **Mood & Wellness Tracking** - Daily mood logs with AI powered insights
- **Productivity Feed** - Personalized suggestions based on your schedule and habits
- **Privacy First** - Complete user control over data sharing and AI interactions

## 🏗️ Tech Stack

### Frontend
- **Web**: Next.js, React, TailwindCSS
- **Mobile**: React Native (future)

### Backend
- **API**: Node.js/Express
- **AI Services**: Python (FastAPI) for mood analysis, suggestions, summaries
- **Database**: Supabase (PostgreSQL)
- **Authentication**: Supabase Auth

### Infrastructure
- **Hosting**: Render
- **Version Control**: GitHub
- **CI/CD**: GitHub Actions

## 📁 Repository Structure

```
ai-life-companion/
├── apps/
│   ├── web/                  # Next.js web app
│   └── mobile/               # React Native app (future)
│
├── backend/
│   ├── api/                  # Express API server
│   └── ai-services/          # Python AI microservices
│
├── packages/
│   ├── ui/                   # Shared UI components
│   ├── utils/                # Shared utilities
│   └── hooks/                # Shared React hooks
│
├── infra/
│   ├── supabase/             # DB schema, migrations, policies
│   └── deployment/           # Docker, CI/CD configs
│
└── docs/                     # Documentation
```

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- Python 3.10+
- Supabase account
- Git

### Setup

1. **Clone the repository**
```bash
git clone https://github.com/swrpdsn/ai-life-companion.git
cd ai-life-companion
```

2. **Install dependencies**
```bash
npm install
```

3. **Setup environment variables**
```bash
cp .env.example .env
# Add your Supabase, API keys, etc.
```

4. **Run development server**
```bash
npm run dev
```

## 🗄️ Database Schema

Core tables:
- `users` - User profiles and auth
- `moods` - Daily mood tracking entries
- `calendar_events` - Unified calendar data
- `suggestions` - AI generated recommendations
- `settings` - User preferences and privacy controls

See `infra/supabase/schema.sql` for complete schema.

## 🎨 MVP Features

- [x] User onboarding and FTUX
- [ ] Calendar sync (Google/Outlook)
- [ ] Mood tracker with daily logging
- [ ] AI suggestion engine
- [ ] Unified activity feed
- [ ] Privacy settings dashboard
- [ ] Web responsive UI

## 📦 Roadmap

### Phase 1 - MVP (Current)
- Core features: calendar, mood, suggestions
- Web app only
- Basic AI integrations

### Phase 2 - Growth
- Mobile app (React Native)
- Advanced AI personalization
- Social features (optional)
- Pro/Premium tier

### Phase 3 - Scale
- Enterprise features
- Team collaboration
- API for third party integrations

## 🤝 Contributing

Contributions welcome! Please read our contributing guidelines first.

## 📄 License

MIT License - see LICENSE file for details

## 📧 Contact

For questions or feedback:
- GitHub Issues: [Create an issue](https://github.com/swrpdsn/ai-life-companion/issues)
- Email: (add your email)

---

**Built with ❤️ for Indian professionals**
