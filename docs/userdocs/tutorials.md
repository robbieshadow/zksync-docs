# آموزش ها

## اضافه کردن وجوه به zkSync با MetaMask

در این آموزش، ما با MetaMask به کیف پول zkSync واریز خواهیم کرد.                                                             &#x20;

> در حالی که آموزش تصاویر MetaMask را برای Rinkeby نشان می دهد، می توانید همان مراحل را برای mainnet دنبال کنید.                                                                                                                                            &#x20;

برای اولین تراکنش پس از واریز، هزینه فعال سازی حساب اعمال می شود. 20 دلار اضافی برای پوشش دادن آن در هنگام هزینه های بالای گاز واریز کنید. در سؤالات متداول ما درباره هزینه فعال سازی حساب بیشتر بیاموزید.        \
\


برای اتصال کیف پول خود به شبکه اصلی zkSync 1.0 دکمه "Ethereum Mainnet" را در بالای MetaMask انتخاب کنید.                                                                                                                                                  &#x20;

<figure><img src="https://docs.zksync.io/D1.png" alt=""><figcaption></figcaption></figure>

&#x20;        &#x20;

1. به https://wallet.zksync.io/ بروید و کیف پول خود را وصل کنید.

* برای اتصال به شبکه اصلی zkSync 1.0:
  * روی نماد اتریوم در پایین سمت راست کلیک کنید.
  * Mainnet را انتخاب کنید.

<figure><img src="https://docs.zksync.io/D00.png" alt=""><figcaption></figcaption></figure>

\


<figure><img src="https://docs.zksync.io/mainnet_goerli_selection.png" alt=""><figcaption></figcaption></figure>

\


![Mainnet.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/Mainnet.png)\


1. topup را انتخاب کنید

\


<figure><img src="https://docs.zksync.io/D2.png" alt=""><figcaption></figcaption></figure>

\


> می‌توانید روش‌های مختلفی را برای افزودن وجه به کیف پول zkSync خود انتخاب کنید، از جمله FIAT onramps، Exchanges، یا Bridges (برای این آموزش از پل zkSync استفاده خواهیم کرد)                                         &#x20;

\


<figure><img src="https://docs.zksync.io/Top-up.png" alt=""><figcaption></figcaption></figure>

\


1. توکن خود را انتخاب کنید، مبلغ را وارد کنید و روی «پر کردن» کلیک کنید

* اگر نمی توانید رمز خود را پیدا کنید:
  * برخی از نشانه ها به جای نماد توکن با شماره شناسه داخلی آنها در صفحه توکن های ما ارجاع داده می شوند. (به عنوان مثال ERC20-23 = UNI).
  * اضافه کردن توکن جدید به zkSync:
    1. روی «نمی‌توانید نشانه‌ای را پیدا کنید؟» کلیک کنید.
    2. برای دسترسی به صفحه Tokens از لینک استفاده کنید.
    3. روی «Add New Token» در گوشه سمت راست بالا کلیک کنید و دستورالعمل‌ها را دنبال کنید.

\


<figure><img src="https://docs.zksync.io/D3.png" alt=""><figcaption></figcaption></figure>

\


> اگر توکنی را اضافه کنید که نیاز به تأیید دارد، باید برای مجاز کردن سپرده گذاری به zkSync، هزینه گاز اتریوم را پرداخت کنید. قبل از رفتن به مرحله 4، پیام های زیر را مشاهده خواهید کرد                                                   .\
>



\


<figure><img src="https://docs.zksync.io/ERC20-approval.png" alt=""><figcaption></figcaption></figure>

1. اطلاعات تراکنش را بررسی کرده و تایید کنید.\


<figure><img src="https://docs.zksync.io/D5.png" alt=""><figcaption></figcaption></figure>

\


