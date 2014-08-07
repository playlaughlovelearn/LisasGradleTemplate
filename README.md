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

