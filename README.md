# Presidential Bank — MoneyMoney Extension
Plugin Homepage: https://github.com/rosch100/Presidential-Bank-MoneyMoney
Bank/Portal: https://www.presidentialpcbanking.com
Version: **1.01**
Status: Username/Passwort + MFA; Cookie-Import optional
Hub (gemeinsame Tools/Doku): https://github.com/rosch100/moneymoney-extensions
## Installation
Unsignierte Datei: [Presidential Bank.lua](https://raw.githubusercontent.com/rosch100/Presidential-Bank-MoneyMoney/main/Presidential%20Bank.lua)
Datei nach `~/Library/Containers/com.moneymoney-app.retail/Data/Library/Application Support/MoneyMoney/Extensions` kopieren, oder im Klon `./link_ext.sh` ausführen.
Unsignierte Plugins: MoneyMoney-**Beta**, Signaturprüfung in den Erweiterungseinstellungen aus.
## Tests
`sh
python3 tests/test_conformance.py
luajit tests/test_presidential_bank.lua

`
Aus dem Repo-Root ausführen.