1. این یک تراکنش L1 است (از آنجایی که وجوه را از L1 به L2 واریز می کنید)، و بنابراین زمان نمایش آن در یک بلوک به کارمزدی که تعیین می کنید بستگی دارد.
2. وجوه شما تنها پس از پردازش تراکنش در L1 در L2 ظاهر می شود (اگر مشکلی دارید، لطفاً Etherscan را بررسی کنید (پنجره جدید باز می شود) تا تراکنش را نظارت کنید)



<figure><img src="https://docs.zksync.io/D6.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://docs.zksync.io/D7.png" alt=""><figcaption></figcaption></figure>

\
\


\


1. سپرده شما تکمیل شده است. تراکنش آغاز شده است، و وجوه شما در کیف پول zkSync شما در ده تاییدیه تراکنش L1 شما قابل مشاهده خواهد بود.                                                                                             &#x20;

| **Committed**                                                                                                                                          | **Verified**                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| <p>یک علامت تیک زرد رنگ در کنار موجودی شما نشان می دهد که سرور zkSync تراکنش شما را پردازش کرده است و وجوه شما برای استفاده فوری </p><p>آماده است.</p> | دو علامت تیک سبز نشان می دهد که اثبات بلوک حاوی تراکنش شما تولید شده و به قرارداد هوشمند در لایه 1 ارسال شده است. |

\


## فعال سازی حساب

اولین تراکنش شما پس از واریز یا تامین مالی حساب شما نیاز به اقدام جداگانه ای برای فعال سازی حساب دارد. برای اطلاعات بیشتر در مورد فعال سازی حساب، به پرسش های متداول فعال سازی حساب مراجعه کنید.                      &#x20;

1. از شما خواسته می شود "Authorize to Sign activation account" را انتخاب کنید و ابتدا باید پیام را امضا کنید تا کلید خصوصی zkSync L2 خود را ایجاد کنید.                                                                                             \


<figure><img src="https://docs.zksync.io/S2.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://docs.zksync.io/S3.png" alt=""><figcaption></figcaption></figure>

\


1. سپس از شما خواسته می شود که پیام را برای فعال سازی حساب امضا کنید (خواندن پیام هایی که امضا می کنید تمرین خوبی است).                                                                                                                                    \


\


<figure><img src="https://docs.zksync.io/S4.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://docs.zksync.io/S5.png" alt=""><figcaption></figcaption></figure>

> هنگام تکمیل تراکنش، هزینه فعال سازی حساب را می توانید در زیر کارمزد تراکنش مشاهده کنید
>
> * برای کسب اطلاعات بیشتر در مورد هزینه فعال سازی حساب، سؤالات متداول فعال سازی حساب ما را بررسی کنید                                                                                                                                               \
>   \>\
>



<figure><img src="https://docs.zksync.io/Activation-fee.png" alt=""><figcaption></figcaption></figure>

\


## انتقال وجه در zkSync

در این آموزش، نحوه انتقال وجه به حساب zkSync دیگر را بررسی خواهیم کرد. چه یک کاربر اتریوم دارای حساب zkSync باشد یا خیر، می توانید وجوه خود را در zkSync به همان آدرسی که در اتریوم دارند ارسال کنید.    &#x20;

به خاطر داشته باشید که این وجوه در لایه 2 (L2) خواهد بود، بنابراین اگر می خواهید از این وجوه در لایه 1 (L1) استفاده کنید، به اتریوم ارسال می کنید.                                                                                                      &#x20;

1. روی "انتقال" کلیک کنید\


<figure><img src="https://docs.zksync.io/S1.png" alt=""><figcaption></figcaption></figure>

"Transfer to zkSync" را انتخاب کنید

<figure><img src="https://docs.zksync.io/S1-2.png" alt=""><figcaption></figcaption></figure>

\


> اگر این اولین تراکنش شما پس از واریز یا تامین مالی حساب zkSync است، به بخش فعال سازی حساب مراجعه کنید.

