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


1. Signing this message submits the transaction to the zkSync network. (remember, it is good practice to read the messages you sign).\


![S7.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/S7.png)

\


1. The transfer should take no longer than a couple of seconds. If you have any difficulties, please check [zkScan](https://zkscan.io/) to monitor the transaction.\


![S9.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/S9.png)

\


1. Your transfer is complete! The transaction has been initiated and the funds are ready for immediate use.

| **Committed**                                                                                                                                          | **Verified**                                                                                                                                       |
| ------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| A single yellow check mark next to your balance indicates the zkSync server has processed your transaction and your funds are ready for immediate use. | Two green check marks signal the proof for the block containing your transaction has been produced and submitted to the smart contract on Layer 1. |
| ![S10.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/S10.png)                                                       | ![S11.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/S11.png)                                                   |

\


## Send Funds to Ethereum

This tutorial will cover the process of withdrawing funds from zkSync back to the Ethereum main chain.\


**Moving funds to an exchange**: If you want to move your funds from zkSync to an exchange, these steps follow the **correct method**. _Alternatively, you can take a risk and enter the exchange address when you withdraw, but most exchanges do not observe smart contract transfers, which may require you to contact their customer support to see your funds on the exchange._

1. Go to "Send."\


![se1.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/se1.png)

\


1. Click on "Send to Ethereum (L1)."\


![se2.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/se2.png)

\


1. Your address will auto-populate with your address.\
   **If you enter a different address for withdrawal, please check that it accepts smart contract transfers.**\


![se.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/se.png)

\


> **If this is your first transaction after depositing or funding your zkSync account, see the** [**Account Activation**](tutorials.md#account-activation) **section.**

> **If you refreshed the page or recently connected your wallet to zkSync, you will be asked to "Authorize to Send to Ethereum."**
>
> * Signing the message will generate your zkSync Layer 2 (L2) private key (remember, it is good practice to read the messages you sign).\
>

1. Select the token to send to Ethereum and enter the amount.

* _Before transacting, you can change the fee token._\
  Users can pay transaction fees in all popular tokens since zkSync supports "gasless meta-transactions."\


![se4.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/se4.png)

\


> **Read the popup carefully to to prevent loss of funds.** >\
>

![se4.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/se4.png)

1. Confirm the withdrawal amount, address, fee, and sign the message (remember, it is good practice to read the messages you sign).\


![se6.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/se6.png)\


1. Your withdrawal has been initiated. There will be an immediate change in your account balance in zkSync, but **withdrawal times can take from 10 minutes to 7 hours before being available on L1.**

* _When network activity increases, blocks fill up faster, and withdrawal times decrease._

| **Committed**                                                                                                                                          | **Verified**                                                                                                                                       |
| ------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| A single yellow check mark next to your balance indicates the zkSync server has processed your transaction and your funds are ready for immediate use. | Two green check marks signal the proof for the block containing your transaction has been produced and submitted to the smart contract on Layer 1. |
| ![se8.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/se8.png)                                                       | ![se9.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/se9.png)                                                   |

\


## Mint an NFT

The following steps will cover using IPFS desktop to mint an NFT.

> If you are new to minting an NFT, consider using one of the community-created frontends\* like [zkNFT](https://zknft.xyz/#/) or [Open Sky](https://open-sky.vercel.app/).\
>

_\*The community-created frontends are not created by the zkSync team, and any issues with minting will need to be sent to the creators of these frontends._

1. Visit the [IPFS.io](https://ipfs.io/) and install IPFS Desktop.\


![m1.png](https://raw.githubusercontent.com/matter-labs/zksync-docs/master/docs/images/m1.png)

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
