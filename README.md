## بسم الله الرحمن الرحيم  

## QKareem  

discord bot that plays Holy Quran chapters in different reciters voice,  
this bot wrriten in java using JDA discord api wrapper and lavaplayer with some utils.  

it's free but not fully completed and i have hope to complete it, as soon as i got free time.  
also i'm planing to write documention and hosting guide.  

here's some things i'm planing to do in the future.    
- create search command that searchs for specifed surah (chapter) or reciter  
- create skip command that skips the current surah.  
- create all command which plays all the specified surha(s)  
- making the bot more easy and comfortable  

### usage

first of all, you should have the following  
- java  
- JDK >= 8  
- gradle  

clone this repository, and add config.txt file in the root of the directory with following content  
```conf
token=
prefix=Q.
```
include a token for a bot to run.
run `gradle run`
go ahead and test the bot using `Q.play 1 "يوسف بن نوح أحمد"`  
where `1` is chapter id and `"يوسف بن نوح أحمد"` reciter name esacped with `"`  
there's no curently way to list the reciters instead find them in json/reciters.json  


use this bot at your own risk i'm not responsiable for any bad use of this bot.
i appreciate your help if you want to contribute in this project, i'm avaliable on discord: `Ahlin Chan#0630`