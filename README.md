## Installation

To install the project dependencies and configure your environment variables, follow these steps:

1. Create a `.env` file in the root of your project.
2. Add the following environment variables to your `.env` file:

```plaintext
PORT=8080
DATABASE_URL=mongodb+srv://img-upload:img-upload@cluster0.on5vjba.mongodb.net/dashboard
JWT_SECRET=cf475a60-5389-479f-ae71-7df358e8e7b3
```

3. Save the `.env` file.

## Running the Project

To run the project, use the following command:

```sh
npm i install
npm run dev
