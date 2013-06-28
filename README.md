CryptsyPythonAPI
================

API for Cryptsy.com Exchange utilizing completely built-in functions and utilities of Python 2.7.

Usage
-------------
Create buy order for dgc, market id 26, then cancels all orders you have for dgc
```python
import Cryptsy
Exchange = Cryptsy.Cryptsy('KEY HERE', 'SECRET HERE')
Exchange.createOrder(26, "Buy", 100, 0.00000001)       # Buy 100 dgc at .00000001 each
Exchange.cancelMarketOrders(26)                        # Cancels all orders in market 26, dgc
```

