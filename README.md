# Register & Login Application

A simple Register & Login app built with Node.js, Express, and MongoDB.

---

## Steps to Run

1. Install dependencies:
   ```bash
   npm install
   npm start
   ```
If MongoDB connection fails, set it up as follows (macOS users):
   ```bash
   brew tap mongodb/brew
   brew install mongodb-community
   brew services restart mongodb-community
   npm start
   ```
Now the local server will be running properly

**Configure IP Address:**
To test or pass make api call from any platform 
  ```bash
  ipconfig getifaddr en0
  ```


* Open the `index.ts` file.
* Locate the line: `const hostname = '192.168.1.8';`
* Replace `192.168.1.8` with your actual IP address.

  `const hostname = '192.168.1.8';
         server.listen(8080, hostname, () => {
              console.log("Server running on http://${hostname}:8080/");
    }); `