> اگر صفحه را بازخوانی کرده اید یا اخیرا کیف پول خود را به zkSync متصل کرده اید، از شما خواسته می شود "مجوز ارسال در zkSync" را انتخاب کنید. \
>

\


<figure><img src="https://docs.zksync.io/authorize-to-send-zksync.png" alt=""><figcaption></figcaption></figure>

\


1. آدرسی را برای ارسال وجه وارد کنید، رمز انتقال را انتخاب کنید و مبلغ را وارد کنید
2. قبل از انجام معامله، می توانید رمز کارمزد را تغییر دهید. کاربران می‌توانند کارمزد تراکنش‌ها را در تمام توکن‌های محبوب بپردازند، زیرا zkSync از «متا تراکنش‌های بدون گاز» پشتیبانی می‌کند.

<figure><img src="https://docs.zksync.io/S8.1.png" alt=""><figcaption></figcaption></figure>

با امضای این پیام، تراکنش به شبکه zkSync ارسال می شود (به یاد داشته باشید، خواندن پیام هایی که امضا می کنید تمرین خوبی است)\


<figure><img src="https://docs.zksync.io/S7.png" alt=""><figcaption></figcaption></figure>

\


1. انتقال نباید بیش از چند ثانیه طول بکشد (اگر مشکلی دارید، لطفاً zkScan را بررسی کنید (پنجره جدید باز می شود) تا تراکنش را نظارت کنید)

<figure><img src="https://docs.zksync.io/S9.png" alt=""><figcaption></figcaption></figure>



1. انتقال شما کامل شد! معامله آغاز شده است و وجوه برای استفاده فوری آماده است

| **Committed**                                                                                                                            | **Verified**                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| یک علامت تیک زرد رنگ در کنار موجودی شما نشان می دهد که سرور zkSync تراکنش شما را پردازش کرده است و وجوه شما برای استفاده فوری آماده است. | دو علامت تیک سبز نشان می دهد که اثبات بلوک حاوی تراکنش شما تولید شده و به قرارداد هوشمند در لایه 1 ارسال شده است. |

\


## انتقال وجه به اتریوم

این آموزش روند برداشت وجه از zkSync به زنجیره اصلی اتریوم را پوشش می دهد.                                              \


انتقال وجوه به صرافی: اگر می خواهید وجوه خود را از zkSync به صرافی منتقل کنید، این مراحل روش صحیح را دنبال می کنند. از طرف دیگر، می‌توانید ریسک کنید و هنگام برداشت، آدرس صرافی را وارد کنید، اما اکثر صرافی‌ها نقل و انتقالات قرارداد هوشمند را رعایت نمی‌کنند، که ممکن است از شما بخواهد با پشتیبانی مشتری آنها تماس بگیرید تا وجوه خود را در صرافی ببینید.                                                                                                     &#x20;

1. روی "انتقال" کلیک کنید\


<figure><img src="https://docs.zksync.io/se1.png" alt=""><figcaption></figcaption></figure>

\


1. روی "انتقال به اتریوم" کلیک کنید\


<figure><img src="https://docs.zksync.io/SE1-2.png" alt=""><figcaption></figcaption></figure>

\


1. آدرس شما به طور خودکار با آدرس شما پر می شود اگر آدرس دیگری را برای برداشت وارد می‌کنید، لطفاً بررسی کنید که انتقال قرارداد هوشمند را می‌پذیرد                                                                                                &#x20;

<figure><img src="https://docs.zksync.io/se.png" alt=""><figcaption></figcaption></figure>



\


> اگر این اولین تراکنش شما پس از واریز یا تامین مالی حساب zkSync است، به بخش فعال سازی حساب مراجعه کنید.                                                                                                                                              &#x20;

> اگر صفحه را بازخوانی کرده اید یا اخیرا کیف پول خود را به zkSync متصل کرده اید، از شما خواسته می شود "مجوز ارسال در zkSync" را انتخاب کنید.                                                                                                \
> \
>

