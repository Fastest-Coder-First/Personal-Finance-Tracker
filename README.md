<h1 align="center">Personal Finance Tracker</h1>

<br>

<p style="text-align: justify;">
<b>Personal Finance Tracker</b> is an intuitive web application, developed with the assistance of GitHub Copilot, that empowers users to effortlessly manage their budget and expenses. With seamless integration of cloud and local backup options, users can securely store and access their financial data anytime, anywhere.</p>

## Made with

| Tech used               | For        |
| ----------------------- | ---------- |
| HTML + CSS + JavaScript | Frontend   |
| Node + Express          | Backend    |
| MongoDB                 | Database   |
| Vercel                  | Hosting    |
| GitHub Copilot          | Assistance |

## Team Personal-Finance-Tracker


- Jayanth
- Prashanth
- Hareessh

## Setup process

Run the below command in the root directory to install all required packages for the backend server:

```
npm install
```

Create an OAuth client ID in Google cloud console with the below info:

```
# Authorized JavaScript origins

http://localhost:4000
https://localhost:4000

# Authorized redirect URIs

http://localhost:4000/api/auth/google/callback
https://localhost:4000/api/auth/google/callback
```

Create a **secrets.env** file in the root directory with content like below:

```
PORT = 4000
FRONTEND = http://localhost:4000
MONGO_URI = <MongoDB url>
GOOGLE_CLIENT_ID = <Client ID from Google cloud console>
GOOGLE_CLIENT_SECRET = <Client secret from Google cloud console>
CALLBACK_URL = /api/auth/google/callback
PASSPORT_SECRET = <anyRandomText>
```

## Running process

Run the below command in the root directory:

```
node index.js
```