# PyChain Ledger

![alt=""](Images/application-image.png)

In this program, we are building a blockchain-based ledger system with an interface which is user-friendly. The ledger will allow for conducting financial transactions and verify the integrity of the transactions on the ledger.

In this python program as backend with streamlit interface, you will be able to input the details of the transaction in the relevant field. 

To conduct such transactions - 

1. We first create a data class named 'Record', which will serve as the basis for the financial transaction record that the blocks of the ledger will store. This Record data class would contain the 3 critical attributes - 'sender', 'receiver' and 'amount'.

2. The Block data class in then created to store the 'Record' data.

3. Streamlit interface is created to capture the user inputs.

4. Test the PyChain ledger by storing Records.


To run streamlit -

1. Run the terminal of the project folder with the .py notebook in it, run it by using the command 'streamlit run pychain.py'

2. Enter the user values for 'sender', 'receiver' and 'amount' and then click the 'Add Block' button. 

3. Verify the block contents and hashes in the Streamlit dropdown menu. 

[![Video-Demo] // Title
(Images/PyChain Ledger.mp4)]



