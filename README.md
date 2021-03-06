# Blog using STRAPI as backend and GatsbyJS as front-end  

This repo has actually two gatsby apps, one under `./frontend` and the other under `./gatsby-starter-typescript-plus`.

### Getting started

**Clone the repository and install dependencies**

```bash
git clone git@github.com:kilinkis/gatsby-strapy-blog.git
cd blog-strapi-gatsby

# Using yarn
yarn setup:yarn

# Using npm
npm run setup:npm
```

### Scaffold your project

This command will launch both of your backend and frontend servers and do a data migration in your backend server

```bash
# Using yarn
yarn build:yarn
yarn develop:yarn

# Using npm
npm run build:npm
npm run develop:npm
```

Alternatively, you can still start your servers separately:

### Start the backend server

```bash
cd backend

# Using yarn
yarn build
yarn develop

# Using npm
npm run build
npm run develop
```

### Start the frontend server

```bash
cd frontend

# Using yarn
yarn develop

# Using npm
npm run develop
```

Gatsby server is running here => [http://localhost:8000](http://localhost:8000)  
Strapi server is running here => [http://localhost:1337](http://localhost:1337)
