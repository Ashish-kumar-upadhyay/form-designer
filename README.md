# Form Designer

## Overview
This is a **Visual Form Designer** built using **HTML, CSS, and Vanilla JavaScript/jQuery**. It allows users to dynamically create, edit, reorder, and delete form elements. The form structure is based on a provided sample JSON and includes drag-and-drop reordering.

## Features
- **Add Elements:** Input fields, Select menus, Textareas, and Checkboxes can be added dynamically.
- **Edit Elements:** Users can edit labels and placeholders.
- **Reorder Elements:** Drag-and-drop functionality to change element order.
- **Delete Elements:** Remove elements from the form.
- **Manage Select Options:** Add and remove options for select fields.
- **Save Form:** Console logs the saved JSON structure.
- **Dark Mode Toggle (Bonus).**
- **Preview & Copy HTML (Bonus).**

## Technologies Used
- **HTML** for structure
- **CSS** for styling
- **JavaScript (Vanilla & jQuery)** for interactivity

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/form-designer.git
   cd form-designer
   ```
2. Open `index.html` in a browser.

## Deployment
The project is hosted on **Netlify**. You can access the live demo [here](https://formtask111.netlify.app).

## JSON Format Example
```json
[
  {
    "id": "unique-id",
    "type": "input",
    "label": "Sample Input",
    "placeholder": "Sample placeholder"
  },
  {
    "id": "unique-id",
    "type": "select",
    "label": "Sample Select",
    "options": ["Option 1", "Option 2"]
  }
]
```

## Contributing
Feel free to contribute by opening issues or pull requests.

## License
This project is open-source under the **MIT License**.

