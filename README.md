LisasGradleTemplate
===================

A gradle template, currently for Minecraft Forge/ForgeGradle, perhaps eventually for other things.

Files
-----
 * `build.gradle` - gradle build file for forge mod projects
 * `settings.gradle` - sets the root project
 * `build.properties` - various properties including the minecraft version and forge version, project name, etc.

I intend, eventually, to expand support; including multi-project builds, however, for the time being the intent is simply to provide a simple way to take existing mod projects (or to create new ones, to be distributed via, e.g. git (and perhaps even non-forge and even non-minecraft builds in the future!)

Note that the intent is also to make use external configuration in order to allow this file to remain the same for various projects; if you want to contribute to the project, please keep that in mind. I still have not done most of the legwork necessary to make a complex build possible this way. for now, a simple build seems to be working.
 
Instructions for Use
--------------------
1. create sources in, or move them into, the standard gradle java source locations:
 * `src/main/java` - `.java` files
 * `src/main/resources` - other project resources (`.png`, etc.)
2. copy the files in this project into the root folder of your project
3. edit `build.properties` as instructed in that file, and set the project name in `settings.gradle`
4. follow the building instructions in `build.gradle`
 * given below, but the instructions in the comments of build.gradle take precdence)
 
Building (from `build.gradle`)
------------------------------
to use this project, run the following commands; with 'gradlew' if you want to use gradle wrapper included in the project, or with 'gradle' to use a local installation of gradle
 * to clean the project (optional, not necessary on initial builds):

 `gradlew clean cleanCache`
 
 * setup Minecraft decompilation workspace, where necessary (ok to try without; use if failed):

 `gradlew setupDecompWorkspace --refreshDependencies`
 
 * to build (build output will be in 'build/libs'):
  
 `gradlew build`

 * to setup for development

 `gradlew setupDevWorkspace`

 * and, to set up for idea/eclipse development:

 `gradlew idea` (for IntelliJ IDEA)

 or
  
 `gradlew eclipse` (for Eclipse)

thank You!
----------
what i have done is little compared to the rest of the folks that made this possible:

 * http://www.gradle.org - the folks behind gradle

 * http://mcp.ocean-labs.de/page.php?4 - the folks behind the Minecraft Coder's Pack

 * http://www.minecraftforge.net - the folks behind Minecraft Forge/FML and ForgeGradle
 * http://github.org/MinecraftForge/MinecraftForge - the MinecraftForge github
 * http://github.org/MinecraftForge/ForgeGradle - the ForgeGradle github

and a few extra props for having gradle/ForgeGradle projects that have helped me in building their projects, and who inspired me to make this repo:
 
 * http://www.extrabiomes.net - home of ExtraBiomesXL
 * http://github.org/ExtraBiomesXL/ExtraBiomesXL - the ExtraBiomesXL github

 * https://github.com/MinecraftPortCentral/Cauldron - Minecraft modded server; Cauldron = bukkit + forge

 * https://github.com/Mine-and-blade-admin/Battlegear2 - dual weilding and combat mod for Minecraft 

You Can Help Save The World!
----------------------------

from `build.gradle`:

and finally: want to change the world? you can only do that by changing yourself. join me and other true believers in Love, and, you too, will save the world! 

how, you ask? if you want, start by putting this blurb, or something like it, in the whatever you give the world from your heart! :)

it's easy! be faithful to others, even if it's hard. love and forgive everyone (yourself, your friends, and even enemies!) do your best to be yourself, and to be happy. and be sure to do your best to help other people you come into contact with do that stuff too.

that, true believers, is real salvation: not in the far-off empty promises of an afterlife, at the expense of this one, but, instead, in the here and now, from the hell that you make for yourself as you try to be someone other than who you truly are, and when you don't try to open up your plans and focus on bringing the things that *you* value into this world.

and that is my message. my prophecy is this: it is our time! and we will save the world...

together, on our own,
(false?) prophetess lisa, PlayLaughLoveLearn, <3 here+now








and, you can help save me too
-----------------------------

you don't need to read further if you just want to use my stuff, it's for everyone, and it's double-free. :)

sigh. any time i put something like this i feel like a heel. 

but i am trying to make a go of things without a job due to some health issues that have hit over the past decade or so of my life. i can't even currently support myself or my family, but have been luckier than a lot of folks, i know, since my dad has been helping.

i am giving away everything i make either under a permissive license or into the public domain, because, well, that's what i believe is right. and i have to this point avoided taking tax-funded assistance, because, even though i have put quite a bit in in taxes, i believe (and rightly so) that all the money taken from me has been spent, and more; and because i don't believe it's right to do so as long as there is another option.

my options are quickly running out.

i tell you this because i have promised myself, the Universe, and everyone else, to do so; that i intend to be fully open and honest about my life, due to those that have inspired me by doing the same. and i have been doing so for the past couple of months through my youtube channel, my twitch channel, my deviant art blog, and whatever other methods i have to share of myself, including sharing lots of things about myself i never thought i would in hopes that my confessions can help someone else through some of the hard things i've gone through.

so, if for whatever reason you feel that i have offered you something of value, i am very appreciative of any support that you might throw my way, from just looking at my art or vids, or using my stuff; and, of course, i'm very appreciative of any donations you care to make. i'm not a charitable institution, i'm not tax-deductible, but i'm trying to do my best to share of myself, and, to whatever extent possible, to change the world.

you can donate to me through my paypal via playlaughlovelearn@thebutterflieseffect.org; if for whatever reason that's not acceptable, or not available to you, or you wish to contact me for any other reason, i can be reached via email at that address.

thanks. :)

to: You
from: my <3
lisa
