# Coffee Machine Using OOP

This is a simple coffee machine simulation implemented in Python using object-oriented programming (OOP) principles. The program allows users to interact with the coffee machine by selecting drinks from a menu, checking the resources, and making payments.

## Components

- **main.py**: The main script that runs the coffee machine simulation. It interacts with the user, processes their choices, and manages the overall flow of the program.

- **coffee_maker.py**: Contains the `CoffeeMaker` class, which models the coffee machine. It handles the resources (water, milk, coffee) and provides methods for reporting, checking resource sufficiency, and making coffee.

- **menu.py**: Defines the `Menu` class and `MenuItem` class. The `Menu` class holds a list of available drinks, and the `MenuItem` class represents each drink with its name, ingredients, and cost.

- **money_machine.py**: Implements the `MoneyMachine` class, which manages the money-related operations. It handles the process of accepting coins, making payments, and tracking profits.

## How to Run

1. Clone the repository to your local machine:

    ```bash
    git clone git@github.com:Sakib-Dalal/Coffee-Machine-Using-OOP.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Coffee-Machine-Using-OOP
    ```

3. Run the main script:

    ```bash
    python main.py
    ```

## Usage

1. When prompted, enter the desired drink name or other commands such as "off" to turn off the machine or "report" to get a resource and profit report.

2. Follow the on-screen instructions for making a payment if required.

3. Enjoy your virtual coffee!

## Contributing

Feel free to contribute by opening issues or submitting pull requests. Your feedback and improvements are welcome!

---

*This project is developed by [Your Name]. For more details, please visit the [GitHub repository](git@github.com:Sakib-Dalal/Coffee-Machine-Using-OOP.git).*
