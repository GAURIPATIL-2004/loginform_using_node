# loginform_using_node


## 🚀 Features

- Built with Node.js and Express
- EJS templating for rendering the login page
- Responsive login form design
- Form data handling via POST method
- Console output of submitted email and password

## 📁 Project Structure

```

project/
│── login.ejs         # Login form UI
├── app.js                # Express server and route handling

````

## 🛠️ Installation & Running

1. Clone the repository:
   ```bash
   git clone https://github.com/GAURIPATIL-2004/loginform_using_node.git
   cd loginform_using_node
````

2. Install the required packages:

   ```bash
   npm install express body-parser ejs
   ```

3. Start the server:

   ```bash
   node app.js
   ```

4. Open your browser and go to:

   ```
   http://localhost:3000
   ```

## 📬 Form Behavior

* Enter an email and password, then submit.
* The server logs the email and password in the console.
* A response message "Login successful!" is shown on the page.

## ⚠️ Note

This is a basic demonstration and **does not** include authentication, session management, or database integration. It is intended for learning or prototyping purposes.

