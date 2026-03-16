# Pizza Order Chatbot 🍕🤖

The Pizza Order Chatbot is an interactive conversational system designed to help customers order pizza easily through a chat interface. Instead of calling a restaurant or manually browsing a menu, users can simply chat with the bot, and it will guide them step by step to complete their pizza order. The chatbot collects important information from the user such as pizza type, size, toppings, quantity, email address, and phone number, and then confirms the order.

## How It Works

When the user starts the conversation with a greeting like "Hey broo" or "Order me pizza", the chatbot begins the ordering process. The chatbot first asks the user to select the pizza type, such as veg pizza, chicken pizza, or other available options. After that, the chatbot asks what size of pizza the user prefers, for example small, medium, or large. Once the size is selected, the chatbot continues by asking the user to choose toppings like cheese, olives, mushrooms, or pepperoni.

Next, the chatbot asks the user for the quantity of pizzas they want to order. After collecting the pizza details, the chatbot asks for the customer's email ID and phone number so the order details can be sent to the user and used for contact or delivery purposes. The chatbot uses predefined actions and parameters to capture this information. Parameters such as @sys.email, @sys.number, @size, @pizzatype, @toppings, and @sys.phone-number help the chatbot understand and store the user's input correctly.

## Parameters & Prompts

Each parameter also has a prompt message to guide the user. For example, the chatbot may ask:
- "May I know your email?"
- "Enter the quantity"
- "Choose a size of pizza"
- "What topping do you want?"

## Order Confirmation

After collecting all required information, the chatbot confirms the order using response messages such as:
- "Pizza is booked to your email"
- "Pizza type confirmed"
- "Size confirmed"
- "Toppings confirmed"

Finally, the chatbot displays a confirmation message that the pizza order has been successfully placed.

## Benefits

This chatbot system helps simplify the pizza ordering process by making it fast, interactive, and user-friendly. It also reduces manual work for restaurants and provides a convenient ordering experience for customers through a simple chat conversation. 🍕🤖