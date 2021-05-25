1. Install jugaad-trader
$ pip install jugaad-trader

2. Login zerodha using jtrader CLI
$ jtrader zerodha startsession

3. Create a file with name zdata.py and copy paste the below script
4. Execute python zdata.py --help command to get all available options
5. Download stock data-
$ python zdata.py -i "NSE:INFY" -f 2020-12-01 -t 2020-12-02 -n minute -o data.csv

6. Download index data-

$ python zdata.py -i "NSE:NIFTY 50" -f 2020-12-01 -t 2020-12-02 -n minute -o data.csv


https://marketsetup.in/posts/download-stock-data-zerodha/#script