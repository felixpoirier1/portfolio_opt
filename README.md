# portfolio_opt
 ## This project strives to create an optimal portfolio from past market data.
 
 1. Choose your industry (there are 6 currently)
 2. Choose your desired return (there is currently a minor bug, I believe that the conversion to continuous compounding is not done correctly)
 3. Choose if you want to create a log excel file (remember this is a financial tool)
 4. Visualize your data
  - Portfolio weights catplot (only in the portfolio.py file)
  - Efficient frontier (only in the PROJECT.ipynb file)
  - Price action (only in the PROJECT.ipynb file)
  - Statistical inferences graphs (only in the PROJECT.ipynb file)



If you wish to contribute take a look at the "PROJECT.ipynb" file, within this notebook we've written a bunch of functional code that creates visualizations and analysis on the performance of your portfolio. I'm currently adding some of these modular chuncks of code onto the "portfolio.py" file, which I will later use to create a simple functional web app. These should be converted to methods in the overarching optimize function, which belongs to the Portfolio class. To achieve this the optimize function will most likely necessitate being turned into an object of its own.

Thank you for your contributions!
