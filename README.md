#!/system/bin/bash"
clear
echo "\033[90m"
read -p "Subscribe My Chanel [ y/t ] : " d;
if [ $d = "y" ]:
then
   echo "\033[1;93mLoading\033[90m...\033[1;97m"
   sleep 2
   termux-open ""
elif [ $d = "t" ]:https://youtube.com/channel/UCGeyn46jU7eu52mymciM0kw
then
   echo "\033[1;93mNext\033[90m...\033[1;97m"
   sleep 1
else
   echo "\033[1;91mWrong Input!!!\033[1;97m"
   sleep 2
   sh bot.sh
fi
echo
echo "\033[1;96m_  _ _  _ _   _ _  _ _     \033[1;91m____ ___  _  _"
echo "\033[1;96m|\ | |  |  \_/  |  | |     \033[1;91m|__| |__] |_/ "
echo "\033[1;96m| \| |__|   |   |__| |___  \033[1;91m|  | |    | \_"
echo
echo "\033[90m{\033[1;91m=====================================\033[90m}"
echo "\033[90m Coded\033[1;91m  :\033[1;93mAlafasy"
echo "\033[90m Youtube\033[1;91m:\033[1;93mMuslimCyber"https://youtube.com/channel/UCGeyn46jU7eu52mymciM0kw
echo "\033[90m Github\033[1;91m :\033[1;96m"
echo "\033[90m{\033[1;91m=====================================\033[90m}"
echo
echo "\033[90m=\033[1;91m--------------------------\033[90m="
echo "\033[1;91m[\033[90m01\033[1;91m]\033[90mNuyul Ceki-Ceki"
echo "\033[1;91m[\033[90m02\033[1;91m]\033[90mNuyul Bacaplus "
echo "\033[1;91m[\033[90m03\033[1;91m]\033[90mNuyul Clipclaps"
echo "\033[1;91m[\033[90m04\033[1;91m]\033[90mNuyul Cashzine "
echo "\033[1;91m[\033[90m05\033[1;91m]\033[90mNuyul Caping   "
echo "\033[1;91m[\033[90m06\033[1;91m]\033[90mNuyul Spincash "
echo "\033[1;91m[\033[90m07\033[1;91m]\033[90mNuyul LuckySc  "
echo "\033[1;91m[\033[90m08\033[1;91m]\033[90mNuyul Buzzbreak"
echo "\033[1;91m[\033[90m09\033[1;91m]\033[90mNuyul Bituro   "
echo "\033[1;91m[\033[90m10\033[1;91m]\033[90mNuyul Yodo     "
echo "\033[1;91m[\033[90m11\033[1;91m]\033[90mNuyul Weviral  "
echo "\033[1;91m[\033[90m12\033[1;91m]\033[90mNuyul Bot Btc  "
echo "\033[1;91m[\033[90m13\033[1;91m]\033[90mNuyul Bot Ltc  "
echo "\033[1;91m[\033[90m14\033[1;91m]\033[90mNuyul BotBch   "
echo "\033[1;91m[\033[90m15\033[1;91m]\033[90mNuyul Bot Doge "
echo "\033[90m=\033[1;91m--------------------------\033[90m="
echo "\033[90m"
read -p "#Choice: " pilih;
if [ $pilih = "1" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   git clone https://github.com/B4N954N2-ID/cekiCrot
   cd cekiCrot
   pkg install python -y
   python ceki-ceki.py
elif [ $pilih = "2" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   cd baca
   nano config.php
   php bot.php
elif [ $pilih = "3" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   cd clip
   nano config.php
   php bot.php
elif [ $pilih = "4" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   cd cz
   nano config.php
   php bot.php
elif [ $pilih = "5" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   cd cap
   nano config.json
   php bot.php
elif [ $pilih = "6" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   git clone https://github.com/BangDanz/spincash
   cd spincash
   php bot.php
elif [ $pilih = "7" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   git clone https://github.com/BangDanz/lcs
   cd lcs
   nano konfig.php
   php bot.php
elif [ $pilih = "8" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   git clone https://github.com/adidoank/buzz
   cd buzz
   php bot.php
elif [ $pilih = "9" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   cd bituro
   nano cnfg.php
   php bot.php
elif [ $pilih = "10" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   cd yodo
   nano config.json
   php bot.php
elif [ $pilih = "11" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   cd weviral
   php bot.php
elif [ $pilih = "12" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   git clone https://github.com/kyo1337/btcclickbot
   cd btcclickbot
   pkg install python -y
   pip install -r requirements.txt
   echo "\033[90m -USAGE :\033[1;93mpython main.py +62(Nomor)"
   sleep 2
elif [ $pilih = "13" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   git clone https://github.com/kyo1337/ltcclickbot
   cd ltcclickbot
   pkg install python -y
   pip install -r requirements.txt
   python main.py
elif [ $pilih = "14" ]:
then
   echo "\033[1;97mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   git clone https://github.com/kyo1337/bchclickbot
   cd bchclickbot
   pkg install python -y
   pip install -r requeirements.txt
   python main.py
elif [ $pilih = "15" ]:
then
   echo "\033[1;93mWaiting\033[90m...\033[1;97m"
   sleep 2
   cd config
   git clone https://github.com/kyo1337/dogeclickbot
   cd dogeclickbot
   pkg install python -y
   pip install -r requirements.txt
   python main.py
else
   echo "\033[1;91mWrong Input!!\033[1;97m"
   sleep 2
   sh bot.sh
fi
