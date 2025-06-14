# GDG Project

A modern web application built with TypeScript, Vite, and Supabase.
![Todo List Dashboard](https://i.postimg.cc/9MJgLYpV/image.png)
## 🚀 Tech Stack

- **Frontend Framework**: React with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Backend/Database**: Supabase
- **Code Quality**: ESLint

## 📦 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (Latest LTS version recommended)
- npm or yarn
- Git

## 🛠️ Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd gdg
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up environment variables:
Create a `.env` file in the root directory and add your Supabase credentials:
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## 🚀 Development

To start the development server:

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173`

## 🏗️ Build

To create a production build:

```bash
npm run build
# or
yarn build
```

## 📁 Project Structure

```
├── src/              # Source files
├── public/           # Static assets
├── supabase/         # Supabase configuration and migrations
├── components.json   # Component configuration
├── tailwind.config.ts # Tailwind CSS configuration
├── vite.config.ts    # Vite configuration
└── tsconfig.json     # TypeScript configuration
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- Your Name - Initial work

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape this project
- Special thanks to the GDG community for inspiration and support 
