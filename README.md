# warp-plus
a Python script to get free WARP+ data

### How to use

To use this script, make sure have `python` package installed on your device.
You can use this script on your PC, VPS, or your android smart phone(using __Termux__).
This script uses `requests` package, so you have to install it first:

For __Termux__ :

```shell
pkg install python git && pip install requests
```
##if you want to use this script on your PC or VPS, install `python` and `git` package using your package manager and then run `pip install requests`

Now clone the git on your device:

```shell
git clone https://github.com/samimifar/warp-plus.git
```
Finally, Run the script:

```shell
cd warp-plus/
python3 warp-plus.py
```

notice: You can find your user-id in the `1.1.1.1 App` settings in the Diagnostics menu.
If there wasn't `user-id`, first enable WARP mode and then try again.


[![Run on Repl.it](https://repl.it/badge/github/samimifar/warp-plus)](https://warp-plus.samimifar.repl.run)
