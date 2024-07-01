# Yareach Real Estate Hub 

Yareach Homes, is a mern-stack real estate application. In this application, users can create account, view property listings, filter or search the property listings and add them to favorites if they like. Also they can create a listing and put their estate for sale or rent.

**Live demo: [Visite Website](https://final-project-alpha-orcin.vercel.app/)**

## :bulb: Features

- Responsive UI
- Dark and Light Theme
- Infinite Scroll
- JWT Authentication
- Filter Listings
- Search for Location or Title
- Create and Edit Listing
- Notifications and Favorites

## :hammer_and_wrench: Built With

- [Typescript](https://www.typescriptlang.org/) - Main Language
- [React](https://reactjs.org/) - UI Library
- [TailwindCSS](https://tailwindcss.com/) - CSS Framework
- [Zustand](https://zustand-demo.pmnd.rs/) - State Management
- [GraphQL](https://graphql.org/) - Query Language
- [Nodejs](https://nodejs.org/en) - Backend
- [Expressjs](https://expressjs.com/) - Nodejs Framework
- [MongoDB](https://www.mongodb.com/) - NoSQL Database
- [Mongoose](https://mongoosejs.com/) - Database ODM
- [React Icons](https://react-icons.github.io/react-icons/) - Icon Library
- [Bcrypt](https://www.npmjs.com/package/bcryptjs) - Encryption
- [Cloudinary](https://www.cloudinary.com/) - Image Storage

## :camera_flash: Screenshots
![Yareach-home-page](https://github.com/Chimezie1283/final-project/blob/main/Screenshots/Screenshot%20(124).png)
![Create-account-page](https://github.com/Chimezie1283/final-project/blob/main/Screenshots/Screenshot%20(123).png)
![Login-page](https://github.com/Chimezie1283/final-project/blob/main/Screenshots/Screenshot%20(122).png)
![Search-page](https://github.com/Chimezie1283/final-project/blob/main/Screenshots/Screenshot%20(121).png)

## :triangular_flag_on_post: Getting Started

First of all you need to clone the repository and install the dependencies for server and client

```shell

git clone https://github.com/Chimezie1283/final-project.git

cd client

npm install

cd ..

cd server

npm install

```

After doing this you must assign the following environment variables

for client:

```shell

VITE_CLOUD_NAME - Cloudinary cloud name
VITE_UPLOAD_PRESET - Cloudinary upload preset

```

for server:

```shell

MONGODB_URI
JWT_ACCESS_SECRET
JWT_REFRESH_SECRET

```

And run the following commands

```shell

npm run dev
npm run start

```



