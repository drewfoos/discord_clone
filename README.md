# Discord Clone

This project is a Discord clone built to demonstrate a real-time chat application using modern web technologies. It utilizes Next.js for the frontend, React for interactive UI components, and Prisma with MongoDB for data management. Authentication is handled by Clerk, ensuring secure user management. Shadcn and Uploadthing are used for additional functionalities like theming and file uploads, respectively.

## Features

- Real-time messaging
- User authentication and management with Clerk
- Channels and direct messages
- File uploads using Uploadthing
- Customizable themes with Shadcn
- Responsive design

## Technologies

- **Next.js**: The React framework used for server-side rendering and static site generation.
- **React**: Used for building the user interface components.
- **Prisma**: Serves as the ORM for interacting with the MongoDB database.
- **MongoDB**: The database used to store all user data and chat messages.
- **Shadcn**: Utilized for dynamic theming and style management.
- **Uploadthing**: Handles file uploads, allowing users to share files within messages.
- **Clerk**: Manages user authentication and session management securely.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

```bash
npm install npm@latest -g
```

### Installing

A step-by-step series of examples that tell you how to get a development environment running:

1. Clone the repo:

```bash
git clone https://github.com/yourusername/discord-clone.git
```

2. Install NPM packages:

```bash
cd discord-clone
npm install
```

3. Setup your environment variables:
   - Create a `.env.local` file in the root directory.
   - Add the following lines:

```env
DATABASE_URL="your-database-url"
NEXT_PUBLIC_CLERK_FRONTEND_API="your-clerk-frontend-api-key"
```

4. Run the development server:

```bash
npm run dev
```

This will start the server at `http://localhost:3000`. Open your browser and navigate to this address to see the application in action.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
