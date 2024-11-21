Dynamic Form Generator

A React-based application that allows you to create dynamic forms by defining a JSON schema. Edit, preview, and deploy forms instantly using this intuitive tool.

Features

==> Live JSON Editor**:Edit your JSON schema in real-time with validation feedback.
==> Generate forms instantly based on the schema.
==>Seamless light and dark mode toggle.
==>Download or copy the JSON schema for reuse.
==>Schema validation ensures proper field definitions.
==>Includes text, email, select, radio, checkbox, textarea, and more.

Technologies Used

- **Frontend**: React.js, Tailwind CSS, React Hook Form
- **State Management**: React State Hooks
- **JSON Validation**: Built-in error detection
- **Deployment**: Vercel
Tools Used

* * VScode


You must have installed the below software to run your website

- Node.js
- npm (or yarn)

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Pratyusha123-prog/zigmentfrontend_123
    
    ```

2. **Install dependencies:**

    ```bash
    npm install
   
    ```

3. **Start the development server:**

    ```bash
    npm start
   

4. Open your browser and navigate to:

    ```
    http://localhost:3000
    ```
## ✨ Demo

Check out the Dynamic form Generator:(https://zigmentfrontend-537.vercel.app/)


### JSON Schema Examples

#### **Registration Form**
```json
{
  "formTitle": "User Registration Form",
  "formDescription": "Please fill in your details below.",
  "fields": [
    { "label": "Name", "type": "text", "id": "name", "required": true },
    { "label": "Email", "type": "email", "id": "email", "required": true },
    { "label": "Password", "type": "textarea", "id": "password" },
    { "label": "Gender", "type": "select", "id": "gender",
      "options": [
     { "value": "Male", "label": "Male" },
     { "value": "Female", "label": "Female" },
     { "value": "Other", "label": "Other" }]
    }]
}
