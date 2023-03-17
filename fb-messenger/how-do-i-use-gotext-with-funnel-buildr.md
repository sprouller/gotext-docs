# How do I use GOtext with Funnel Buildr?

If you are using Funnel buildr and want to use Tobi messenger opt-in checkbox within your funnel pages, you will have to set up a few custom settings.

1\. Go to your GOtext app settings section and at the bottom of the page you will find your custom javascript in "My custom script" section.

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

Copy the code and put It inside \<script> tags. In our case It would be (**yours will be different**):

`<script type="text/javascript" src="me-c220584dc70346652215af303334abf8.js"></script>`

2\. Go to your Funner buildr app and choose a funnel you want to add messenger javascript to.

In settings menu select "Custom body script" menu element, paste your javascript code and hit "Save changes".

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

3\. Choose a place where you want the opt-in checkbox to be visible (we recommend under "Add to cart" button) and add our custom div there.

`<div class="tobi-checkbox"></div>`

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

Hit save and you're all ready to go!

If you need any help with setting up Tobi with Funnel Buildr, you can always message us using our customer chat.
