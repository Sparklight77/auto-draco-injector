# Auto-Draco-Injector
A bash script for Termux to automate the complex process of patching Minecraft using Draco-Injector. Based on a repo by mcbegamerxx9541 which you can find [here](https://github.com/mcbegamerxx954/draco-injector). Thanks to [callmesoumya2063](https://github.com/CallMeSoumya2063) for testing and fixing few issues.

It should be noted that i don't know bash well, i studied saveral repos and in turn i was able to create something like this.
 
# Tutorial
1. You need to install [termux](https://github.com/termux/termux-app/releases)

2. Place Minecraft Apk file in Downloads folder (note that Apk should have Minecraft in its name otherwise script won't detect it)

3. Open Termux and run this command ```curl -o Draco_injector.sh https://github.com/Sparklight77/Auto-Draco-Injector/blob/main/Draco_injector.sh && apt update -y && apt upgrade -y && clear```

4. Follow Instructions 

5. After patching once just use `bash draco-injector.sh` for starting injector

6. After Patching Minecraft Apk, you can find it in `Patch`folder in home directory
>[!Note]
You Should be connected to network during Patch process. Playstore Minecraft have 64bit and 32bit merged in one apk, to make them saperate you have to use [ApkTool M](https://maximoff.su/apktool/?lang=en) antisplit feature and put the output apk in downloads folder then you can run injector start command. You can patch and install 32bit Minecraft apk on 64bit device but it will result in performance issues so its recommended to use apk according to device.

>[!important]
If you encounter any issues then report it in mcpegamerxx9541 repository which you can find [here](https://github.com/mcbegamerxx954/draco-injector/issues), simply open an issue, tell your problem and mention you used my script for patching Minecraft.

# Note
If you find any issues or want to suggest me something then open an issue. Iam always looking for improvements.
