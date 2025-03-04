# General Errors

* [**How to Fix the ‘You’ll need a new app to open this ms-gaming overlay’ Error on Windows 10?**](general-errors.md#how-to-fix-the-youll-need-a-new-app-to-open-this-ms-gaming-overlay-error-on-windows-10)
* [**Error 'Application is already running'**](general-errors.md#error-application-is-already-running)
* [**An error occurred during platform initialization: Exception has been thrown by the target of an invocation**](general-errors.md#an-error-occurred-during-platform-initialization-exception-has-been-thrown-by-the-target-of-an-invoc)
* [**An error occurred during platform initialization: Object reference not set to an instance of an object**](general-errors.md#an-error-occurred-during-platform-initialization-object-reference-not-set-to-an-instance-of-an-objec)
* [**An error occurred during platform initialization: Fail to load DLL signatures**](general-errors.md#an-error-occurred-during-platform-initialization-fail-to-load-dll-signatures)
* [**Trendlines are moving on tick charts. How to resolve it?**](general-errors.md#trendlines-are-moving-on-tick-charts.-how-to-resolve-it)
* [**Incorrect view of icons inside the application (for Mac via Parallels)**](general-errors.md#incorrect-view-of-icons-inside-the-application-for-mac-via-parallels)
* [**How to replace the main Toolbar to another screen (monitor)?**](general-errors.md#how-to-replace-the-main-toolbar-to-another-screen-monitor)
* [**Data latency (xxx ms) on Chart, DOM Trader**](general-errors.md#data-latency-xxx-ms-on-chart-dom-trader)
* [**After launching the platform, windows are not displaying or are completely darkened**](general-errors.md#after-launching-the-platform-windows-are-not-displaying-or-are-completely-darkened)

***

## How to Fix the ‘You’ll need a new app to open this ms-gaming overlay’ Error on Windows 10?

<figure><img src="../.gitbook/assets/error1.jpg" alt=""><figcaption></figcaption></figure>

The easiest method is to start troubleshooting by simply **disabling Game Bar**. This could be helpful to remove the key combination and use it for other purposes.&#x20;Now, you can take these steps:

* Press the **Win + I** combination key to open Windows Settings
* Go to **Gaming > Gaming bar**.
* Switch the toggle of **Xbox Game Bar for things like recording game clips, screenshots, and broadcasts using the Game Bar** to **Off**. Next, press **Win + G** to see if the error is solved.

<figure><img src="../.gitbook/assets/image (135).png" alt=""><figcaption></figcaption></figure>

More details you can find here [https://www.minitool.com/news/ms-gaming-overlay-popup.html](https://www.minitool.com/news/ms-gaming-overlay-popup.html)

## Error 'Application is already running'

<figure><img src="../.gitbook/assets/image (136).png" alt=""><figcaption></figcaption></figure>

* This message is displayed if you try running multiple 3rd Dimension in parallel on the same computer or you have closed 3rd Dimension a few seconds ago and it did not finish closing yet. In 20 seconds or sooner 3rd Dimension can be started again.
* If even after a few minutes the platform fails to start, go to the **Task Manager**. Press **Ctrl+Shift+Esc** to open the Task Manager with a keyboard shortcut or right-click the Windows taskbar and select “Task Manager.”\
  Find the process with the name **"Starter"**, select it and click on **End task**.

<figure><img src="../.gitbook/assets/image (137).png" alt=""><figcaption></figcaption></figure>

***

## An error occurred during platform initialization: Exception has been thrown by the target of an invocation

This error occurs due to the <mark style="color:red;">**removal of the file**</mark> by the **Avast antivirus or AVG antivirus**, which is necessary for the correct work of the platform.&#x20;



<figure><img src="../.gitbook/assets/start.jpg" alt="" width="467"><figcaption></figcaption></figure>

Our developers informed Avast and AVG companies that the file CefSharp.BrowserSubprocess.exe is a part of the CefSharp library — HTML5, JavaScript and PDF supported Web browser based on Chromium Embedded Framework. It allows using web browsing services in applications to create the user interface. We use this library in our platform as well. More information about it can be read here [https://cefsharp.github.io](https://cefsharp.github.io)

We don't know a reason why antivirus sometimes recognizes this file as suspicious, but if you search in Google, you can see that there are already many reports from users about the same problem: [https://www.google.com/search?q=cefsharp.browsersubprocess.exe+antivirus](https://www.google.com/search?q=cefsharp.browsersubprocess.exe+antivirus) In general case antivirus developers recommend reporting a problem as false positive.

To be 100% sure, that this file is not dangerous, you can check it manually using different web services like [https://www.virustotal.com](https://www.virustotal.com) They will display your results received from different antiviruses.

\


<figure><img src="../.gitbook/assets/Screenshot_2 (3).png" alt=""><figcaption><p>CefSharp.BrowserSubprocess.exe is checked by all major antiviruses</p></figcaption></figure>

As a solution, we recommend you remove Avast or AVG antiviruses (completely) and reinstall the platform.

## An error occurred during platform initialization: Object reference not set to an instance of an object

<figure><img src="../.gitbook/assets/an error 3rd.jpg" alt="" width="467"><figcaption><p>3rd Dimension error "Object reference not set to an instance of an object"</p></figcaption></figure>

This error usually occurs when a user attempts to install the platform with a version not compatible with their PC's system type. For instance, installing a 64-bit version on a 32-bit system. It's important to check your PC's settings to determine the system type and download the corresponding version from the [3rd Dimension website.](https://thirddimension.exchange/)

Here is how you can check the system type: [https://support.microsoft.com/en-us/windows/32-bit-and-64-bit-windows-frequently-asked-questions-c6ca9541-8dce-4d48-0415-94a3faa2e13d](https://support.microsoft.com/en-us/windows/32-bit-and-64-bit-windows-frequently-asked-questions-c6ca9541-8dce-4d48-0415-94a3faa2e13d)

Once you have determined the type of your system, you can proceed to [**download the version**](https://thirddimension.exchange/) that corresponds to it.

<figure><img src="../.gitbook/assets/3rd website.png" alt=""><figcaption></figcaption></figure>

***

## An error occurred during platform initialization: Fail to load dll signatures

<figure><img src="../.gitbook/assets/error 3.jpg" alt="" width="467"><figcaption><p>3rd Dimension error "Fail to load dll signatures"</p></figcaption></figure>

This error can occur for several reasons:

* There is <mark style="color:red;">**no internet connection**</mark>**&#x20;or a weak connection**. Please check that the connection is stable with your browser.
* It appears that you are currently utilizing an <mark style="color:red;">**outdated version**</mark>**&#x20;of our platform that is no longer supported**. We strongly advise that you [**download the newest version**](https://thirddimension.exchange/) from our official website and [<mark style="color:green;">**transfer all of your settings**</mark>](../getting-started/reset-settings-to-default..md) from the old version to the updated one.
* The platform has **not fully installed the files** to work correctly. Please reinstall the platform.

<figure><img src="../.gitbook/assets/Screenshot_3 (2).png" alt=""><figcaption><p>Full list of folders and files for 3rd Dimension</p></figcaption></figure>

***

## Trendlines are moving on tick charts. How to resolve it?

Currently, there is an issue with the independent movement of drawings (trendlines, rectangles, etc.) on non-time-based chart types such as Tick, Range bars, Volume bars, and Renko.

To prevent changes in drawings, we recommend placing the endpoint of the drawing before the current (forming) bar. Additionally, we suggest enabling the '**Right Ray'** option in the settings of the respective drawing.

<figure><img src="../.gitbook/assets/221.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/2211.png" alt=""><figcaption></figcaption></figure>

***

## **Incorrect view of icons inside the application (for Mac via Parallels)**

Sometimes users may encounter the problem of incorrect display of icons of various functions inside the application. For example, the picture below is such a situation.

<figure><img src="../.gitbook/assets/mac icon error.png" alt=""><figcaption></figcaption></figure>

This situation occurs when using the Parallels emulator for Mac. To solve this problem, Parallel itself offers a solution at the link below [https://kb.parallels.com/112983](https://kb.parallels.com/112983)

> **Isolate Windows from Mac** to exclude Mac OS X influence. (**Virtual Machine > Configure… > Options > Security** > check on **Isolate Mac from Windows**)

***

## **How to replace the main Toolbar to another screen (monitor)?**

<figure><img src="../.gitbook/assets/3rd main tool bar.png" alt=""><figcaption><p>3rd Dimension Main toolbar</p></figcaption></figure>

There are two ways to move the main toolbar to another monitor:

* To move the main toolbar to another monitor, <mark style="background-color:orange;">**click and hold the mouse cursor on it and drag it to the desired monitor**</mark>. Make sure <mark style="background-color:blue;">**both monitors are aligned at the same level**</mark>, which you can verify in your monitor settings.

<figure><img src="../.gitbook/assets/image (46).png" alt=""><figcaption></figcaption></figure>

* click on the main toolbar and use the key combination <mark style="background-color:blue;">**Win + Shift + Arrow**</mark> <mark style="background-color:blue;"></mark><mark style="background-color:blue;">(left / right)</mark>.

***

## Data latency (xxx  ms) on Chart, DOM Trader

This message appears when there's a delay in data within a specific time interval. The cause may stem from a <mark style="color:red;">**slow Internet connection**</mark> or <mark style="color:red;">**issues on the data provider's end**</mark>.

Whether the data delay occurs on a Bybit server, Kucoin, Binance, or during transmission to the client, we make efforts to identify instances where server-side timestamps start to lag.

Additionally, you have the option to mitigate data load by closing panels, disabling volume tools, or closing unnecessary tabs in your browser (if it's active while using the platform).

<figure><img src="../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

***

## **After launching the platform, windows are not displaying or are completely darkened**

<figure><img src="../.gitbook/assets/dark.jpg" alt=""><figcaption><p>Platform doesn't work correctly</p></figcaption></figure>

1. **For Intel Processors:** Update your drivers at [**Intel Graphics Windows DCH Drivers**](https://www.intel.com/content/www/us/en/download/19344/intel-graphics-windows-dch-drivers.html).
2. **If the Issue Persists After Initial Driver Installation:** Sometimes, the driver may not install correctly on the first attempt. Please reinstall the driver.&#x20;

{% hint style="info" %}
There's no need to reboot your PC after the second installation.
{% endhint %}

3. **Restart the Platform:** Once the driver is successfully installed, restart the platform, and the issue should be resolved.

If the problem continues, please contact our support team via live chat on our website or on [Telegram ](https://t.me/ThirdDimensionSupport)
