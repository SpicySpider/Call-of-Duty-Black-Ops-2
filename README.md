# Call-of-Duty-Black-Ops-2

                                          ,,,,,                                   
                                     ,g@@$$@@@@$@N,                               
                                  ,g@MT4$@@@@@@@@@$@gg                            
                                 @$P|||||1@@@@@@@@@@@@$@g                         
                                @@,|||||,g$@@@@@@@@@@@@@$K                        
                           ,gT||@$$$$$$$$$$||Z*N$@@@@@@@@@                        
                        ,$|j|||A||T1$*T|||,w+S|||$@@@@$$N                         
                        }||||$ITTTZTT||g||,gQ|g@g$@$@$$P                          
                 g@@$$$@@@@$$$$&$$$$&$$$$$$$$$@$$@@$$$$     ,,ggggg,,             
              ,@$@&&$$B&$$@@$@$$$$$$$$$$$@$$$$@@$B$$$@@@@@$$$$@$@@@@@$Bg          
             g@@+|||||w,  *B@@$$$$$$$$$$$&@@@$@@@@$$$BNPP*$$@@@$$@$@@@@$k         
          ,@@@@@g&w$@&$@@@Bg$@$$$$$$$$$$$$@$BNNB$$$NJggggw $@@@@@@$$@$@@@         
         g$@@@@$@T||||P"]PNB&$$$$$$M$$$$@$L||||||@$@@@@@@@$BQB@@@@@@@@g$@         
        ]@@@@@P-  "9|[ g$@g ]$$$$$$$$$@@@@@$$||||PT7"]@@@@@@@$g"N$@@@@@@          
        ]@@P-       $y@@*PNBg$@$$N*$$$@@$|;2$$@*`     "B@@@@@@@@,  -*B@[          
        ]$"         ]@`     "$-    ] $@@P               ]N$@@@@@$N    @           
         P          "                 ]@F                  "N$@@@@@   -           
                                       @                      "%@@@P              
                                                                ]@@               
                                                                 @                
	       _____       _            _____       _     __         
	      / ___/____  (_)______  __/ ___/____  (_)___/ /__  _____
	      \__ \/ __ \/ / ___/ / / /\__ \/ __ \/ / __  / _ \/ ___/
	     ___/ / /_/ / / /__/ /_/ /___/ / /_/ / / /_/ /  __/ /    
	    /____/ .___/_/\___/\__, //____/ .___/_/\__,_/\___/_/     
	        /_/           /____/     /_/           

        		 |Call of Duty: Black Ops 2|
		 PLUTONIUM INSTALLATION & SERVER INFORMATION

# General Information

Hey, I'm SpicySpider. I'm a former decorated double shotgun ranked, easter egg
completionist, Playstation 3 pleb. I was able to log into my old BO2 account and find some of my statistics, near the 
end of playing zombies I didnt care as much and didnt do as well. Below is what I
found on my summary:
```				Career Stats:
		Kills: 					201422
		Bullets Fired: 				1140249
		Downs: 					3195
		Revives: 				2476
		Grenade Kills: 				9905
		Headshots: 				41658
		Deaths: 				1434
		Gibs: 					197787
		Perks: 					3793
		Doors: 					2360
		Accuracy: 				0.86
		Miles Traveled:				3414
```
Since then, I've started college as an Electrical Engineer and have gotten more 
into PCs, technology, and general coding. The purpose of this document is mostly 
for general purpose guides and specifically how I run my servers for plutonium. 
In case you aren't aware, Plutonium is a free patch/install for Black Ops 2 and 
Modern Warfare 3 which allows dedicated servers, customizability, and fixes for 
the original games. The content of this document will evolve as my servers do 
so please bare with me. I felt the need to write this since I have spent the last 
2 months really learning plutonium's ins and outs; and the information isnt as readily
availible as I believe it should be.

Please note some of my information below, dont be afraid to contact me.

SpicySpider Discord:
https://discord.gg/kjtDNXB

Twitter:
https://twitter.com/SpicySpidertv

Twitch:
https://www.twitch.tv/spicyspidertv

Donate(directs to paypal donation page):
https://rb.gy/2zyx6b


# Guide: How to Install Plutonium


I don't think I can really make it any easier than plutonium says so:
https://forum.plutonium.pw/topic/2819/how-to-install-update-plutonium-t6


# Server Setup


https://forum.plutonium.pw/topic/13/plutot6-server-set-up-guide
If you need any help go to the Plutonium Discord: https://discord.gg/hbrmKA


https://forum.plutonium.pw/topic/1589/installing-iw4madmin-to-your-dedicated-server-windows
If you need any help go to the IW4M Admin Discord: https://discord.gg/YyUevV

If you want people to access your server you NEED to port forward. Here is an 
amazing website containing almost all the routers and guides to port forward them:
find your router and follow it. Make sure you do the same port as your server and
you'll use UDP protocol.

https://portforward.com/router.htm



# Modding and GSC Code

Finally we get to the more difficult part. GSC coding is interesting. You can always
steal code from someone for like Zombies++, Zombies Reimagined, or even just the
restart mod from Jezuzlizard (link below). 

https://forum.plutonium.pw/topic/308/release-zombies-map-restart-clientside-issues-workaround

Those are cool and all but I think its important to code them a least some yourself.
I know this will fall on deaf ears but hear me out. First, read this:

