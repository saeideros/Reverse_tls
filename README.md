**به زودی اپدیت میشود**
![R (2)](https://github.com/Azumi67/PrivateIP-Tunnel/assets/119934376/a064577c-9302-4f43-b3bf-3d4f84245a6f)
نام پروژه : ریورس تانل WS + WSS[TLS]
---------------------------------------------------------------

-----------
**توضیح کوتاه در مورد این پروژه :**

- حتما در سرور تست، نخست تانل را ازمایش کنید و سپس اقدام به استفاده از آن بکنید.
- تمامی تست های من با سرورهای کاملا فیلتر شده بوده است.
- در این اسکریپت شما یا با WS، ریورس تانل را برقرار میکنید یا با TLS
- در این ریورس تانل ممکن است سرعت بالایی در اسپید تست نگیرید اما من مشکلی در یوتیوب و اینستاگرام با ایپی کاملا فیلتر شده نداشتم.
- از TCP و UDP پشتیبانی میکند.
- ریست تایمر برای سرویس های خود را بر اساس نیاز خودتان تعیین کنید.
- در این تانل میتوانید چندین سرور خارج را به یک سرور ایران وصل کنید. اگر از این ریورس تانل راضی بودید، میشود تعداد سرور خارج و ایران را افزایش داد.
- حتما ریست تایمر سرور خارج و ایران یکسان باشد.
- پنل شما در خارج باید نصب شده باشد
- اگر به هر دلیلی پیش نیاز ها برای شما نصب نشد و خطا گرفتید، دوباره امتحان بفرمایید.
- همیشه اگر مشکلی در تانل شما است در قسمت status و لاگ های تانل، سرویستان را نگاه کنید.
- من در وقت آزاد این را درست کردم و ممکن است اشتباهاتی هم داخلش باشد. پیشاپیش ببخشید.

------------------------
![307981](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/39b2794b-fd04-4ae5-baea-d4b66138766e)
 **فهرست :**
 ----------------------
 
**دسترسی سریع به اسکریپت** >> **[کلیک](https://github.com/Azumi67/KCP_tunnel#%D8%A7%D8%B3%DA%A9%D8%B1%DB%8C%D9%BE%D8%AA-%D9%85%D9%86)**
- **امکانات** >> **[کلیک](https://github.com/Azumi67/KCP_tunnel/tree/main#%D8%A7%D9%85%DA%A9%D8%A7%D9%86%D8%A7%D8%AA)**
- **تک سرور** : 
- **تانل KCP TCP تک کانفیگ** >> **[کلیک](https://github.com/Azumi67/KCP_tunnel/tree/main#%D8%AA%D8%A7%D9%86%D9%84-kcp-tcp-%D8%AA%DA%A9-%DA%A9%D8%A7%D9%86%D9%81%DB%8C%DA%AF)**
-  **تانل KCP + ICMP تک کانفیگ** >> **[کلیک](https://github.com/Azumi67/KCP_tunnel/tree/main#%D8%AA%D8%A7%D9%86%D9%84-kcp--icmp-%D8%AA%DA%A9-%DA%A9%D8%A7%D9%86%D9%81%DB%8C%DA%AF)**
-  **تانل KCP TCP مولتی کانفیگ (1 یا چند سرور خارج)** >> **[کلیک](https://github.com/Azumi67/KCP_tunnel/tree/main#%D8%AA%D8%A7%D9%86%D9%84-kcp-tcp-%D9%85%D9%88%D9%84%D8%AA%DB%8C-%DA%A9%D8%A7%D9%86%D9%81%DB%8C%DA%AF)**
- **تانل KCP + ICMP مولتی کانفیگ** >>  **[کلیک](https://github.com/Azumi67/KCP_tunnel/tree/main#%D8%AA%D8%A7%D9%86%D9%84-kcp--icmp-%D9%85%D9%88%D9%84%D8%AA%DB%8C-%DA%A9%D8%A7%D9%86%D9%81%DB%8C%DA%AF)**
- **تانل KCP + PrivateIP کانفیگ** >> **[کلیک](https://github.com/Azumi67/KCP_tunnel#%D8%AA%D8%A7%D9%86%D9%84-kcp--privateip-%DA%A9%D8%A7%D9%86%D9%81%DB%8C%DA%AF)**
- **اسکریپت های کارآمد** >> **[کلیک](https://github.com/Azumi67/KCP_tunnel#%D8%A7%D8%B3%DA%A9%D8%B1%DB%8C%D9%BE%D8%AA-%D9%87%D8%A7%DB%8C-%DA%A9%D8%A7%D8%B1%D8%A2%D9%85%D8%AF-)**

--------------
![check](https://github.com/Azumi67/PrivateIP-Tunnel/assets/119934376/13de8d36-dcfe-498b-9d99-440049c0cf14)
**امکانات**
-

- پشتیبانی از TCP و UDP
- قابلیت تانل بر روی چندین پورت
- امکان استفاده از ایپی 4 و 6
- امکان استفاده از ساب دامین در ریورس تانل ( باید برایش cert گرفته شود)
- امکان استفاده از چند سرور خارج و یک سرور ایران
- امکان حذف تمامی تانل ها و سرویس ها

 ------------------------------------------------------

![147-1472495_no-requirements-icon-vector-graphics-clipart](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/98d8c2bd-c9d2-4ecf-8db9-246b90e1ef0f)
 **پیش نیازها**

 - لطفا سرور اپدیت شده باشه.
 - میتوانید از اسکریپت اقای [Hwashemi](https://github.com/hawshemi/Linux-Optimizer) و یا [OPIRAN](https://github.com/opiran-club/VPS-Optimizer) هم برای بهینه سازی سرور در صورت تمایل استفاده نمایید. (پیش نیاز نیست)


----------------------------

  
  ![6348248](https://github.com/Azumi67/PrivateIP-Tunnel/assets/119934376/398f8b07-65be-472e-9821-631f7b70f783)
**آموزش**
-
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**تانل ریورس WS ایپی 4** [TCP]
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : WS TCP > IPV4 > IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/242cb93c-708e-4d2f-8ae7-d2469665e75c" alt="Image" />
</p>



- نخست سرور ایران را کانفیگ میکنیم
- اگر خطای GIT CLONE در نصب پیش نیاز ها گرفتید، دوباره تلاش کنید
- من دو سرور خارج داشتم پس عدد 2 را وارد میکنم.
- پورت تانل را 443 قرار میدهم.
- پورت های سرور اول من 8080 و 8081 میباشد . اینگونه وارد میکنم 8080,8081
- پس از آن، کلیدی برای سرور اول ب GENERATE میشود. باید از این کلید در سرور اول خارج استفاده کنید.
- پورت های سرور دوم خارج من 8082 و 8083 میباشد . پس اینگونه وارد میکنم : 8082,8083
- کلید سرور دوم خارج هم GENERATE میشود و از آن در سرور دوم خارج، استفاده خواهیم کرد.
- ریست تایمر را هم هر 2 ساعت انتخاب میکنم.
----------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج اول** 

**مسیر : WS TCP > IPV4 > KHAREJ 1**




 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/5173ace4-40a1-4a57-a88b-c9d179680667" alt="Image" />
</p>

- سرور خارج اول را کانفیگ میکنیم.
- ایپی 4 سرور ایران را وارد میکنم.
- پورت تانل که 443 قرار داده بودم
- کلیدی که برای سرور اول خارج GENERATE شده بود را اینجا PASTE میکنم.
- پورت های کانفیگ سرور اول خارج 8080 و 8081 بود پس اینگونه وارد میکنم : 8080,8081
- ریست تایمر هم که عدد 2 را وارد کرده بودیم. ( باید ریست تایمر یکسان باشد که همه سرویس ها همزمان ریست شوند)


--------------------------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج دوم** 

**مسیر : WS TCP > IPV4 > KHAREJ 2**




 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/5305f0d1-d346-4789-8e84-04450cfac0ca" alt="Image" />
</p>

- سرور خارج دوم را کانفیگ میکنیم.
- ایپی 4 سرور ایران را وارد میکنم.
- پورت تانل که 443 قرار داده بودم
- کلیدی که برای سرور دوم خارج GENERATE شده بود را اینجا PASTE میکنم.
- پورت های کانفیگ سرور دوم خارج 8082 و 8083 بود پس اینگونه وارد میکنم : 8082,8083
- ریست تایمر هم که عدد 2 را وارد کرده بودیم. ( باید ریست تایمر یکسان باشد که همه سرویس ها همزمان ریست شوند)


--------------------------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**تانل ریورس WS ایپی 6** [TCP]
-
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : WS TCP > IPV6 > IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/505f3ca5-e556-45a3-936d-9c291d0700cf" alt="Image" />
</p>



- نخست سرور ایران را کانفیگ میکنیم
- اگر خطای GIT CLONE در نصب پیش نیاز ها گرفتید، دوباره تلاش کنید
- من دو سرور خارج داشتم پس عدد 2 را وارد میکنم.
- پورت تانل را 443 قرار میدهم.
- پورت های سرور اول من 8080 و 8081 میباشد . اینگونه وارد میکنم 8080,8081
- پس از آن، کلیدی برای سرور اول GENERATE میشود. باید از این کلید در سرور اول خارج استفاده کنید.
- پورت های سرور دوم خارج من 8082 و 8083 میباشد . پس اینگونه وارد میکنم : 8082,8083
- کلید سرور دوم خارج هم GENERATE میشود و از آن در سرور دوم خارج، استفاده خواهیم کرد.
- ریست تایمر را هم هر 2 ساعت انتخاب میکنم.
----------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج اول** 

**مسیر : WS TCP > IPV6 > KHAREJ 1**




 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/16ff88a5-4d9b-4f52-a917-307fc4db6842" alt="Image" />
</p>

- سرور خارج اول را کانفیگ میکنیم.
- ایپی 6 سرور ایران را وارد میکنم.
- پورت تانل که 443 قرار داده بودم
- کلیدی که برای سرور اول خارج GENERATE شده بود را اینجا PASTE میکنم.
- پورت های کانفیگ سرور اول خارج 8080 و 8081 بود پس اینگونه وارد میکنم : 8080,8081
- ریست تایمر هم که عدد 2 را وارد کرده بودیم. ( باید ریست تایمر یکسان باشد که همه سرویس ها همزمان ریست شوند)


--------------------------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج دوم** 

**مسیر : WS TCP > IPV4 > KHAREJ 2**




 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/381d4353-e541-4f77-aaaf-88600438d21a" alt="Image" />
</p>

- سرور خارج دوم را کانفیگ میکنیم.
- ایپی 6 سرور ایران را وارد میکنم.
- پورت تانل که 443 قرار داده بودم
- کلیدی که برای سرور دوم خارج GENERATE شده بود را اینجا PASTE میکنم.
- پورت های کانفیگ سرور دوم خارج 8082 و 8083 بود پس اینگونه وارد میکنم : 8082,8083
- ریست تایمر هم که عدد 2 را وارد کرده بودیم. ( باید ریست تایمر یکسان باشد که همه سرویس ها همزمان ریست شوند)


--------------------------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**تانل ریورس WS ایپی 4** [UDP]
-
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : WS UDP > IPV4 > IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/b24a9954-64a8-4820-960d-f98ed2695130" alt="Image" />
</p>



- نخست سرور ایران را کانفیگ میکنیم
- اگر خطای GIT CLONE در نصب پیش نیاز ها گرفتید، دوباره تلاش کنید
- من دو سرور خارج داشتم پس عدد 2 را وارد میکنم.
- پورت تانل را 443 قرار میدهم.
- پورت سرور من 50820 است . پورت وایرگاردم میباشد.
- پس از آن، کلیدی برای سرور خارج GENERATE میشود. باید از این کلید در سرور خارج استفاده کنید.
- ریست تایمر را هم هر 2 ساعت انتخاب میکنم.
----------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج** 

**مسیر : WS UDP > IPV4 > KHAREJ **



 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/57e3935d-9a05-4713-a563-fa35e2102fd1" alt="Image" />
</p>

- سرور خارج را کانفیگ میکنیم.
- ایپی 4 سرور ایران را وارد میکنم.
- پورت تانل که 443 قرار داده بودم
- کلیدی که برای سرور خارج GENERATE شده بود را اینجا PASTE میکنم.
- پورت کانفیگ سرور  خارج 50820 بود پس اینگونه وارد میکنم : 50820
- ریست تایمر هم که عدد 2 را وارد کرده بودیم. ( باید ریست تایمر یکسان باشد که همه سرویس ها همزمان ریست شوند)


--------------------------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**تانل ریورس WS ایپی 6** [UDP]
-
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : WS UDP > IPV6 > IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/df6c8c3f-260c-49c8-a713-446f1dd2d4fb" alt="Image" />
</p>



- نخست سرور ایران را کانفیگ میکنیم
- اگر خطای GIT CLONE در نصب پیش نیاز ها گرفتید، دوباره تلاش کنید
- من دو سرور خارج داشتم پس عدد 2 را وارد میکنم.
- پورت تانل را 443 قرار میدهم.
- پورت سرور من 50820 است . پورت وایرگاردم میباشد.
- پس از آن، کلیدی برای سرور خارج GENERATE میشود. باید از این کلید در سرور خارج استفاده کنید.
- ریست تایمر را هم هر 2 ساعت انتخاب میکنم.
----------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج** 

**مسیر : WS UDP > IPV6 > KHAREJ **



 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/ca407e5a-cbb1-46d4-8afc-2a07c3826b6b" alt="Image" />
</p>

- سرور خارج را کانفیگ میکنیم.
- ایپی 6 سرور ایران را وارد میکنم.
- پورت تانل که 443 قرار داده بودم
- کلیدی که برای سرور خارج GENERATE شده بود را اینجا PASTE میکنم.
- پورت کانفیگ سرور  خارج 50820 بود پس اینگونه وارد میکنم : 50820
- ریست تایمر هم که عدد 2 را وارد کرده بودیم. ( باید ریست تایمر یکسان باشد که همه سرویس ها همزمان ریست شوند)

----------------------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**تانل ریورس TLS با ساب دامین** [TCP]
-
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : WSS TCP > IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/8ac6c5df-27fc-458c-b9e8-c83e5a3d84ad" alt="Image" />
</p>



- نخست سرور ایران را کانفیگ میکنیم
- اگر خطای GIT CLONE در نصب پیش نیاز ها گرفتید، دوباره تلاش کنید
- من قبلا CERT برای ساب دامین ام نگرفتم، پس گزینه NO رو میزنم که ACME نصب بشود.
- ایمیل ادرسمان را وارد میکنیم و سپس ساب دامین را وارد میکنیم که CERT برایش گرفته شود.
- من پشت ساب دامین از ایپی 4 استفاده کردم. شما میتوانید با ایپی 6 NATIVE هم تست نمایید.
 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/0b5f950a-151c-425f-9692-eb57316481a9" alt="Image" />
</p>
- من دو سرور خارج داشتم پس عدد 2 را وارد میکنم.
- پورت تانل باید 443 باشد.(توجه کنید)
- نام ساب دامین تان را وارد نمایید. ساب دامینی که برایش CERT گرفتید.
- پورت های سرور اول خارج من 8080 و 8081 میباشد.
- پس از آن، کلیدی برای سرور اول خارج GENERATE میشود. باید از این کلید در سرور اول خارج استفاده کنید.
- پورت های سرور دوم خارج من 8082 و 8083 میباشد.
- پس از آن، کلیدی برای سرور دوم خارج GENERATE میشود. باید از این کلید در سرور دوم خارج استفاده کنید.
- ریست تایمر را هم هر 2 ساعت انتخاب میکنم.
----------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج اول** 

**مسیر : WSS TCP > KHAREJ 1**



 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/b02bbfa5-f89d-4ecf-b7ac-5e63e8e7aa68" alt="Image" />
</p>

- سرور اول خارج را کانفیگ میکنم.
- نام ساب دامینی که برایش CERT گرفتم را وارد میکنم.
- پورت تانل نیازی نیست
- کلیدی که برای سرور اول خارج، GENERATE شده بود را اینجا PASTE میکنم.
- تعداد کانفیگ من 2 عدد میباشد پس عدد 2 را وارد میکنم.
- پورت کانفیگ سرور اول خارج، 8080 و 8081 بود. در اینجا پورت ها را جداگانه وارد میکنیم.
- ریست تایمر هم که عدد 2 را وارد کرده بودیم. ( باید ریست تایمر یکسان باشد که همه سرویس ها همزمان ریست شوند)

--------------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج دوم** 

**مسیر : WSS TCP > KHAREJ 2**


 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/a4049114-bb2c-445e-a249-21a649efe17a" alt="Image" />
</p>

- سرور دوم خارج را کانفیگ میکنم.
- نام ساب دامینی که برایش CERT گرفتم را وارد میکنم.
- پورت تانل نیازی نیست
- کلیدی که برای سرور دوم خارج، GENERATE شده بود را اینجا PASTE میکنم.
- تعداد کانفیگ من 2 عدد میباشد پس عدد 2 را وارد میکنم.
- پورت کانفیگ سرور دوم خارج، 8082 و 8083 بود. در اینجا پورت ها را جداگانه وارد میکنیم.
- ریست تایمر هم که عدد 2 را وارد کرده بودیم. ( باید ریست تایمر یکسان باشد که همه سرویس ها همزمان ریست شوند)

--------------------------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**تانل ریورس TLS با ساب دامین** [UDP]
-
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : WSS UDP > IRAN**


 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/e2edc4b4-ba7b-4576-864a-b28fa0268686" alt="Image" />
</p>


- نخست سرور ایران را کانفیگ میکنیم
- اگر خطای GIT CLONE در نصب پیش نیاز ها گرفتید، دوباره تلاش کنید
- من قبلا CERT برای ساب دامین ام گرفتم، پس گزینه Y رو میزنم که SKIP بشود.
- من یک سرور خارج دارم پس عدد 1 را وارد میکنم.
- پورت تانل باید 443 باشد.(توجه کنید)
- نام ساب دامین تان را وارد نمایید. ساب دامینی که برایش CERT گرفتید.
- پورت سرور خارج من 50824 میباشد. پورت وایرگاردم میباشد.
- پس از آن، کلیدی برای سرور خارج GENERATE میشود. باید از این کلید در سرور خارج استفاده کنید.
- ریست تایمر را هم هر 2 ساعت انتخاب میکنم.
----------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج** 

**مسیر : WSS UDP > KHAREJ 1**



 <p align="right">
  <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/8c78c360-e6b6-47d1-a116-abe6d287c342" alt="Image" />
</p>

- سرور خارج را کانفیگ میکنم.
- نام ساب دامینی که برایش CERT گرفتم را وارد میکنم.
- پورت تانل نیازی نیست
- کلیدی که برای سرور خارج، GENERATE شده بود را اینجا PASTE میکنم.
- تعداد کانفیگ من 1 عدد میباشد پس عدد 1 را وارد میکنم.
- پورت کانفیگ سرور خارج، 50820 بود.
- ریست تایمر هم که عدد 2 را وارد کرده بودیم. ( باید ریست تایمر یکسان باشد که همه سرویس ها همزمان ریست شوند)

--------------------------------------

**اسکرین شات**


<details>
  <summary align="right">Click to reveal image</summary>
  
  <p align="right">
    <img src="https://github.com/Azumi67/Reverse_tls/assets/119934376/51e4bfe2-ba58-42b3-91c9-4ca1237f86a1" alt="menu screen" />
  </p>
</details>


------------------------------------------
![scri](https://github.com/Azumi67/FRP-V2ray-Loadbalance/assets/119934376/cbfb72ac-eff1-46df-b5e5-a3930a4a6651)
**اسکریپت های کارآمد :**
-
- این اسکریپت ها optional میباشد.


 
 Opiran Scripts
 
```
 bash <(curl -s https://raw.githubusercontent.com/opiran-club/pf-tun/main/pf-tun.sh --ipv4)
```

```
apt install curl -y && bash <(curl -s https://raw.githubusercontent.com/opiran-club/VPS-Optimizer/main/optimizer.sh --ipv4)
```

Hawshemi script

```
wget "https://raw.githubusercontent.com/hawshemi/Linux-Optimizer/main/linux-optimizer.sh" -O linux-optimizer.sh && chmod +x linux-optimizer.sh && bash linux-optimizer.sh
```

-----------------------------------------------------
![R (a2)](https://github.com/Azumi67/PrivateIP-Tunnel/assets/119934376/716fd45e-635c-4796-b8cf-856024e5b2b2)
**اسکریپت من**
----------------

```

```
---------------------------------------------
![R23 (1)](https://github.com/Azumi67/FRP-V2ray-Loadbalance/assets/119934376/18d12405-d354-48ac-9084-fff98d61d91c)
**سورس ها**




![R (9)](https://github.com/Azumi67/FRP-V2ray-Loadbalance/assets/119934376/33388f7b-f1ab-4847-9e9b-e8b39d75deaa) [سورس  OPIRAN](https://github.com/opiran-club)

![R (9)](https://github.com/Azumi67/6TO4-GRE-IPIP-SIT/assets/119934376/4758a7da-ab54-4a0a-a5a6-5f895092f527)[سورس  Hwashemi](https://github.com/hawshemi/Linux-Optimizer)



-----------------------------------------------------

![youtube-131994968075841675](https://github.com/Azumi67/FRP-V2ray-Loadbalance/assets/119934376/24202a92-aff2-4079-a6c2-9db14cd0ecd1)
**ویدیوی آموزش**

-----------------------------------------
