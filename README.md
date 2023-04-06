# The guide!
made by zxxxxo

<details>
    <summary>Microsoft Azure Application Part 1</summary>

## Azure App Registration Part 1

*Contrary to popular belief, this is actually very easy!*
First, make sure you have a Microsoft Account. If you don't, you can make one [here](https://account.microsoft.com/account).
Then, go ahead and sign up for Microsoft Azure. You can do that [here](https://azure.microsoft.com/en-us/free/).

Secondly, visit [Microsoft Azure&#39;s](https://portal.azure.com/#create/hub) website.

Next, at the search top bar, search for "App registrations"

Then, click "New registration" in the top left corner

Next, type any name you want. To make it believable, you can choose something like "Discord" or "Hypixel"

</details>

<details>
    <summary>Microsoft Azure Application Part 2</summary>

## Azure App Registration Part 2

Now, set the redirect uri to your onrender link or your vps if it applies to you. Then set the platform to web.

Reopen config.json and set the client_id to the Application (client) ID on the Azure page.

Then, back on Azure, click "Add a certificate or secret" under Client credentials.

Click "New client secret", the name can be anything you want. It doesn't matter.

Then, click add and copy the Secret ID and set that to client_secret in the config.

Set the redirect uri you put to the azure as redirect_uri in config

[https://login.live.com/oauth20_authorize.srf?client_id=`clientidhere`&amp;response_type=code&amp;redirect_uri=`redirecturlhere`&amp;scope=XboxLive.signin+offline_access&amp;state=](https://login.live.com/oauth20_authorize.srf?client_id=`clientidhere`&response_type=code&redirect_uri=`redirecturlhere`&scope=XboxLive.signin+offline_access&state=)

</details>

