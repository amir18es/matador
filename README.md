1⃣ ابتدا پیش نیاز های سورس نصب میکنیم‌ :

🔸 sudo apt-get update; sudo apt-get upgrade; sudo apt-get install tmux; sudo apt-get install luarocks; sudo apt-get install screen; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev; sudo apt-get update; sudo apt-get install; sudo apt-get install upstart-sysv

🔹 wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz;tar zxpf luarocks-2.2.2.tar.gz;cd luarocks-2.2.2 && ./configure; sudo make bootstrap;sudo luarocks install luasocket;sudo luarocks install luasec;sudo luarocks install redis-lua;sudo luarocks install lua-term;sudo luarocks install serpent;sudo luarocks install dkjson;sudo luarocks install lanes;sudo luarocks install Lua-cURL

🔸 cd ..
======================
* سپس سورس را کلون میکنیم :**
🔺 git clone https://github.com/MaTaDoRTeaM/MaTaDoR
======================
وارد شماره‌ ربات میشویم و  یه ربات (api) با
 @Botfather 
میسازیم اسم و ایدی وارد میکنیم (سپس باید اینلاین را فعال کنیم 
/setinline
 میزنیم و بعد ایدی ربات رو میزنیم در اخر یه ok میفرسیم‌)
======================
سپس‌ با شماره ربات، ربات
 @userinfobot 
را استارت کرده و ایدی عددی شماره ربات را کپی میکنیم کرده ...
======================
* وارد مسیر زیر میشویم**
MaTaDoR/api/bot/bot.lua
در خط [3] توکن ربات (api) که مرحله سوم با شماره ربات ساخیم وارد میکنیم.
در خط [5] ایدی سودو اصلی یعنی خودتون قرار میدید
سپس در خط [30] ایدی عددی خودتان و ربات (cli) که در مرحله سوم گرفتیم قرار میدهید
سیو میکنیم‌ خارج میشیم‌ ....
======================
وارد مسیر زیر میشیم‌
MaTaDoR/cli/plugins/Tools
در خط [2] ایدی عددی سودو قرار میدهید .
سیو میکنم‌ خارج میشیم‌....
سپس وارد مسیر زیر میشویم 
MaTaDoR/cli/bot/bot.lua
و بعد در خط [19] ایدی ربات (api) و سودو را وارد میکنیم  توجه داشته باشید ایدی عددی ربات (api) اول توکن نوشته شده است
سیو میکنم‌ خارج میشیم‌....
======================
دستورات زیر در ترمینال وارد کنید ...
▪️cd MaTaDoR/cli

▫️chmod +x matador.sh

▪️chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh

▫️./matador.sh install && ./matador.sh

صبر میکنیم تا کامل نصب بشه 

شماره ربات وارد مکنید کد میزنید‌
از سرور خارج و دوباره وصل میشید...
کد های زیر را در سرور میزنیم 
▪️cd MaTaDoR/api

▫️chmod +x matador.sh

▪️chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh

▫️./matador.sh install && ./matador.sh
از سرور خارج و دوباره وصل میشید...
======================
 اینجا ربات نصب شده برا لانچ کردن ...
کد زیر در سرور میزنید 
▪️killall screen

▫️cd MaTaDoR/cli

▪️tmux

▫️ screen ./auto.sh

سپس کلید Ctrl+b را میگیرید روی D کلیک میکنید
کد های زیر میزنیم
▫️tmux

▪️cd MaTaDoR/api

▫️  ./auto.sh

توجه داشته باشید بعد از لانچ شده ربات (api) یا همون هلپر وارد شماره ربات میشم و ربات (api) که در مرحله سوم ساختیم /start میکنیم ...
======================
💢یه مورد راجب سورس
 کسای که رباتشون میدون قرار خیلی گروه داشته باشه و دوست ندارن هنگ کنه ربات  با شماره ایران بزنن سرعتش خودتون میبینید =))
