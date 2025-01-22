# App-Tasks-Generator

# AI Task Management System

A modern, intelligent task management system powered by AI agents that help organize, suggest, and manage tasks efficiently.

![Project Preview](https://raw.githubusercontent.com/stackblitz/ai-task-management/main/preview.png)

## Features

### 🤖 AI Agents
- **Project Manager**: Coordinates tasks and ensures project goals are met efficiently
- **Developer**: Handles technical implementation with full-stack expertise
- **Designer**: Creates intuitive UI/UX experiences with accessibility in mind

Each agent provides specialized insights and task suggestions based on their expertise.

### 📋 Task Management
- Create and manage tasks with priority levels
- Track task status (pending, in-progress, completed)
- Filter tasks by status, priority, and search terms
- Grid and list view options
- Tag-based organization
- Real-time updates

### 💬 Interactive Chat
- Natural language interaction with AI agents
- Multi-agent collaboration
- Context-aware task suggestions
- Real-time response system

## Tech Stack

- **Frontend**: React with TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **AI Integration**: Google's Generative AI (Gemini)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-task-management.git
cd ai-task-management
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env` file in the root directory and add your Google AI API key:
```
VITE_GOOGLE_AI_API_KEY=your_api_key_here
```

4. Start the development server:
```bash
npm run dev
```

## Usage

1. **Activate Agents**
   - Click on agents to activate/deactivate them
   - Hover over agents to see their full expertise
   - Active agents will participate in task suggestions

2. **Chat Interface**
   - Type messages to interact with active agents
   - Agents will suggest tasks based on their expertise
   - Use the "Add Task" button for quick task generation

3. **Task Management**
   - Toggle between grid and list views
   - Use filters to sort and find tasks
   - Click on tasks to expand/collapse details
   - Update task status and priority with quick actions

## Project Structure

```
src/
├── components/         # React components
│   ├── AgentCard.tsx  # Agent display component
│   ├── AgentChat.tsx  # Chat interface component
│   └── TaskCard.tsx   # Task display component
├── lib/               # Utility functions
│   ├── gemini.ts      # AI integration
│   └── taskParser.ts  # Task parsing logic
├── types/             # TypeScript definitions
└── App.tsx           # Main application component
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Google Generative AI](https://ai.google.dev/) for powering the AI agents
- [Lucide Icons](https://lucide.dev/) for the beautiful icon set
- [Tailwind CSS](https://tailwindcss.com/) for the styling system