<figure><img src="https://docs.zksync.io/authorize-to-send-zksync.png" alt=""><figcaption></figcaption></figure>

توکن ارسالی به اتریوم را انتخاب کرده و مبلغ را وارد کنید

قبل از انجام معامله، می توانید رمز کارمزد را تغییر دهید کاربران می‌توانند کارمزد تراکنش‌ها را در تمام توکن‌های محبوب بپردازند، زیرا zkSync از «متا تراکنش‌های بدون گاز» پشتیبانی می‌کند.                                          &#x20;

<figure><img src="https://docs.zksync.io/se4.png" alt=""><figcaption><p><br></p></figcaption></figure>

برای جلوگیری از هدر رفتن وجوه، پنجره بازشو را با دقت بخوانید                                                                           &#x20;

<figure><img src="https://docs.zksync.io/SE-Popup.png" alt=""><figcaption></figcaption></figure>

مبلغ برداشت، آدرس، هزینه، و پیام را امضا کنید (به یاد داشته باشید، خواندن پیام هایی که امضا می کنید تمرین خوبی است)                                                                                                                                             &#x20;

<figure><img src="https://docs.zksync.io/se6.png" alt=""><figcaption></figcaption></figure>

1. برداشت شما آغاز شده است. تغییری فوری در موجودی حساب شما در zkSync ایجاد خواهد شد، اما زمان برداشت ممکن است از 10 دقیقه تا 7 ساعت طول بکشد تا در L1 در دسترس باشد.                               &#x20;

* وقتی فعالیت شبکه افزایش می‌یابد، بلوک‌ها سریع‌تر پر می‌شوند و زمان برداشت کاهش می‌یابد            &#x20;

| **Committed**                                                                                                                                                                                  | **Verified**                                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| یک علامت تیک زرد رنگ در کنار موجودی شما نشان می دهد که سرور zkSync تراکنش شما را پردازش کرده است و وجوه شما برای استفاده فوری آماده است.                                                       | دو علامت تیک سبز نشان می دهد که اثبات بلوک حاوی تراکنش شما تولید شده و به قرارداد هوشمند در لایه 1 ارسال شده است.                                   |

\


## ضرب یک NFT

مراحل زیر استفاده از دسکتاپ IPFS برای برش NFT را پوشش می دهد.                                                              &#x20;

> اگر در ساخت NFT تازه کار هستید، از یکی از فرانتاندهای ایجاد شده توسط انجمن\* مانند Open Sky استفاده کنید (پنجره جدید باز می شود).                                                                                                                           \
>

فرانت‌اندهای ایجاد شده توسط انجمن توسط تیم zkSync ایجاد نمی‌شوند و هر مشکلی در مورد Minting باید برای سازندگان این فرانت‌اندها ارسال شود.                                                                                                            &#x20;

1. از IPFS.io بازدید کنید (پنجره جدید باز می شود) و IPFS Desktop را نصب کنید\


<figure><img src="https://docs.zksync.io/m1.png" alt=""><figcaption></figcaption></figure>

\


1. Go to "Files", select "+ Import", and choose your image.\


![m2.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/m2.png)

\


1. Click on the three dots at the end of the row of your imported image and click on "Copy CID" (Content Identifier).\


![m3.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/m3.png)

\