https://forum.plutonium.pw/topic/10/tutorial-loading-custom-gsc-scripts?_=1598220368780

Make sure to download the toolkit from the link as well as it will have the
compiler for us. I'm going to be completely honest, GSC coding is something
you MUST learn yourself. The way I learned is literally just reverse 
engineering some of the codes I'll be posting here. It took a long time, and 
probably wasn't the best way, but it's the way I stay interested. If that's wrong
then I dont really wanna be right. Regardless if this method seems bad, here
is another link that will probably explain it better for you.

https://forum.plutonium.pw/topic/198/resource-gsc-resources-and-helpful-links

Theirs really no way for me to make it easier for you if your interested in GSC.
With that said, let me go ahead and give you everything to make it easier for you.
Here is every single thing I used to make my own personal GSC's:

https://github.com/Jbleezy/BO2-Reimagined

https://forum.plutonium.pw/topic/124/resource-gsc-working-tombstone-fix-works-on-tranzit-and-town?_=1599021222048

https://forum.plutonium.pw/topic/1061/release-set-money-for-late-people-joining

https://forum.plutonium.pw/topic/870/release-set-money-on-spawn-zombies/1

https://forum.plutonium.pw/topic/308/release-zombies-map-restart-clientside-issues-workaround

https://forum.plutonium.pw/topic/29/release-all-perk-slots-unlock-script-zombies?_=1599021298425

https://cabconmodding.com/threads/black-ops-2-zombie-gsc-give-all-perks-function.2266/

Lastly here is links to all my personal GSC's. These should be compiled and uncompiled.
Enjoy.

https://drive.google.com/file/d/1fXkeZGeHYtDsnPfTkXIXXTRD0tQnEzqS/view?usp=sharing


===================================================================================
				    TOWN FIX
===================================================================================
Lastly, I'm kinda conflicted if I should be sharing this. Apperently it's kind
of a big deal to plutonium as I personally talked to someone who got banned for
looking into this. I don't really know what to believe all I know is just keep
this to yourself. For my sake. I dont really want to come back to this project
one day and find out I'm banned. Anyways, long story short you can play Town on 
a custom match but if you try to run it on a dedicated server it just doesnt work.
Anyways I found a way to make it run and have been using it on my servers so the
fix goes like this. It's not really a fix, but it works so. eh.

find the line named sv_maprotation "gametype zclassic loc tran... etc" and comment
it out my simply adding two // behind it. should look like this:

//sv_maprotation "gametype zclassic loc transit map zm_transit"

Now since you just commented out the line that lets you choose maps, you need to 
add something else to allow you to use town. The lines you need to add are below.
Just copy and paste this below the commented out sv_maprotation.

===================================================================================
				  Final thoughts
===================================================================================
Why am I done running servers? This was never really for other people, this project
was for me. It was mostly a self purposed challenge and I learned a lot. Was this
information useless? maybe... but I met some really cool people along the way.
I really don't have time to work on these servers anymore so I think I'm happy to 
close the chapter here.
The plutonium community is pretty interesting, the people in plutonium are pretty jaded. 
Getting information from them is very difficult at times and it may seem like they are 
working against you occationally. Regardless, there were other people, like me, whom 
really loved this project and wanted to help. I absolutely wouldn't have gotten my 
servers where they were without you guys.

I send my sincerest gratitude to RaidMax, Luigistyle, Amused, JezuzLizard, Ashton Biehl,
Swifty, JBleezy, CodFishCody, Joey Winchester, 💙💜Brandon💜💙, and MANY more.
Honestly, if I hadn't gained the following I did I would have never spent this 
much time on the servers.
Below were some of the patches, this was my personal list and things I wanted to do
were eventually listed below. Honestly, This is maybe 10 percent of the actual fixes
I did with the servers but I didnt think every little change needed to be reported.
You can probably find more information on the twitter. Theres a lot more to be said
and the information to completely recreate the servers aren't all here. Theirs too
much to discuss and I can't remember all the issues I've dealt with in 2 months.
Stay Spicy 



===================================================================================
				  Major Patches
===================================================================================
Issues				   		 Date			Status
patch !discord command with aliases		8/31/2020		Live
add discord to webfront				8/31/2020		Live
Include Webfront for website			8/31/2020		Live
Different run speed for Origins			8/30/2020		unpatched
dynamic money resetting points			8/30/2020		Live
Points & Money not loading       		8/30/2020		Unknown
Shovels not spawning		  		8/29/2020		Unknown
IW4M Admin Webfront accessability		8/29/2020		Live
Tombstone Fix for Town and Tranzit		8/29/2020		Live
Point,kap40, jugg delayed loading		8/29/2020		Live
Not able to run client after server init	8/28/2020		Unknown
Update Servers to new T6 update			8/23/2020		Live
Dynamic Money					8/12/2020		Live
Point Visualization for 4+ lobbies		8/12/2020		Pruned
Paralyzer and MOTD plane broken			8/09/2020		Unknown
Afterlife, Welcome messages			8/07/2020		Live
IW4M Admin					8/06/2020		Live
Added too many server (Limit found 15)		8/05/2020		Pruned
__________________________________________________________________________________
More Servers					7/29/2020		Live
Fast Restart blackscreen			7/25/2020		Live
Edited Reimagined GSC				7/23/2020		Live
