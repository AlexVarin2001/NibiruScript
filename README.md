# NibiruScript
**Скрипт для установки нибиру (nibiru-itn1)**
Предварительно необходимо выполнить:
NIBIRU_MONIKER="your_name"
NIBIRU_CHAIN="nibiru-itn-1"
NIBIRU_WALLET="your_name"
echo 'export NIBIRU_MONIKER='${NIBIRU_MONIKER} >> $HOME/.bash_profile
echo 'export NIBIRU_CHAIN='${NIBIRU_CHAIN} >> $HOME/.bash_profile
echo 'export NIBIRU_WALLET='${NIBIRU_WALLET} >> $HOME/.bash_profile
source $HOME/.bash_profile

После скрипта устанавливается последний snapshot с сайта https://app.nodejumper.io/nibiru-testnet/sync
