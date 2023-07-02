## Available Scripts

In the project directory, run the below command in the terminal:
### `npm start`

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

## React Contact Manager
This is a basic contact manager website built with ReactJS. It allows users to input contact information and saves the data in the browser's cache or LocalStorage using the useState and useEffect React hooks.

## Features
User-friendly interface for managing contact information.
Input fields for adding a contact's name, email, and phone number.
The ability to save the contact information and display it in a list.
Automatic saving of contact data in the browser's cache or LocalStorage.
Easy deletion of contacts from the list.


## Technologies Used

ReactJS
JavaScript
HTML
CSS

## Usage
Input the contact's name, email, and phone number in the respective fields.
Click the "Add" button to add the contact to the list.
Existing contacts will be displayed in a list below the input form.
To delete a contact, click the Trash button next to the contact in the list.
## Storage Mechanism
The React Contact Manager uses the useState and useEffect hooks to manage the contact data and store it in the browser's cache.
When a new contact is added or an existing contact is deleted, the contact list is updated using the useState hook.
The useEffect hook is used to monitor changes to the contact list and automatically save it in the browser's cache or LocalStorage.
On page reload, the contact list is retrieved from the cache or LocalStorage and displayed.
