# Block_chain


## As a fintech engineer who’s working at one of the five largest banks in the world, My recent promotion to act as the lead developer on their decentralized finance team. Our task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger. ##


--------

## Technologies

# Imports
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib


## Observations
Following the below process I was able to create the required interface. 
1. Create a Record Data Class
2. Modify the Existing Block Data Class to Store Record Data
3. Adds the cache decorator for Streamlit
4. Add Relevant User Inputs to the Streamlit Interface
5. Test the PyChain Ledger by Storing Records


# Conclusions
Image of Interface.
![Streamlit_interface](bootcamp/Block_chain/images/Block_chain_ledger.png)

## Contributors

By: Roy Booker

---

## License

MIT
