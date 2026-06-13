# Silver Hoofs Pre-School Hub

Welcome to the Silver Hoofs Pre-School Hub repository. This project serves as the main web portal for Silver Hoofs Pre-School, offering a user-friendly and modern interface for prospective parents and visitors.

## Quick Start

### Prerequisites
- Node.js 18+ (recommend latest LTS) and npm 9+
- Git

### Installation

```bash
# Install dependencies
npm install

# Start the dev server
npm run dev
```

### Building for Production

```bash
# Build the application
npm run build

# Preview the production build
npm run preview
```

## Technologies Used

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## Environment Variables

For WhatsApp integration to work properly, create a `.env` file from `.env.example`:

```bash
cp .env.example .env
```

And configure `VITE_WHATSAPP_NUMBER` with your full international phone number (digits only). Example: `VITE_WHATSAPP_NUMBER=919980444424`.
