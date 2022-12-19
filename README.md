# Creating_a_PyChain_Ledger_using_Streamlit
A simple blockchain based ledger using PyChain with a web interface 
>
## Project Overview
This project uses the Streamlit application to build a PyChain ledger that documents transaction data to a blockchain so that transactions records cannpt be changed or tampered with. It includes a validation process that reports the bloockchain transactions into a dataframe.
>
## Technologies
The project uses Python version 3.9.12, with the the following:
>
-Pandas - version 1.3.5 allows easy creation and manipulation of dataframes
>
-Streamlit - version 1.15.2 enables to application in a web browser that allows users to interact with the ledger
>
-Data Classes - provides both a decorator and function that automatically add generated special methods to classes and allows class blocks to be coded into the application
>
-Typing - enables fundamental support of the types: Any, Union, Tuple, Callable, Typevar and Generic
>
-Hashlib - implements a simple interface to secure hash and message digest algorithms. This project uses SHA265 to create a hexidigest.

## Installation Guide
a) Install the Streamlit application in terminal in a deev environment (pip install streamlit)
>
b) Use vscode to view and edit the pychain.py file
>
## Results
>
Below are examples of the program.
>
### Web interface of PyChain Ledger
![Screen Shot 2022-12-14 at 13 02 12](https://user-images.githubusercontent.com/110360757/208361240-1e631e19-47b1-4b0d-8248-086455d79491.png)
>Note validation of blockchain at base of image, and Block Difficulty slider and Block Inspector in the left sidebar.
>
### Dataframe record confirming blockchain transactions
![Screen Shot 2022-12-14 at 13 02 36](https://user-images.githubusercontent.com/110360757/208361744-b9668e54-ccdc-4d22-80e4-4923978ba01c.png)
