## **XMLHttpRequest Example**

This project demonstrates the use of **`XMLHttpRequest`** to make a GET request to the GitHub API. It retrieves information about a user and logs it to the browser's console.

### **Project Structure**

`-index.html`

`-readme.md`

### **Features**

* Fetches data from the **GitHub API** using  **XMLHttpRequest** .
* Logs the request's ready states.
* Displays the number of followers for the specified GitHub user (`aadilkhan08`).

### **Usage**

1. Clone the repository:
   `git clone <repo url>`
2. Open the `index.html` file in a browser.
3. Open the **browser console** to view the following:
   * Ready states (from `0` to `4`)
   * User data fetched from the GitHub API.
   * Number of followers for the user.

### **Code Explanation**

1. **HTML Structure** :
   The HTML contains a basic explanation of the XMLHttpRequest ready states.
2. **JavaScript** :

* **`XMLHttpRequest`** is used to send an HTTP GET request to the GitHub API.
* The **`onreadystatechange`** function logs the different request states.
* If the state is `DONE (4)`, the response is parsed and relevant data is logged.

### **Output**

In the browser console, you will see:

1. Logs of request states (0 to 4).
2. The type of data fetched (object).
3. The number of followers for the specified GitHub user.
