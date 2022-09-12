# Camping-Companion
A website to find companions for your camping trips!

This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.
Feel free to try the website yourself! https://guarded-reef-23130.herokuapp.com

![Image 1](https://user-images.githubusercontent.com/112682232/189574935-c4aed58d-f4f5-4cd9-b6de-a7661510ca14.png)
![Image 2](https://user-images.githubusercontent.com/112682232/189574963-b4f7d715-4eea-4b86-b129-a64f60623a02.png)
![Image 3](https://user-images.githubusercontent.com/112682232/189574969-51274a7e-1c97-4cb3-814d-2cd5f370bdb8.png)

## Run it locally
1. Install [mongodb](https://www.mongodb.com/)
2. Create a cloudinary account to get an API key and secret code

```
git clone https://github.com/Mohammed-Alsaad/Camping-Companion.git
cd Camping-Companion
npm install
```

Create a .env file in the root of the project and add the following:  

```
DATABASEURL='<url>'
API_KEY=''<key>
API_SECRET='<secret>'
```

Run ```mongod``` in another terminal and ```node app.js``` in the terminal with the project.  

Then go to [localhost:3000](http://localhost:3000/).
