# How-to-bypass-Spotify-in-Russia-so-that-the-Discord-integration-works-and-everything-loads.
ПРИВЕТ! Я РАССКАЖУ КАК ОБОЙТИ СПОТИФАЙ ЧТОБЫ ВСЕ РАБОТАЛО И РАБОТАЛА ИНТЕГРАЦИЯ  ДИСКОРД! СЛЕДУЙ ПО МОИМ ШАГАМ!
ПРОЕКТ ГДЕ-ТО ДЕЛАЛ САМ! ГДЕ-ТО ПОМОГ ИИ! (Квантис) 

=== SPOTIFY ОБХОД ===

1. ПОДГОТОВКА + ZAPRET
Сначала скачай Spotify через VPN (любая страна, где он работает: США, Германия, Польша и т.п.) и зарегистрируйся там. VPN нужен только для установки и создания аккаунта, потом его можно выключить.
После этого добавь в Zapret:

Файл: lists\list-general-user.txt (если нет — list-general.txt)
Вставь в конец:

api.spotify.com
login5.spotify.com
encore.scdn.co
gew1-spclient.spotify.com
spclient.wg.spotify.com
api-partner.spotify.com
aet.spotify.com
www.spotify.com
accounts.spotify.com
open.spotify.com
gew1-dealer.spotify.com
accounts.scdn.co
open-exp.spotifycdn.com
www-growth.scdn.co


2. ЧТОБЫ ГРУЗИЛО КАРТИНКИ / ОБЛОЖКИ
Туда же, в тот же файл:

i.scdn.co
o.scdn.co
p.scdn.co
pl.scdn.co
mosaic.scdn.co
charts-images.scdn.co
audio-fa.scdn.co
line-in.scdn.co
canonical.scdn.co
canonical-v4.scdn.co
t.scdn.co
canvaz.scdn.co
seektables.scdn.co
image-cdn-fa.spotifycdn.com
pickasso.spotifycdn.com
seed-mix-image.spotifycdn.com
concerts.spotifycdn.com
thisis-images.spotifycdn.com
spotifycdn.com
spotifycdn.net
podz-content.spotifycdn.com
wap.spotifycdn.com
web-sdk-assets.spotifycdn.com


3. СТАТУС В DISCORD (ФИНАЛЬНАЯ КОРОЧКА)
Скачай:
https://github.com/ungive/discord-music-presence

Установи, запусти. Discord сам подхватит статус Spotify.
Официальная интеграция Spotify для этого не нужна.

=== ПОСЛЕ ВСЕГО ===
- Перезапусти Zapret (закрой .bat и запусти заново)
- Перезапусти Discord
- Если статус не появился сразу — перезагрузи ПК

                                           *Фишки от Квантиса 

связь с создателем:
tg:@Qu4ntis
поддержка автора (2202 2092 8357 2047)
