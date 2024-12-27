<img src="https://github.com/user-attachments/assets/aff4f9ff-11c4-4fda-919b-723545225749" width="50"> << me <p>shuv here, i dont maintain this project anymore, if you wish to fix an issue you noticed, create a pull request, thx</p>

**if something doesn't work DO NOT PM ME for god's sake I will 100% ignore you both in the server and my pms regardless of issue**

# ** DO NOT PING ME FOR ANY ISSUE I COULDN'T CARE LESS ABOUT YOUR ISSUES **

# Groq & Usage with CreatureChat
Learn how to set up **Groq** with **CreatureChat** to use it and play for free.

**Requirements:**
  * Google Account
  * 1 braincell

"what do i do when i don't have 1 braincell??" stfu

## 1. Setting up Groq & Logging in
Head over to **[Groq](https://groq.com/)** and log in with your Google account. (see image below)
![logging in](https://i.ibb.co/bJYVZWC/image.png)
After logging in, you can start creating your **API Key**, which will power the AI used for the mod.

## 2. Creating API Key
Navigate to the **[GroqCloud API Key Dashboard](https://console.groq.com/keys)** to create a key.
Click on the **Create API Key** button. In the popup, name your key (e.g., "CreatureChat") and Create it. (follow the screenshots below)
> [!IMPORTANT]
> Copy your key and keep it somewhere safe until the last step!

> [!WARNING]
> **DO NOT SHARE THIS KEY TO ANYBODY.** If you really have to, only send the key partially if they are not meant to use it, only to view.

![creating the api key](https://i.ibb.co/cxcmFFr/im1ge.png)
![popup box](https://i.ibb.co/nCRFq0j/image.png)
![copying api key](https://i.ibb.co/CJNK4vY/image-2.png)

Congratulations, you've completed the hardest part.
Your dashboard should now look like this:
![key dashboard](https://i.ibb.co/7XV1D2P/1image.png)

I've already made some keys for other purposes, but as you can see, there's the **CreatureChat** key we just created. Its creation date should be today's date, and the "Last Used" status should be "Never".

## Minecraft Setup
To install the mod, **[follow this official guide by the creators on YouTube](https://youtu.be/P2txUop_kSM?si=6Swz90w7P3pmPSlm)**.

### 3. Setting up the mod
In any of your singleplayer worlds or on multiplayer, enter these commands:

`/creaturechat model set llama3-8b-8192` - This sets up the model you want to use.

`/creaturechat url set "https://api.groq.com/openai/v1/chat/completions"` - This is the Groq API endpoint; do not modify this.

> [!NOTE]
> Do not visit the URL in the second command; it's an API endpoint and is not meant to be accessed directly.

We've now set the model for the AI.

> [!TIP]
> You can use a different model if you'd like! Here is a list of all possible models you can switch to; Use the `/creaturechat model set` command and replace "llama3-8b-8192" with one of these:
> 
> <table>
>   <tr>
>     <th>Provider</th>
>     <th>Model Name</th>
>   </tr>
>   <tr>
>     <td rowspan="2">Google</td>
>     <td>gemma2-9b-it</td>
>   </tr>
>   <tr>
>     <td>gemma-7b-it</td>
>   </tr>
>   <tr>
>     <td rowspan="5">Meta</td>
>     <td>llama-3.1-70b-versatile</td>
>   </tr>
>   <tr>
>     <td>llama-3.1-8b-instant</td>
>   </tr>
>   <tr>
>     <td>llama3-70b-8192</td>
>   </tr>
>   <tr>
>     <td>llama3-8b-8192</td>
>   </tr>
>   <tr>
>     <td>llama-guard-3-8b</td>
>   </tr>
>   <tr>
>     <td rowspan="2">Groq</td>
>     <td>llama3-groq-70b-8192-tool-use-preview</td>
>   </tr>
>   <tr>
>     <td>llama3-groq-8b-8192-tool-use-preview</td>
>   </tr>
>   <tr>
>     <td>Mistral AI</td>
>     <td>mixtral-8x7b-32768</td>
>   </tr>
> </table>



### Final Steps
Enter this command in Minecraft chat:

`/creaturechat key set <your copied key>` - This sets up the API key for use.

Confused? Use the key from step 2 that you saved earlier.
Lost it? **[Create a new one here.](https://github.com/shuvmaybe/groqsetup?tab=readme-ov-file#2-creating-api-key)**

That's it! Enjoy playing!
If you're new here, [join the Discord community](https://discord.gg/skAx6tyqvF).
Thank you.
