# Modern Full Stack ECommerce Application with Stripe & Sanity

**Fully responsive Modern Full Stack Ecommerce application with Payments functionality**. Modern design, animations, ability to add and edit products on the go using a CMS, advanced cart functionalities, and the complete integration with Stripe so that you can cover real payments.

- Advanced React Best Practices such as:
  - Folder and file structure, hooks and refs
  - Advanced State Management of the entire application using React Context API
- Next.js Best Practices such as:
  - File-based routing, Data fetching that allows server-side rendering and static generation which makes your websites incredibly optimized (show getServerSideProps, getStaticPaths, getStaticProps), and you’ll also learn how to use Next.js as a backend endpoint.
- Stripe to manage payments, products, shipping rates, and the entire checkout process
- Manage the content of the app using Sanity. Sanity is the unified content platform that’ll make the making of the entire app possible.
- Through Sanity, clients will be able to change the store’s homepage and more importantly, the details of all the products in the store
- Sanity allows us to focus on developing the application without having to worry about the content, file storage, and databases.

## System Requirements

To get started with development, you need to install few tools

1. git

   `git` version 2.13.1 or higher. Download [git](https://git-scm.com/downloads) if you don't have it already.

   To check your version of git, run:

   ```shell
    git --version
   ```

2. node & npm

   `node` version 16.15.1 or higher. Download [node](https://nodejs.org/en/download/) if you don't have it already.
   `npm` version 5.6.1 or higher. You will have it after you install node.

   To check your version of node or npm, run:

   ```shell
    node --version
    npm --version
   ```

## Setup

To set up a development environment, please follow these steps:

1. Clone the repo

   ```shell
    git clone https://github.com/pinjamar/ecommerce-web-shop
   ```

2. Change directory to the project directory and install nextjs

   ```shell
   cd ecommerce-web-shop
   npx create-next-app
   ```

   Now copy the dependencies from the package.json file.

3. Next step is running the app, do that by first changing the folder to the "ecommerce-sanity", after that install npm and run the app

   ```shell
   npm install --legacy-peer-deps
   npm run dev
   ```

   Project will be running in the browser.

   Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

4. To continue setup, stop the app by clicking ctrl+c and install Sanity (yes to all prompts in terminal)

   ```shell
   npm install -g @sanity/cli
   ```

   "Project name" - ecommerce-sanity; "Default dataset configuration" - yes, "Template" - Clean project with no predefined schemas.
   Go to .gitignore file and remove "/" in front of node_modules so git doesn't copy them.

   Start the sanity by typing:

   ```shell
   npx sanity dev
   ```

   Copy the files in the "schemas" folder and add some content through the sanity to start working. That's it!
