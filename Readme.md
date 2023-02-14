# Express Mongo JWT boilerplate

<!-- ![Witch Boilerplate](./logo.webp) -->

A quick template to work on Express, Mongo and JWT backend API's
<br>
<br>

## How to install locally
<br>
<br>

### Set up the mongodb

<br>

Create a mongodb Atlas database, for it you will need to have an account on their site (https://www.mongodb.com/atlas/database) and set up a cluster.

Go to your cluster page, it should look like this.


![Image 1](manual_capture_1.png)

Click on Connect on the top right side of the page, there you will find the instructions for connecting your application to the remote database.

![Image 2](manual_capture_2.png)

Copy the connection string to your clipboard

<br>
<br>

### Create a .env file

<br>

Create a file name .env with the following content. Remember that you should have the connection string copied to your clipboard. Paste it in the first field.
```env:
MONGO_URL = {your_mongo_atlas_connection_string}
JWT_PASSWORD = {Your_jwt_private_token_password}
```

<br>
<br>

### Install dependencies

<br>

On the project directory, install the dependencies using the following command.

```bash:
npm i
# or npm install
```
<br>
<br>

### Start the application

<br>

Use the following command

```bash:
npm run dev
# or npm run start
```

<br>
<br>

