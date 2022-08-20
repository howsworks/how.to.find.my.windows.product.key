# How to find my windows product key 



[![how to find my windows product key ](red2.png)](https://github.com/howsworks/how.to.find.my.windows.product.key)


We teaches you how to find a Windows activation key on your computer using your computer's PowerShell application, or by using a third-party app called ProduKey. If, however, you received Windows 10 as a free upgrade from 8 or 7, you will not find a license key. These methods will only work if you purchased a license in either physical or digital form from Microsoft or if the computer you purchased came with the OS installed


## Using PowerShell


1. Open PowerShell as an administrator. You can do this by pressing the Windows key and the S key at the same time to open the search function. Then, type "PowerShell" and right-click the app from the list of results and click Run as Administrator.


2. Enter the following code: powershell "(Get-WmiObject -query 'select * from SoftwareLicensingService').OA3xOriginalProductKey and press Enter. This code will search your computer for the Microsoft OS license key.

3. Note your product key. You should see the product key appear directly below the command that you entered; this is your product key.

	* The product key will be 25 characters long.
	* Take a screenshot of the results or write down the key to make sure that you have access to it if needed.
	* If this command doesn't work, you'll need to use ProduKey to find your Windows product key.


## Using ProduKey


1. Open the ProduKey website. Go to http://www.nirsoft.net/utils/product_cd_key_viewer.html on a computer. ProduKey is highly rated and a very popular solution for people if the PowerShell method does not work. It works for Windows 10/8/7 and Vista and finds keys for both manually purchased and computer-embedded licenses.

	* On some computers, downloading and running ProduKey will result in a virus warning. This is because ProduKey is able to access your product key, not because it is malicious—as long as you download ProduKey from the official website, you can ignore the virus warning.

2. Scroll down and click Download ProduKey (In Zip file). It's near the bottom of the page. Doing so will prompt the ProduKey setup folder to download onto your computer.


3. Open the ProduKey folder. Double-click the ProduKey ZIP folder in your computer's default downloads folder (e.g., the desktop).

4. Click Extract all. You'll see this option under the Compressed Folder Tools tab and clicking it prompts a window to pop up.

5. Click Extract after you've picked an extract location. You can click Browse to select a new location for the file save, if you'd like, but the default save location is usually ok. You'll see the Extract at the bottom of the window. Doing so will decompress the ProduKey folder and open it for you.

6. Double-click the ProduKey application. It resembles a key. The ProduKey window will open; you should see your computer's 25-character product key to the right of the hard drive's name.
You can take a screenshot of the key or write it down to make sure you have access to it later.
