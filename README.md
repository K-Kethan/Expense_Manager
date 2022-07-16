This React JS project is an expense tracker which makes note of all the incomes and expenses.
In this project, let's build a **Money Manager** app by applying the concepts we have learned till now.



The app must have the following functionalities

- Initially, Balance Amount, Income Amount, and Expenses Amount should be `0`
- Balance Amount should be calculated by removing the Expenses Amount from the Income Amount in the list of transactions
- Income Amount should be calculated by removing the Expenses Amount in the list of transactions
- Expenses Amount should be calculated by adding only Expenses Amount in the list of transactions
- The `MoneyManager` component is provided with `transactionTypeOptions`. It consists of a list of transaction type objects with the following properties in each object


- Initially, the value of the `titleInput` should be empty
- Initially, the value of the `amountInput` should be empty
- Initially, the first option in the list should be selected
- When a transaction is added, by providing the values in the `titleInput`, `amountInput` and `optionId` and **Add** button is clicked,

  - A new transaction should be added to the transaction history list
  - `totalBalance`, `totalIncome` and `totalExpenses` should be updated accordingly

    ```
    totalBalance = totalIncome - totalExpenses
    ```

  - After updating, the values in the `titleInput`,`amountInput` and `optionId` will be updated to their initial values

- When the delete button in the transaction history is clicked,
  - The respective transaction should be deleted from the transaction history list
  - `totalBalance`, `totalIncome` and `totalExpenses` should be updated accordingly


