# Alone-Official

Normal commands 

Member count
$nomention
$title[━━━ALONE HOMΣTOWП━━━]
$description[Total Mamber:$membersCount]
$footer[●━━━━━━━━━━━━━━━━━━━━━●]
$color[00ff59]

Av
$nomention
$title[**avtar**]
$description[]
$footer[]
$color[#5c0aff]
$image[$userAvatar[$mentioned[1]]]

Em
$nomention
$title[$message[1]]
$color[00ff11]
$footer[$message[3]]
$description[$message[2]]

Help
$nomention
$addCmdReactions[✔]
$dm 
$title[**ΛLӨПΣ ӨFFICIΛL CӨMMΛUПDS**]
$color[ff3333]
$description[**MODERATION COMMANDS**

A!mute {user} - mutes a user
A!unmute {user} - unmutes a user
A!ban {user} - bans a user
A!unban {user} - to unban a user
A!setmute {role} - sets mute role
A!kick {user} - to kick a user 

**FUN COMMANDS**

A!membercount - current members in the server
A!slap {user} - posts a slapping gif
A!punch {user} - posts a punching gif
A!cry - sends crying gif
A!hug {user} posts a hugging gif
A!av {user} - sends mentioned users avatar 
A!image {text} - posts imaged text
A!say {text} - to send text from bot
A!em {titel} {description}{footer} - Posts embed]
$footer[]

Moderation commands

Set mute
$nomention 
$onlyAdmin[you must be admin]
$setVar[Muted;Muted]
The mute role is now set as $message 

Mute
$argsCheck[>1;Please mention somebody to mute.]
$nomention $mute[Muted]
$onlyPerms[manageroles;<:error:581372917737193472>**You don't have enough premonition to run this command**]
$title[▄︻デ═Mυƚҽ═══━一]
$color[00ff11]
$footer[Mυƚҽԃ Ⴆყ $username.]
$description[
Mυƚҽԃ:<@$mentioned[<]>]

Unmute
$argsCheck[>1;Please mention somebody to unmute.]
$nomention $unmute[Muted]
$onlyPerms[manageroles;<:error:581372917737193472>**You don't have enough premonition to run this command**]
$title[▄︻デ═UNMUTE═══━一]
$color[00ff11]
$footer[Uɳɱυƚҽԃ Ⴆყ $username.]
$description[
Uɳɱυƚҽԃ:<@$mentioned[<]>]

Ban
$argsCheck[>1;Please mention somebody to ban.]
$nomention $ban
$onlyPerms[manageroles;<:error:581372917737193472>**You don't have enough premonition to run this command**]
$title[▄︻デ═BAN═══━一]
$color[00ff11]
$footer[Bαɳ Ⴆყ $username.]
$description[
Bαɳ:<@$mentioned[<]>]

Unban
$argsCheck[>1;Please mention somebody to unban.]
$nomention $unban
$onlyPerms[manageroles;<:error:581372917737193472>**You don't have enough premonition to run this command**]
$title[ ▄︻デ═UNBAN═══━一 ]
$color[00ff11]
$footer[UɳႦαɳ Ⴆყ $username.]
$description[UɳႦαɳ Ⴆყ:<@$mentioned[<]>]

Clear
$nomention
$embedSuppressErrors[Failed to clear message!;Something went wrong;ff0000;;;]
$onlyIf[$guildID!=;]
$onlyPerms[managemessage;❌ <@authorID> you aren't allowed to do that!] 
$onlyif[$noMentionMessage] >= [Usage: ``!clear <amount> <@user> ``]

Deleting Messages....

$editIn[1s;Successfully deleted $noMentionmessages messages]
$clear[$noMentionmessages;
$replaceText[$replaceText[&$mentioned[1]&;&&;;1];&$mentioned[1]&; $mentioned[1];1]yes]

Fun commands

Slap
$nomention
$argsCheck[>1;**Pls mention somebody to slap]
$color[$randomText[ff0000;fff000]]
$title[]
$description[**👋<@$authorID> SLAPED <@$mentioned[1]> **]
$image[$randomText[https://bolojawan.com/wp-content/uploads/2017/08/giphy-2.gif;https://cdn.weeb.sh/images/HJKpm1twW.gif;https://cdn.weeb.sh/images/H1n57yYP-.gif;https://cdn.weeb.sh/images/HJcoQ1Fwb.gifhttps://cdn.weeb.sh/images/HkA6mJFP-.gif;https://cdn.weeb.sh/images/SJdXoVguf.gif;https://cdn.weeb.sh/images/Hk6JVkFPb.gif;https://cdn.weeb.sh/images/BJgsX1Kv-.gif]]

Punch
$nomention
$argsCheck[>1;**Pls mention somebody to punch]
$color[$randomText[ff0000;fff000]]
$title[]
$description[**👊💥 <@$authorID> PUNCHED <@$mentioned[1]> DHISHOOOM! **]
$image[$randomText[https://cdn.weeb.sh/images/SJAfH5TOz.gif;https://cdn.weeb.sh/images/ByI7vTb-G.gif;https://cdn.weeb.sh/images/SyYbP6W-z.gif;https://cdn.weeb.sh/images/BkdyPTZWz.gif;https://cdn.weeb.sh/images/HkFlwpZZf.gif;https://cdn.weeb.sh/images/rJRUk2PLz.gif;https://cdn.weeb.sh/images/BJg7wTbbM.gif;https://cdn.weeb.sh/images/B1rZP6b-z.gif]]

Image
$nomention
$deletecommand
$title[]
$description[]
$image[https://flamingtext.com/net-fu/proxy_form.cgi?script=3d-logo&text=$message[1]+$message[2]+$message[3]+$message[4]+$message[5]+$message[6]+$message[7]+$message[8]+$message[9]+$message[10]+$message[11]+$message[12]+$message[13]+$message[14]+$message[15]+$message[16]+$message[17]+$message[18]+$message[19]+$message[20]+&_loc=generate&imageoutput=true]
$color[$random[0;999999]]

Say
$nomention
$deletecommand
$message

Cry
$nomention
$color[$randomText[ff0000;fff000]]
$title[]
$description[**😥<@$authorID> STARTED CRYING**]
$image[$randomText[https://cdn.weeb.sh/images/B1Jg1eqJM.gif;https://cdn.weeb.sh/images/HJZX78Xw-.gif;https://cdn.weeb.sh/images/SJ08mUXwZ.gif;https://cdn.weeb.sh/images/rJXwmLQv-.jpeg;]]

Hug
$nomention
$argsCheck[>1;**Pls mention somebody to punch]
$color[$randomText[ff0000;fff000]]
$title[]
$description[** ☺<@$authorID> hugs <@$mentioned[1]> **]
$image[$randomText[https://cdn.weeb.sh/images/HytoudXwW.gif;https://cdn.weeb.sh/images/S1a0DJhqG.gif;https://cdn.weeb.sh/images/S1DyFuQD-.gif]]
