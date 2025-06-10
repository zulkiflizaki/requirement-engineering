# E-commerce "Add to Cart" Feature (Functional vs. Non-Functional Requirements)
This repository hosts a simple web page demonstrating an "Add to Cart" feature for an e-commerce store. It's designed as an in-class activity to help differentiate between functional and non-functional requirements in software development using JavaScript.

## 🚀 Purpose
The main goal of this project is to give you a hands-on way to see how both functional (what a system does) and non-functional (how well a system performs or its qualities) requirements are put into code. By building a basic "Add to Cart" feature, you'll get to see these important concepts in action!

## 📦 Features
This project highlights both types of requirements through its implementation:

**Functional Requirements**
These define what the "Add to Cart" system does:

- **Add Product to Cart**: You can click buttons to add different products (like "Laptop" and "Mouse") to a simulated shopping cart.
- **Update Quantity**: If you add the same product multiple times, its quantity in the cart automatically goes up instead of adding a duplicate entry.
- **Display Cart Items & Total**: The shopping cart area instantly updates to show everything you've added and your running total price.

**Non-Functional Requirements**
These define how well the "Add to Cart" system performs and its qualities:
- **Usability (User Feedback)**: After clicking "Add to Cart," you'll get a visual cue (right now, it's a simple console log, but you can expand it to an on-screen message!). This makes the experience smoother by confirming your action.
- **Robustness (Error Handling)**: The code includes basic checks to stop problems, like preventing you from adding products with invalid prices (e.g., zero or negative amounts). This ensures the system handles unexpected data gracefully.

## 💻 How to Run
It's super simple to get this project running in your browser!

1. Clone the Repository:
Open your terminal or command prompt and run:
```
git clone https://github.com/zulkiflizaki/requirement-engineering.git
```

2. Navigate to the Project Directory:
```
cd requirement-engineering
```

3. Open `index.html`:
Just double-click the `index.html` file in your file explorer. It will open automatically in your default web browser (like Chrome, Firefox, or Edge).

That's it! You should now see the simple e-commerce page with the "Add to Cart" buttons ready for you to try out.

## 🛠️ Technologies Used
- **HTML5**: For the basic structure and content of the web page, including the product listings and the cart area.
- **CSS3**: Handles the minimal styling to make the page look clean and easy to read.
- **JavaScript (Vanilla JS)**: Powers all the interactive logic for adding items to the cart, updating quantities, displaying cart contents, and implementing both the functional and non-functional requirements.

## 🤝 Contributing
This project is mainly for learning, but if you have ideas for improvements, want to add more features (like a "Remove from Cart" button or more advanced non-functional examples), feel free to fork this repository and send in a pull request!

## 📄 License
This project is open-source and available under the **[GNU License](https://eff.org)**. 