1. Use the text below to create a metadata.json file or click the link to [create your file online](https://codebeautify.org/online-json-editor/cb3f2098).

```json
{
  "name": "Your NFT name",
  "image": "https://ipfs.io/ipfs/CID of Image",
  "description": "Description of your NFT",
  "external_url": "Optional URL",
  "attributes": [
    {
      "trait_type": "Attribute 1",
      "value": "Value 1"
    },
    {
      "trait_type": "Attribute 2",
      "value": "Value 2"
    },
    {
      "trait_type": "Attribute 3",
      "value": "Value 3"
    }
  ]
}
```

1.  Enter the CID from step 3 at the end of the `"image": "https://ipfs.io/ipfs/` section and fill out the rest of the values as needed.

    > Example metadata.json file:

```json
{
  "name": "zkSync",
  "image": "https://ipfs.io/ipfs/QmX4kiKSy4bBB8PXqj8ZM8gNNmra3Xh1NshiaF5TRk5c2C",
  "description": "zkSync Logo",
  "external_url": "https://zksync.io/",
  "attributes": [
    {
      "trait_type": "Logo",
      "value": "Yes"
    },
    {
      "trait_type": "Color",
      "value": "Yes"
    }
  ]
}
```

1. Save your .json file or download your .json file if you used the link from step 4.\


![json.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/json.png)

\


1. Import your .json file to IPFS as in step 2 and copy the CID for your .json file.
2. On your [zkSync wallet](https://wallet.zksync.io/), open the NFTs tab and select "+ Mint NFT."\


![m4.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/m4.png)

\


> **If this is your first transaction after depositing or funding your zkSync account, see the** [**Account Activation**](tutorials.md#account-activation) **section.**

> **If you refreshed the page or recently connected your wallet to zkSync, you will be asked to "Authorize to Mint NFT."**
>
> * Signing the message will generate your zkSync Layer 2 private key (remember, it is good practice to read the messages you sign).\
>

1. Enter the copied CID of your .json file in "Content Address" and click "Mint NFT."

* _Before minting, you can change the fee token._\
  Users can pay transaction fees in all popular tokens since zkSync supports “gasless meta-transactions.”\


![m7.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/m7.png)

\


1. Confirm the fee and sign the message (remember, it is good practice to read the messages you sign).\


![m8.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/m8.png)

\


1. Minting your NFT has been initiated and will be available for transfer, or withdrawal to L1, once it has been verified, which takes between 10 minutes to 7 hours.

* _When network activity increases, blocks fill up faster, and verification times decrease._

| **Committed**                                                                                               | **Verified**                                                                                                                                       |
| ----------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| A single yellow check mark next to your balance indicates the zkSync server has processed your transaction. | Two green check marks signal the proof for the block containing your transaction has been produced and submitted to the smart contract on Layer 1. |
| ![m10.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/m10.png)            | ![m11.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/m11.png)                                                   |
| <p><br></p>                                                                                                 |                                                                                                                                                    |

## Alternative Withdrawal

The Alternative Withdrawal tool is used when funds have been sent to an account that cannot connect to the [zkSync wallet](https://wallet.zksync.io/).

1. Check to see if your account qualifies to use the Alternative Withdrawal tool by entering your address on [zkScan](https://zkscan.io/).
2. Check your account for the following information:

*
  1. The account is at least 24 hours old.
*

    1. The account has never been activated (i.e., nonce is zero).\


    ![nonce.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/nonce.png)

    \


> **If your account meets the requirements for using the "Alternative Withdrawal" tool, proceed with the following steps.**

1. Go to [Alternative Withdrawal](https://withdraw.zksync.io/).

* _You can also access the “Alternative Withdrawal” tool on the_ [_zkSync.io_](http://zksync.io/) _webpage under "zkTools.”_\


![zktools.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/zktools.png)

\


1. Enter the zkSync address from steps 1 and 2.\


![a1.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/a1.png)

\


1. Select the token you want to be withdrawn and the method for paying the fee.\


![a3.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/a3.png)

\


1. Complete the fee payment process on your wallet.\


![a4.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/a4.png)

\


1. The funds should be in your wallet within 24 hours and can be see under "Internal Txns" on [Etherscan](https://etherscan.io/).

* If you do not see your funds within 24 hours, please email us at withdraw@zksync.io with the following information:
  *
    1. Your zkSync address from step 1.
  *
    1. The token and the amount.
  *

      1. The Ethereum transaction hash of the fee payment.\


      ![int-txns.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/int-txns.png)

      \
