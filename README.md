# Simple Auth
This project demonstrates **Basic Authentication** with Node.js and Express.  
A demo account is hardcoded for testing.
- **Username**: `admin`  
- **Password**: `12345`
---

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/minhchau-07/simple_auth.git
   cd simple_auth

2. Install dependencies: npm install

3. Start the server: node basic_auth.js

4. Server running on http://localhost:3000
"Welcome! Visit second public resource."

### Test with Postman
Method: GET
URL: http://localhost:3000/secure
Authorization->Basic Auth
Success Response: You have accessed a protected resource 🎉
Wrong credentials: Access denied.

