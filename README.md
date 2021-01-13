# LiveTicker
Live price ticker game\
For now only support BTC/USDT Binance


basically starts a live price feed on the btc/usdt pair on Binance and allows to demo-trade using buy and sell buttons.
The PnL of the current position is calculated in the second row, while the total PnL of all positions is calculated at the bottom of the screen.

Buy and Sell buttons are used to open / close long and short positions.

Compiled by buildozer

## buildozer dependencies
`requirements = python3,kivy,requests,urllib3,websockets,asyncio,six,gevent,greenlet,zope.event,zope.interface,setuptools,chardet,certifi,idna`

## buildozer android permissions
`android.permissions = INTERNET`

## buildozer versions
* `osx.python_version = 3.8.5`
* `osx.kivy_version = 2.0.0`

## general notes
* added the SSL certificate as an env var
