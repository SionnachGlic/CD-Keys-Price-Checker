# CDKeys.com Price Checker

Will check the price of specified games on CDkeys.com, sending a desktop notification if it's at or below the user's maximum price.

cdkeys_price_get_input allows user to enter a url of a desired game on cdkeys.com, and tells them the title and current price. Then asks them the maximum price they're willing to pay and saves these details in a csv.

cdkeys_price_compare Checks the current price of all games on the csv against the user's maximum price, sending a desktop notification if the current price is cheap enough.
