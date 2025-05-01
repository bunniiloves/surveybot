# Survey Bot

An automated survey completion platform leveraging AI to generate intelligent, context-aware responses for maximizing survey earnings.

## Key Features

- 🧠 AI-powered response generation using OpenAI
- 👤 Demographic-based response optimization
- 🔄 Automated survey interaction framework
- 🤖 CAPTCHA solving capabilities
- 📊 Comprehensive dashboard and statistics
- 📝 Response template management
- 📚 Machine learning response pattern refinement

## Tech Stack

- **Frontend**: React, TailwindCSS, shadcn/ui
- **Backend**: Node.js, Express
- **Database**: PostgreSQL with Drizzle ORM
- **AI**: OpenAI API (GPT-4o)

## Getting Started

### Prerequisites

- Node.js 18+
- PostgreSQL database
- OpenAI API key

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/survey-bot.git
   cd survey-bot
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file with your environment variables:
   ```
   DATABASE_URL=your_postgresql_connection_string
   OPENAI_API_KEY=your_openai_api_key
   ```

4. Set up the database:
   ```bash
   npm run db:push
   ```

5. Start the development server:
   ```bash
   npm run dev
   ```

## Usage

- Configure bot settings in the Bot Settings page
- Manage your profile details in the Profile Manager
- View active surveys and bot jobs in the Dashboard
- Track earnings in the Earnings Report
- Add custom response templates in the Response Templates page
- Train the bot with the Training Form

## License

[MIT](LICENSE)