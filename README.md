Summary 
Based on the code, the dataset used is titled "Dataset_Generator_for_DTDC.csv". It is a courier and logistics dataset containing 49,639 entries with 42 original features.

Key Dataset Features
The dataset includes the following columns which you should list in your README:

Logistics Info: Origin, Destination, Pouch No, Mode (Surface, Express, Air Cargo).

Client Info: Sender's Name, Phone, Address, City, State, Pincode, and Recipient details.

Consignment Details: Total Pieces, Actual Weight, Volumetric Weight, Chargeable Weight, Nature of Consignment (Dox/Non-Dox).

Financials: Tariff, Value Added Services (VAS) Charges, Total Amount, and Payment Mode (Cash, Card, Wallet).

Data Processing Steps
In your README "Methods" section, you can include these specific Python processing steps found in your notebook:

Cleaning: Removed duplicates and filled missing values (NaNs) for GSTIN, Signatures, and Company Stamps with "0" or "No".

Feature Engineering:

Converted date strings to datetime objects.

Created a delivery_days column (difference between Receive and Sender dates).

Extracted the month of shipping.

Renaming: For better code readability, columns were renamed to use underscores (e.g., Actual Wt to Actual_Weight).

Visualization Insights
Your analysis shows that the "Surface" mode is the most frequently used transport method, and payments are primarily split between Cash, Card, and Wallet.
