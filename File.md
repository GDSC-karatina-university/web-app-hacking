## Download

Node and npm
### GNU/Linux
```
sudo apt install nodejs npm
node -v
```

### Windows users 
```
https://nodejs.org/en/download/
```
Open command prompt and check version
```
node -v
```

Download juiceShop for the node version you have installed.
```
https://github.com/juice-shop/juice-shop/releases/
```

# Running the server
Extract the tar file and inside the extracted folder run
```
npm start
```

You should see this if it starts successful.
```
> juice-shop@13.2.2 start /home/k3lv1n/juice-shop
> node build/app

info: All dependencies in ./package.json are satisfied (OK)
info: Chatbot training data botDefaultTrainingData.json validated (OK)
info: Detected Node.js version v14.19.1 (OK)
info: Detected OS linux (OK)
info: Detected CPU x64 (OK)
info: Configuration default validated (OK)
info: Required file server.js is present (OK)
info: Required file index.html is present (OK)
info: Required file styles.css is present (OK)
info: Required file main.js is present (OK)
info: Required file tutorial.js is present (OK)
info: Required file polyfills.js is present (OK)
info: Required file runtime.js is present (OK)
info: Required file vendor.js is present (OK)
info: Port 3000 is available (OK)
info: Server listening on port 3000
```
If you get any UnhandledPromiseRejectionWarning ignore them.

## Testing
Open browser and navigate to:
```
http://localhost:3000
```

# Install burpsuite (Community edition)
Requires you have java installed.
Linux users using Kali Linux and Parrot Security distributions dont need this because its
already included

# Windows users
```
https://portswigger.net/burp/releases/professional-community-2022-2-4?requestededition=community
```