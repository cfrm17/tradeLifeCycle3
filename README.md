# Trade Life Cycle Management Part 3

A trade, also called a deal, is an exchange of financial products from one entity to another. The life cycle of a trade is the fundamental activity of exchanges, investment banks, hedge funds, pension funds and many other financial companies.

 All the steps involved in a trade, from the point of order placed and trade execution through to settlement of the trade, are commonly referred to as the trade life cycle. Trade life cycle consists of a series of logical stages and steps.

1.	Pre-sale stage: Marketing persons from investment banks, brokers and dealers introduce various financial products and vehicles to clients. Investors or institutional fund managers survey the market and find the most suitable and competitive products.
2.	Trade execution: After trading negotiations between seller and buyer, an order is placed and the trade is executed. The completion of a buy or a sell order of a financial product is known as Trade Execution.
3.	Trade Capture: After trade execution, the trade is booked in the Front Office system, Middle Office Risk Management system and Back Office system.
4.	Trade Validation and Confirmation: Back office validates trade attributes and confirms trade settlement. Risk Management checks the valuation, risks and limits.
5.	Trade Settlement: Any fee or premium needs to be settled. For a periodic cash settlement trade, such as interest rate swaps or bonds, there is a process of simultaneous exchange of cash between parties at each payment date.
6.	Trade Termination: A trade may be expired at maturity or terminated early. The early termination  could be caused by a position sell or triggered by an early termination provision, such as auto call/cancel, knock-out, etc.

1.	Trade Payment Settlement
This is the process of simultaneous exchange of cash payments or assets periodically between two parties for derivatives (such as swaps) or securities (such as bonds). In the EOD process, FinPricing will automatically compute the cash payments at each payment date for a periodic payment instrument. However, the system also provides an interface for a user to settle or modify cash payment manually.

Click the BackOffice tab at the top-left corner of the application. Then, expend BackOffice -> Action and select the Payment Settlement.

After that, you can either click the Load button to load an existing payment settlement for review/modification or the New button to generate a new cash settlement.

If you click the Load button, a selection window pops up. Expend BackOffice -> Fee -> Book (e.g., Interest Rate) and select a product (e.g., FiBond). All the bond trades having cash settlements within this book are displayed in the main windows

Select a trade and then click the Load button. All the payment settlements of the trade are displayed in the main windows. You can modify the settlements and click the Save button to save all the changes.

Or if you click the New button, a selection window pops up. Expend BackOffice -> Fee -> Book (e.g., Interest Rate) and select a product (e.g., FiBond). All the bond trades within this book are displayed in the main windows.

Select a trade and click the New button. A new payment settlement template is shown in the main window. Fill all fields and click the Save button. The new payment settlement is created.

A security or derivatives could be expired, early terminated or sold. FinPricing allows a user to terminate trades flexibly. 

Click the BackOffice tab at the top-left corner of the application. Then, expend BackOffice -> Action and select the Termination Settlement.

Select a terminated trade and then click the Load button. The termination details of the trade are displayed in the main windows. You can modify the termination information and click the Save button to save all the changes.

Or if you click the New button, a selection window pops up. Expend BackOffice -> Settlement -> Book (e.g., Interest Rate) and select a product (e.g., IrSwap). All the interest rate swap trades within this book are displayed in the main windows.

Select a trade and click the New button. A new trade termination template is shown in the main window. Fill all fields and click the Save button. The trade is terminated



You can find more details at
https://finpricing.com/lib/IrCurveIntroduction.html

