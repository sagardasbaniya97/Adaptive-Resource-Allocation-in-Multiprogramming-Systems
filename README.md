**Adaptive Resource Allocation in Multiprogramming Systems (ARA)**
A real-time web-based dashboard for monitoring and managing system resources with adaptive process priority management.

🎯** Project Overview**

This project implements an Adaptive Resource Allocation system designed for multiprogramming environments. It monitors CPU and memory usage in real-time and dynamically adjusts process priorities based on configurable thresholds.
**

✨ Features**

Real-time Resource Monitoring: Live CPU and memory usage tracking with visual indicators

Process Management: View and manage running processes with priority adjustment

Adaptive Priority Engine: Automatically adjusts process priorities based on resource thresholds

Interactive Charts: Visualize resource usage trends over time

Activity Logs: Track all system actions and priority changes

Configurable Thresholds: Set custom CPU and memory thresholds for priority decisions

CSV Export: Export process data for external analysis

🛠️ Technology Stack

Frontend: React 18 + TypeScript

Styling: Tailwind CSS with custom design system

Charts: Recharts for data visualization

UI Components: Radix UI + shadcn/ui

Build Tool: Vite

State Management: React Hooks

📊 Dashboard Components

Component	Description

System Metrics	Displays CPU, Memory, Cores, and Uptime

Resource Chart	Real-time line chart of resource usage

Process Table	List of active processes with controls

Activity Logs	System event history

Threshold Config	Adjustable priority thresholds

🚀 Getting Started

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

⚙️ How It Works
Monitoring: The system continuously monitors CPU and memory usage

Threshold Check: When usage exceeds configured thresholds, the decision engine activates

Priority Adjustment: Processes are automatically reprioritized to optimize resource allocation

Logging: All actions are logged for audit and analysis

📁 Project Structure

src/

├── components/

│   ├── dashboard/

│   │   ├── Header.tsx

│   │   ├── SystemMetrics.tsx

│   │   ├── ResourceChart.tsx

│   │   ├── ProcessTable.tsx

│   │   ├── ActivityLogs.tsx

│   │   └── ThresholdConfig.tsx

│   └── ui/

├── hooks/

│   └── useResourceMonitor.ts

├── types/
│   └── process.ts

└── pages/
    └── Index.tsx
    
📝 License
This project is created for educational purposes.

Built with ❤️ using React and TypeScript
