# Contact Book TS

A simple yet powerful contact management application built with TypeScript for type-safe development. This project allows users to efficiently manage their contacts with features like adding, editing, deleting, and searching. Deployed on Vercel for seamless hosting and accessibility.

Live Demo: [Contact Book App](https://contact-book-ts-project.vercel.app/)

## Features

- **Add Contacts**: Easily input new contacts with name, phone, email, and other details.
- **Edit & Delete**: Update or remove existing contacts with intuitive UI controls.
- **Search & Filter**: Quickly find contacts by name or other attributes.
- **Responsive Design**: Works flawlessly on desktop, tablet, and mobile devices.
- **TypeScript Integration**: Ensures robust, error-free code with static typing.
- **Persistent Storage**: Contacts are saved locally (or integrate with backend for cloud sync).

## Tech Stack

- **Frontend**: React with TypeScript for building interactive UIs.
- **Build Tool**: Vite for fast development and bundling.
- **Styling**: CSS Modules.
- **Deployment**: Vercel for easy CI/CD and serverless hosting.
- **Linting**: ESLint for code quality and consistency.
- **Other**: LocalStorage for data persistence (expandable to APIs).

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/bohdan-miskov/contact-book-ts.git
   cd contact-book-ts
   ```

2. Install dependencies:
   ```
   npm install
   ```
   or
   ```
   yarn install
   ```

3. Start the development server:
   ```
   npm run dev
   ```
   or
   ```
   yarn dev
   ```

The app will be available at `http://localhost:5173` (or similar port).

### Build for Production

To create an optimized build:
```
npm run build
```

Deploy the `dist` folder to Vercel or any static hosting service.

## Usage

1. Open the app in your browser.
2. Use the form to add a new contact.
3. Browse the list of contacts.
4. Search for specific contacts using the search bar.
5. Click on a contact to edit or delete it.

For authentication or advanced features (if implemented), refer to the app's login flow.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, open an issue on GitHub or reach out to the maintainer: Bohdan Miskov.

---

*Built with ❤️ using TypeScript and React*
