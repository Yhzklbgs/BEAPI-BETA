## REQUIREDMENT ##
```PY
pip3 install httpx && pip3 install httpx[http2]
```

## EXAMPLE ##
- ALPHACODERS
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.alphaCodersSearch("naruto", 1)
api.pretyPrint(res) #for prety print result
```

- ANIMESTREAM
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.animeOngoing()
api.pretyPrint(res) #for prety print result
```

- ANIMEXIN
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.animeXin()
api.pretyPrint(res) #for prety print result
```

- AUTHKEY2PRIMARY
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.authKey2Primary('your line authkey')
api.pretyPrint(res) #for prety print result
```

- ALPHACODERS
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.alphaCodersSearch("naruto", 1)
api.pretyPrint(res) #for prety print result
```

- BRAINLY
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.brainlySearch('kenapa bumi bulat')
api.pretyPrint(res) #for prety print result
```

- GIFSEARCH
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.gifSearch("naruto")
api.pretyPrint(res) #for prety print result
```

- GOOGLESEARCH
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.googleSearch("naruto")
api.pretyPrint(res) #for prety print result
```

- GOOGLEIMG
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.googleImg("naruto")
api.pretyPrint(res) #for prety print result
```

- GOOGLE TRANSLATE
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.googleTranslate('anjing', 'en')
api.pretyPrint(res) #for prety print result
```

- IMGREVERSE
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.googleImgReverse("url_img")
api.pretyPrint(res) #for prety print result
```

- INSTAGRAM
```PY
from BEAPI import BEAPI
api = BEAPI()
#INSTAGRAM POST
#res = api.instaPost("https://www.instagram.com/p/CNLOThQjnzU/")
#api.pretyPrint(res) #for prety print result
#INSTGRAM PROFILE
res = api.instaProfile("instagram")
api.pretyPrint(res) #for prety print result
```

- JOOXSEARCH
```PY
from BEAPI import BEAPI
api = BEAPI()
#WITH SEARCH QUERY
res = api.jooxSearch("bring me the horizon")
#WITH SONG ID
res = api.jooxId("1W09eg2vDIJLQgrWOj_4FQ==")
api.pretyPrint(res) #for prety print result
```

- KAMUS INDONESIA
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.kamusIndonesia("makan")
api.pretyPrint(res) #for prety print result
```

- LINEAPPNAME LAST
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.lineAppName()
api.pretyPrint(res) #for prety print result
```

- LINEAPPNAME RANDOM
```PY
from BEAPI import BEAPI
api = BEAPI()
#["android","ios","androidlite","chromeos","desktopmac","desktopwin","iosipad"]
res = api.lineAppNameRandom("chromeos")
api.pretyPrint(res) #for prety print result
```

- LINE QR ROTATE
```PY
from BEAPI import BEAPI
api = BEAPI()
qr = api.lineGetQr("IOSIPAD\t10.5.2\tiPhone 8\t11.2.5")
print("Link QR: "+qr["result"]["qrlink"])
print("IP: "+qr["result"]["ip"])
pincode = api.lineGetQrPincode(qr["result"]["session"])
print("Pincode: "+pincode["result"]["pincode"])
auth = api.lineGetQrAuth(qr["result"]["session"])
print("AccessToken: "+auth["result"]["accessToken"])
print("Cert: "+auth["result"]["certificate"])
```

- LINEPRIMARYCONVERT
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.linePrimary2Secondary("IOSIPAD\t10.5.2\tiPhone 8\t11.2.5","your_authtoken")
api.pretyPrint(res) #for prety print result
```

