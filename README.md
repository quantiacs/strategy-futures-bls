# Predict futures use BLS Data (U.S. Bureau of Labor Statistics)

This trading strategy is designed for the [Quantiacs](https://quantiacs.com/contest) platform, which hosts competitions
for trading algorithms. Detailed information about the competitions is available on
the [official Quantiacs website](https://quantiacs.com/contest).

## How to Run the Strategy

### In an Online Environment

The strategy can be executed in an online environment using Jupiter or JupiterLab on
the [Quantiacs personal dashboard](https://quantiacs.com/personalpage/homepage). To do this, clone the template in your
personal account.

### In a Local Environment

To run the strategy locally, you need to install the [Quantiacs Toolbox](https://github.com/quantiacs/toolbox).

## Strategy Overview

This Jupyter notebook outlines a comprehensive strategy for leveraging data from the [U.S. Bureau of Labor Statistics](https://www.bls.gov/) (BLS) to inform trading decisions in the futures market. It begins by introducing the BLS as a key source for
macroeconomic data on prices, employment, compensation, and productivity. The notebook then demonstrates how to access
and utilize BLS datasets using Quantiacs' platform, highlighting the process for filtering and selecting relevant data
sets—specifically, the Average Price Data (AP) dataset focusing on household fuel, motor fuel, and food items.

Through practical examples, the notebook showcases how to list available datasets, inspect their metadata, and filter
series relevant to the U.S. with a substantial history for analysis. It focuses on using Average Price Data for fuel oil
as an indicator, supplemented by futures contract data from the energy sector, to craft a trading strategy. This
strategy employs a multi-pass backtesting approach, combining price indicators with macroeconomic data to decide on
long, short, or neutral positions in Brent Crude Oil futures.

The code sections are detailed, including imports, data loading and preprocessing, strategy definition, and backtesting.
This strategy is presented as a template for users to adapt and integrate into their trading models, complete with links
to documentation and forums for further assistance.
