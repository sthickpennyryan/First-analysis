Python Project whilst learning Data Analytics with Python


**The purpose of this project was to familiarise myself with utilising python (with pandas and numpy)
and upload raw data and transform it into business ready data.
Actions covered: 
      Importing Data  e.g., SuperStoreOrders = pd.read_csv('Downloads\SuperStoreOrders.csv', sep=',') 
      Removing NULL values e.g., SuperStoreOrders2 = SuperStoreOrders.dropna() 
      Dropping duplicate rows e.g., SuperStoreOrders3 = SuperStoreOrders2.drop_duplicates() 
      Data normalisation - replacing characters and changing data types to enable future analysis e.g., 
      SuperStoreOrders3['sales'] = SuperStoreOrders3['sales'].str.replace('$', '').str.replace(',', '').astype(int) 
      Basic analysis e.g., SuperStoreOrders3['Delivery Days'] = SuperStoreOrders3['ship_date'] - SuperStoreOrders3['order_date']' 

