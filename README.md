# AMCE Dashboard: Full-Stack Dashboard for Invoice Management

## Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Challenges and Solutions](#challenges-and-solutions)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

**AMCE** is a comprehensive dashboard application designed for managing company invoices. It targets businesses needing large-scale invoice management with a flexible UI, consolidating the ability to view invoices, customers, and dashboard data all in one place.

## Key Features

- **Invoice Management:** Efficiently view and manage invoices.
- **Customer Management:** Access and handle customer data.
- **Dashboard:** Centralized view of all essential data.
- **Responsive Design:** Ensures optimal viewing on any device, with a mobile-first approach.
- **User Interaction:** Smooth and intuitive user experience to enhance engagement.

## Technologies Used

- **Frontend & Backend:** Next.js
- **Validation:** Zod
- **Styling:** Tailwind CSS
- **Version Control:** Git, GitHub

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/TheSaviourEking/next-starter.git
   cd next-starter
   ```

2. **Install dependencies:**

   ```bash
   pnpm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root directory and add your environment variables:

   ```env
    PORT=3000
    POSTGRES_URL=
    POSTGRES_PRISMA_URL=
    POSTGRES_URL_NON_POOLING=
    POSTGRES_USER=
    POSTGRES_HOST=
    POSTGRES_PASSWORD=
    POSTGRES_DATABASE=
    <!--  `openssl rand -base64 32` -->
    AUTH_SECRET=
    AUTH_URL=http://localhost:3000/api/auth
   ```

4. **Start the development server:**

   ```bash
   pnpm dev
   ```

## Usage

To use the AMCE dashboard:

1. **Navigate to the project directory:**

   ```bash
   cd next-starter
   ```

2. **Start the server:**

   ```bash
   pnpm start
   ```

3. **Access the dashboard:**

   Open your browser and go to `http://localhost:3000`.

## Challenges and Solutions

**Challenge:** Utilizing Next.js for backend calls.
- **Solution:** Leveraged server actions, routes, and dynamic routing to handle backend calls effectively. Gained a deep understanding of Next.js conventions to overcome these challenges.

## Contributing

We welcome contributions to enhance the AMCE project. To contribute:

1. **Fork the repository:**

   Click the "Fork" button at the top right of the repository page.

2. **Clone your forked repository:**

   ```bash
   git clone https://github.com/TheSaviourEking/amce-ledger.git
   cd amce-ledger
   ```

3. **Create a new branch:**

   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make your changes and commit them:**

   ```bash
   git commit -m "Add your message here"
   ```

5. **Push to your forked repository:**

   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a pull request:**

   Go to the original repository and click "New Pull Request".

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or suggestions, please feel free to contact:

- **Name:** Saviour Eking
- **Email:** [saviour.eking@outlook.com](mailto:saviour.eking@outlook.com)
- **LinkedIn:** [Saviour Eking](https://www.linkedin.com/in/saviour-eking/)
- **GitHub:** [thesavioureking](https://github.com/thesavioureking)

Thank you for checking out the AMCE Dashboard project!
