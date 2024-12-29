# Naan Mudhalvan Project - BOOK STORE USING MERN STACK
## Team Members
- Hariharaa Sudan S - `` 15F3760781AF5EABEB84B41A8B6EBAD6 ``
- Raymon H Nathan - `` EDE1C2958CEC753910246B2676E352A5 ``
- Senoj S - `` 70D70BF01D9B23FBC9741D2379CFAAF0 ``
- Stanley A - `` FACDA76538784D4B6E4495868C773C48 ``
- Viswanathan V - `` AF466A501CEB740A8F248F6F70674B3D ``

## Demo Video
[![Watch Video](/frontend/src/assets/github-cover.png)]([https://drive.google.com/file/d/1ABCXYZ/view](https://drive.google.com/file/d/1LpIJ0VsMRZ2PM2gAO2D8kGYw-sHaEdKZ/view?usp=drive_link))


## How to run this project:

### For Frontend 
Follow the below steps to run the project: 
- Firstly clone or unzip the project folder.
* Go to the frontend directory by using the following command ``` cd frontend ```.
* * create a **.env.local** file in the frontend root directory as the same level where the **package.json** is located and keep the following environment variables there:
```

VITE_API_KEY="AIzaSyCXvDIC4MPrkaMdeg_O2iij88wLpfj3qBA"
VITE_Auth_Domain="book-store-mern-app.firebaseapp.com"
VITE_PROJECT_ID="book-store-mern-app"
VITE_STORAGE_BUCKET="book-store-mern-app.appspot.com"
VITE_MESSAGING_SENDERID= "205632822247"
VITE_APPID="1:205632822247:web:b0db0ec66bf6de0bbb3b42"
```
+ Then run `` npm install `` commend to install node dependencies.
- Finally, to run the project, use ``npm run dev`` command.


### For Backend
Follow the below steps to run the project: 
- Firstly clone or unzip the project folder.
* Go to the backend directory by using the following command ``` cd backend```.
+ Then run `` npm install `` commend to install node dependencies.
* create a **.env** file in the backend root directory as the same level where the **package.json** is located and keep the following environment variables there: 
```
DB_URL = "mongodb://localhost:27017/book-store"
JWT_SECRET_KEY = 'bc992a20cb6706f741433686be814e3df45e57ea1c2fc85f9dbb0ef7df12308a669bfa7c976368ff32e32f6541480ce9ec1b122242f9b1257ab669026aeaf16'

Note: Please setup mongodb and change the MongoDB url and set your jwt secret key above.
```
- Create the database named '' book-store '' with the collections '' users,books,orders '' 
- Import the JSON documents into its respective collections.
  
- Finally, to run the project, use ``npm run start:dev`` command.