- 9GAG
```PY
from BEAPI import BEAPI
api = BEAPI()
##['funny', 'among-us', 'animals', 'anime-manga', 'animewaifu', 'animewallpaper', 'apexlegends', 'ask9gag', 'awesome', 'car', 'comic-webtoon', 'coronavirus', 'cosplay', 'countryballs', 'home-living', 'crappydesign', 'cyberpunk2077', 'drawing-diy-crafts', 'rate-my-outfit', 'food-drinks', 'football', 'fortnite', 'got', 'gaming', 'gif', 'girl', 'girlcelebrity', 'guy', 'history', 'horror', 'kpop', 'timely', 'leagueoflegends', 'lego', 'superhero', 'meme', 'movie-tv', 'music', 'basketball', 'nsfw', 'overwatch', 'pcmr', 'pokemon', 'politics', 'pubg', 'random', 'relationship', 'savage', 'satisfying', 'science-tech', 'sport', 'starwars', 'school', 'travel-photography', 'video', 'wallpaper', 'warhammer', 'wholesome', 'wtf', 'darkhumor', 'funny', 'nsfw', 'girl', 'wtf', 'anime-manga', 'random', 'animals', 'animewaifu', 'awesome', 'car', 'comic-webtoon', 'cosplay', 'cyberpunk2077', 'gaming', 'gif', 'girlcelebrity', 'leagueoflegends', 'meme', 'politics', 'relationship', 'savage', 'video', 'algeria', 'argentina', 'australia', 'austria', 'bosniaherzegovina', 'bahrain', 'belgium', 'bolivia', 'brazil', 'bulgaria', 'canada', 'chile', 'colombia', 'costarica', 'croatia', 'cyprus', 'czechia', 'denmark', 'dominicanrepublic', 'ecuador', 'egypt', 'estonia', 'finland', 'france', 'georgia', 'germany', 'ghana', 'greece', 'guatemala', 'hongkong', 'hungary', 'iceland', 'india', 'indonesia', 'iraq', 'ireland', 'israel', 'italy', 'japan', 'jordan', 'kenya', 'kuwait', 'latvia', 'lebanon', 'lithuania', 'luxembourg', 'malaysia', 'mexico', 'montenegro', 'morocco', 'nepal', 'netherlands', 'newzealand', 'nigeria', 'norway', 'oman', 'pakistan', 'peru', 'philippines', 'poland', 'portugal', 'puertorico', 'qatar', 'romania', 'russia', 'saudiarabia', 'senegal', 'serbia', 'singapore', 'slovakia', 'slovenia', 'southafrica', 'southkorea', 'spain', 'srilanka', 'sweden', 'switzerland', 'taiwan', 'tanzania', 'thailand', 'tunisia', 'turkey', 'uae', 'usa', 'ukraine', 'uk', 'uruguay', 'vietnam', 'yemen', 'zimbabwe']
res = api.nineGagFresh('funny')
api.pretyPrint(res) #for prety print result
#OR
res = api.nineGagHot('funny')
api.pretyPrint(res) #for prety print result
```

- 1CAKRANDOM
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.oneCakRandom()
api.pretyPrint(res) #for prety print result
```

- SIMISIMI
```PY
from BEAPI import BEAPI
api = BEAPI()
#['af', 'al*', 'ar', 'hy', 'az', 'eu', 'be', 'bn', 'bs', 'bg', 'ca', 'cx*', 'ch*', 'hr', 'cs', 'da', 'nl', 'en', 'et', 'ph*', 'fi', 'fr', 'fy', 'gl', 'ka', 'de', 'el', 'gu', 'he', 'hi', 'hu', 'is', 'id', 'it', 'ja', 'kn', 'kk', 'kh*', 'ko', 'ku', 'lv', 'lt', 'mk', 'ms', 'ml', 'mr', 'mn', 'my', 'ne', 'nb', 'as', 'br', 'gn', 'jv', 'or', 'rw', 'zh*', 'ps', 'fa', 'pl', 'pt', 'pa', 'ro', 'ru', 'rs*', 'si', 'sk', 'sl', 'es', 'sw', 'sv', 'tg', 'ta', 'te', 'th', 'tr', 'uk', 'ur', 'uz', 'vn*', 'cy']
res = api.simiSimi('anjing', 'id')
api.pretyPrint(res) #for prety print result
```

- SMULE
```PY
from BEAPI import BEAPI
api = BEAPI()
#res = api.smulePerformance("JoseffMcKenneth")
#res = api.smuleUser("JoseffMcKenneth")
res = api.smulePost("https://www.smule.com/p/2352981025_3553994501")
api.pretyPrint(res) #for prety print result
```

- SHORTLINK
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.shortLink('https://google.com')
api.pretyPrint(res) #for prety print result
```

- SCREEN SHOT WEB
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.screenShotWeb('https://google.com')
api.pretyPrint(res) #for prety print result
```

- TRACKRESI
```PY
from BEAPI import BEAPI
api = BEAPI()
#['pos', 'wahana', 'jnt', 'sap', 'sicepat', 'jet', 'dse', 'first', 'ninja', 'lion', 'idl', 'rex', 'ide', 'sentral']
res = api.trackingResi('your_resi', 'your_courier')
api.pretyPrint(res) #for prety print result
```

- TIKTOK
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.tiktokPost("https://www.tiktok.com/@msglowbdl/video/6933152608211307778")
api.pretyPrint(res) #for prety print result
res = api.tiktokPostV2("https://www.tiktok.com/@msglowbdl/video/6933152608211307778")
api.pretyPrint(res) #for prety print result
res = api.tiktokProfile("@msglowbdl")
api.pretyPrint(res) #for prety print result
```

- STORAGE UPLOAD
```PY
from BEAPI import BEAPI
api = BEAPI()
res = api.storageUpload('path_to_file')
api.pretyPrint(res) #for prety print result
```

- YOUTUBE
```PY
from BEAPI import BEAPI
api = BEAPI()
#res = api.youtubeDownloadUrl("https://www.youtube.com/watch?v=N5_9eyFqD5E")
#api.pretyPrint(res)
res = api.youtubeDownloadSearch("bring me the horizon")
api.pretyPrint(res)
```

## INFORMATION ##
STATUS: ACTIVE
<br />
UPDATE STATUS: CONTINUE 
<br />
LAST UPDATE: 28/10/21
<br />
MAX CONCURRENT: 1
<br />
LICENSE: FREE
