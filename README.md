# Guide to Clone, Install Dependencies and Run the CoffeeShop Website

## Step 1: Clone the Repository

First, you need to clone the repository from GitHub. Open your terminal, navigate to the directory where you want to clone the repository and run the following command:

```bash
git clone https://github.com/SE109-CoffeeShop/coffee-shop-fe.git
```

## Step 2: Navigate to the Project Directory

Once the repository has been cloned, navigate to the project directory by typing:

```bash
cd coffee-shop-fe
```

## Step 3: Copy Environment Variables

For Next.js to function correctly, it needs certain environment variables. Copy the provided  `.env.example`  file and rename it to  `.env`:

```bash
cp .env.example .env
```

Then, open the  `.env`  file and replace the placeholders with your actual data.

## Step 4: Install Dependencies

The next step is to install all the dependencies for the project. You can do this with the following command:

```bash
npm install
```

Make sure you have `Node.js` and `npm` installed on your machine before running this command.

## Step 5: Run the Web Application

Finally, you can run the web application with the following command:

```bash
# To run in dev mode
npm run dev
# To run production mode
npm run start
```

This will start the development server and the application will be accessible at  `http://localhost:3000`  (or whatever port your environment is set to).

# Note

These instructions assume that you have  `git`,  `Node.js`, and  `npm`  installed on your machine. If you don't have these installed, you will need to install them first.