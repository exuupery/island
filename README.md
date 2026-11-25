<div align="center">

<img src="app-icon.svg" width="96" alt="Island icon">

# Island

**Dynamic Island for Windows**

![Windows 10 and 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4)
![Latest release](https://img.shields.io/github/v/release/exuupery/island?label=release&color=8ea2ff)
![Interface: English and Russian](https://img.shields.io/badge/interface-English%20%7C%20%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-8ea2ff)

</div>

<details>
<summary><b>English</b> · click to read in English</summary>
<br>

<div align="center">

A liquid black pill at the top of your screen that shows what is happening right now<br>
and opens into a toolbox when you reach for it.

<img src="docs/img/en/hero.png" width="860" alt="Island opened on the Home tab: player, volume, quick actions, launcher">

</div>

## What it is

Island sits on top of every window, in the middle of the top edge. Collapsed, it is a small pill that
tells you about music, downloads, the microphone, a screen recording. Rest the cursor on it, or push
the cursor against the top edge, and it opens into a panel: clipboard history, a file shelf, text tools,
an AI chat, screenshots, a command bar, the weather and a control centre.

It never takes the keyboard focus away from the window you are typing in, so a click on a clipboard
entry pastes it right where the caret is.

<div align="center">
<img src="docs/img/demo-en.webp" width="760" alt="The Eyes wake up and say hello; the island reaches for the cursor, plays music, opens on a hover and goes through every tab: Home, the clipboard, the shelf, the text tools, the AI chat, the note, the weather, the control centre; then the command bar, a download, the computer's load, auto-hide, characters, the New Year and the light theme">
</div>

## The pill is alive

The island itself is made of ferrofluid. Its lower edge reaches for the cursor, spikes to the music in
the colour of the album cover, drops a bead when something good happens and sags when you are away.

<div align="center">
<img src="docs/img/en/live-pills.png" width="860" alt="Pill states: the liquid island with the time and the weather, the time and the battery charge, music, the computer's load and the headphones' charge, a timer with its label, the microphone and the camera in use, voice to text, screen recording, a download, files on the shelf, a character, snow and a garland">
</div>

Events show up on their own and fold away a moment later:

<div align="center">
<img src="docs/img/en/live-cards.png" width="860" alt="Cards: reminder, a timer that has run out with its label, dictated text, screenshot, color picker, downloaded file, headphones running low, VPN">
</div>

Music with an equalizer and the song's words · dictation with a voice meter · reminders and a timer · downloads,
not only from the browser · Steam downloads · microphone and camera dots with a mute button · volume by mouse
wheel · keyboard layout and Caps Lock · the charge of Bluetooth headphones, mice and keyboards · the computer's
load · Windows notifications · VPN with country and IP · screen recording · OBS recording and stream · AI agents
at work (Claude Code, Codex, opencode) · updates.

The time sits in the middle of the folded island (with seconds, if you like), with the battery charge next to
it on a laptop and the weather at the ends. The keyboard layout, the number of the virtual desktop and the
computer's load can stand there too; when one end gets much wider than the other, the pill lines everything
up in one even row instead of leaving a gap.

If the island gets in the way of your browser's tabs, there are three ways out. Auto-hide: it leaves the
screen and comes back when the cursor rests at the very top edge above it, or on its hotkey. A list of
programs: it hides only while one of them is in front, and if you like, only when its window comes up to the
pill itself. The notch mode, as on a MacBook: a strip as tall as the pill stays behind the island, and
maximised windows start below it.

<div align="center">
<img src="docs/img/en/auto-hide.png" width="860" alt="Auto-hide: the island is hidden, the cursor at the edge of the screen, the island is out">
</div>

## Pick a character

Liquid island is the default. If you want company, 30 characters live in **Settings → Character**, each with a
live preview: Pixel, a tail, an island on legs, a jellyfish, a hamster wheel, a campfire, a lens, Newton's
cradle and more, and for the New Year a snowman, Father Frost, a bullfinch, a gingerbread man and a reindeer.
They react to music, to the AI thinking, to finished actions and alarms, their eyes follow the real cursor,
and they fall asleep when you are away. A character can be made bigger, and the liquid edge can stay under any
of them. The liquid island, Pixel, Spark and Eyes are free; the others come with [Island Pro](#island-pro).

<div align="center">
<img src="docs/img/en/characters.webp" width="812" alt="30 characters and every reaction of theirs: idle, music, the AI thinking, done, attention, a file, sleep">
</div>

## Weather

A forecast tab: the weather now over a sky that matches it, the next hours and a week ahead, and tiles as on an
iPhone: the wind, humidity, pressure, the sun, precipitation and the UV index. There can be several cities,
switched with one press. The temperature also sits on the folded island, and a card warns you about an hour
before rain or snow starts. When it rains outside, the liquid island drips a little.

<div align="center">
<img src="docs/img/en/tab-weather.png" width="760" alt="Weather tab: the weather now, the hours ahead, and tiles: wind, humidity, pressure, the sun, precipitation, the UV index">
</div>

The forecast comes from [MET Norway](https://www.met.no/en) with no key and no sign-up. You choose the cities
by name; they are never guessed from your network address. The weather is part of [Island Pro](#island-pro).

## Inside

<table>
<tr>
<td width="50%" valign="top">
<img src="docs/img/en/tab-clipboard.png" alt="Clipboard tab">
<b>Clipboard.</b> History of text and images with search and pins. A click pastes the entry into the window you were typing in; a copied picture also opens with a button of its own, and a text turns into a QR code. Screen recordings land here too: a click pastes the file, and it can be opened or shown in its folder.
</td>
<td width="50%" valign="top">
<img src="docs/img/en/tab-shelf.png" alt="Shelf tab with the phone">
<b>Shelf and phone.</b> Drop files on the island and they wait there until you drag them into the right window, one by one or all at once; the shelf shows where and when each came from. The phone connects by a QR code, with no app and no servers in between: photos, files and text from it land on the shelf and the clipboard, and files from the island go to the phone. Both need to be on the same home network.
</td>
</tr>
<tr>
<td valign="top">
<img src="docs/img/en/tab-text.png" alt="Text tab">
<b>Text.</b> Wrong keyboard layout, cases, transliteration, JSON, Base64, URL, QR codes, plus AI actions: translate, fix, shorten, explain, reply.
</td>
<td valign="top">
<img src="docs/img/en/tab-chat.png" alt="Chat tab">
<b>Chat.</b> A conversation with an AI that remembers the context. Attach pictures and documents (PDF, Word, Excel, PowerPoint, text): paste, drop or pick them, then ask. Dictate the message with the microphone button. With no key at all, the tab opens Gemini, DeepSeek and ChatGPT on their own sites: you only sign in.
</td>
</tr>
<tr>
<td valign="top">
<img src="docs/img/en/command-bar.png" alt="Command bar">
<b>Command bar.</b> Apps (those from the Store too), files and folders by name, recent files, a calculator, unit and currency conversion, web search, a question to the AI, “timer 30 min report”, “remind me to call mum at 7 pm”, “shut down in 30 minutes”, “brightness 50”, “qr …”; a line after “>” runs in cmd or PowerShell. A command can be spoken too. <code>Alt+Space</code>; <code>Ctrl+Enter</code> opens the folder of a program or a file, <code>Ctrl+Shift+Enter</code> starts a program as administrator.
</td>
<td valign="top">
<img src="docs/img/en/tab-note.png" alt="Note tab: formatting, folders, the timer and reminders">
<b>Note, timer and reminders.</b> A note that saves itself, with formatting (bold, italic, struck, marked with a colour, lists, numbered lists and tasks with ticks) and folders for tasks and ideas. Beside it are a timer (ready lengths or your own, and what it is for; it stays in the pill while it runs) and reminders typed as one phrase: “call mum tomorrow at 9”, “pills every day at 23:00”, “hand in the report on November 19 at 4 pm”. The time read from a phrase moves with buttons, and a reminder can be changed afterwards.
</td>
</tr>
<tr>
<td valign="top">
<img src="docs/img/en/tab-controls.png" alt="Controls tab">
<b>Controls.</b> Wi-Fi with its list of networks (or the wired network, if you prefer or the computer has no Wi-Fi), Bluetooth with its paired devices (their charge, and headphones and speakers connected in one press), the VPN (Happ, v2RayTun, Karing, Cloudflare WARP, Mullvad, Private Internet Access, Windscribe, OpenVPN, Windows' own connections, or a client of your own by its link or command) and the dark theme in one press. Below them, the computer's load (processor, memory, video card, network) and the brightness of the monitors; lock, sleep, restart and shut down, the last three asking to be pressed twice.
</td>
<td valign="top">
<img src="docs/img/en/command-controls.png" alt="System commands in the command bar">
<b>System commands.</b> The same from the command bar: “wifi”, “bluetooth”, “theme”, “lock”, “brightness 50”.
</td>
</tr>
</table>

### Tools

- **Screenshots** of an area or the whole screen, to the clipboard and to a folder, with markup: arrows, boxes, a marker, text, blur for private data. If you like, the markup goes right on the selection, as in Lightshot. The text of a screenshot is translated with one button.
- **Text from the screen (OCR).** Windows' Russian and English recognizers are merged line by line.
- **QR codes** from the screen and from any text, and a **color picker** with a magnifier and colour history.
- **Screen recording** to MP4 (H.264 through Media Foundation, 30 or 60 frames per second, normal or high quality, with the computer's sound and, if you like, the microphone) or GIF, into a folder of your choice.
- **Paste without formatting** on a hotkey.
- **The island's look.** A dark or a light theme, or whatever Windows uses (with a hotkey to switch), any colour, a size from 80 to 200%, the transparency of the folded and of the open island set on their own.
- **Your own Home.** Keep only what you need on it, one player for instance, and the island fits what is left; tabs you do not use leave the row.
- **The New Year on the island** (a Holidays page of its own): snow falling from under the pill, a cap of snow on it and a garland along its edge, on the days you choose or always; if you like, snow over the whole screen.
- **The island in screenshots and recordings.** By default screen captures leave it out; one setting shows it in screenshots, recordings and streams.
- **Volume.** The mouse wheel over the island, the volume of the player itself and of each program from Home. You can also choose whose volume the island controls and which microphone it mutes and records, when these are not the defaults of Windows: handy with a virtual mixer.
- **Voice to text.** Press the hotkey (or the button at the top of the open island), speak, press again: the text is on the clipboard (and, if you like, typed straight into the window you were in). A voice command sends what you said to the command bar and runs it.
- **Reminders and a timer** that show up as a card with a sound and wait until you answer them; reminders can repeat on the days you name.
- **A choice of player.** When more than one is open, a button in the player picks the one the island shows and controls. AIMP and Winamp show up too, though Windows knows nothing of them; a player you do not want on the island can be hidden.
- **Groups in the launcher.** Drag one shortcut onto another and the two become a group; a group opens above the row. The plus adds a link: a site, or a command of another program (`steam://run/…`); its icon is found by itself (the site's or the app's) or picked from a file, and a right click changes the link.
- **Hotkeys for shortcuts.** Any shortcut of the launcher, a link included, can have a hotkey of its own (Settings → Hotkeys).
- **Where the island stands.** On the monitor of your choice, moved along its top edge; with a taskbar at the top of the screen it stands under it. Over games and videos on the whole screen it hides, and its hotkeys still call it out.
- **The pill while music plays.** The usual one, a wider one with the track's name and a thin bar of its time, or a mini player: the cover, the track, the bar and the buttons right in the pill. A hotkey switches between them.
- **The song's words in time with the music.** In the mini player and in a pill of its own, the line being sung lights up. Free, turned on in the settings; the words come from the open [LRCLIB](https://lrclib.net/) base, only for the song that plays.
- **AI agents in a terminal** (Island Pro). Claude Code, Codex and opencode tell the island what they do: the pill shows that an agent is working, waits for an answer or is done, and a card comes with its question or the beginning of its answer. Claude Code and Codex can be answered right on the island: allow or deny a command, and with Claude Code, pick one of its choices. Connected in Settings with one press.
- **Through mode.** The folded island lets clicks through and does not open under the cursor: it is in sight and in nobody's way. The settings, a hotkey or the command bar turn the mode on and off.
- **The edge as an equaliser.** For the liquid island: with music the edge shows the sound by frequency, low on the left and high on the right.
- **A link to a screenshot.** A button on the screenshot's card uploads it to Imgur or ImgBB with a key of your own (nothing is uploaded until you choose a service) and copies the link.
- **Windows notifications.** Messages and notifications of other programs are shown on the island as a card with their icon; a click opens the program. Turned on in Settings, where the programs not to show are listed too.
- **AI** through any OpenAI-compatible API, through a proxy of your own if needed, with free services one click away.
- **Two languages.** Russian on Russian-speaking systems, English everywhere else; switch in Settings at any time.

Text from the screen, screen recording, voice to text and the AI are part of [Island Pro](#island-pro);
everything else here is free.

<div align="center">
<img src="docs/img/en/light.png" width="760" alt="The island in its light theme: the Home tab">
</div>

<div align="center">
<img src="docs/img/en/settings.png" width="860" alt="Settings: the list of pages at the left, the character gallery and the general options with the live island above them">
</div>

### Hotkeys

All of them can be changed in Settings.

| | |
|---|---|
| `Ctrl+Alt+I` | open or close the island |
| `Alt+Space` | command bar |
| `Ctrl+Alt+A` | AI chat |
| `Ctrl+Alt+D` | voice to text: start and finish |
| `Ctrl+Alt+V` | clipboard history |
| `Ctrl+Alt+S` / `Ctrl+Alt+Shift+S` | screenshot of an area / of the screen |
| `Ctrl+Alt+O` | text from the screen |
| `Ctrl+Alt+Q` | QR code from the screen |
| `Ctrl+Alt+C` | color picker |
| `Ctrl+Alt+R` | screen recording: start and stop |
| `Ctrl+Alt+Shift+V` | paste without formatting |
| `Ctrl+Alt+M` | microphone: mute and unmute |

The rest have no key until you give them one in the same place: through mode, auto-hide, the VPN, the island's
theme, the look of the pill with music, the voice command, the shortcuts of the launcher and more.

## Island Pro

Island is free, and most of it stays free for good: the live pill, clipboard history, the shelf and the
phone, text tools, the note with the timer and reminders, screenshots with markup, QR codes, the color picker,
the command bar, the control centre, the New Year's snow and garland, the liquid island and three characters
(Pixel, Spark and Eyes).

**Island Pro** is bought once and adds the rest:

- the other 26 characters, the New Year's ones too, and the liquid edge under any of them;
- the weather: the forecast tab, the temperature on the island, warnings about rain and snow;
- the AI (the chat, text actions, the translation of a screenshot, a question from the command bar) and voice to text, both with your own key from an AI service, free ones included; and Gemini, DeepSeek and ChatGPT on their own sites in the Chat tab, with no key;
- the voice command;
- screen recording and text from the screen;
- the status of AI agents in a terminal (Claude Code, Codex, opencode) on the island, and answering them from it.

For the first 14 days all of Pro is open, so you can try everything before you decide. After that the
free part keeps working, and nothing you saved is lost.

The key costs **$4.99**, never expires, is checked on your computer with no internet and works on all of
your own computers.

**[Buy Island Pro](https://islandapp.pro/?lang=en#isl-pro)**, then paste the key into **Settings → Island Pro**.

Like the project? You can **[support its development](https://app.lava.top/3871177473?tabId=donate)** with any sum.
Visa, Mastercard, Apple Pay and PayPal are accepted.

<div align="center">
<img src="docs/img/en/settings-pro.png" width="620" alt="Settings: the Island Pro block with the trial, the Buy button and the field for the key">
</div>

## Install

Download the latest `Island_x.y.z_x64-setup.exe` from
[**Releases**](https://github.com/exuupery/island/releases/latest) and run it.
Windows 10 or 11, 64-bit.

Island updates itself: it checks for a new version at startup and every 6 hours, shows an “Update” card,
downloads the signed installer and restarts. What a new version brings is in **Settings → Updates**, with
short clips of the main points.

### AI

Island ships without any key: you bring your own, and it stays on your computer. **Settings → AI** has
ready-made services, so it takes a minute and can cost nothing:

| Service | Free tier | Pictures | Dictation with the same key |
|---|---|---|---|
| [Groq](https://console.groq.com/keys) | about 1000 requests a day, no card | yes, up to three per message | yes: Whisper, up to 8 hours of speech a day |
| [Google Gemini](https://aistudio.google.com/apikey) | free tier of AI Studio | yes | yes |
| [OpenRouter](https://openrouter.ai/keys) | 50 requests a day on free models | yes | no |
| [DeepSeek](https://platform.deepseek.com/api_keys) | paid | yes | no |
| OmniRoute | your own gateway on this computer | as its models allow | no |

Pick one, press “Get a key”, paste the key, press “Test”. Any other OpenAI-compatible address works too.
These three services do not answer requests from Russia; there they need a VPN. A VPN that works only as a
proxy can be given to the AI alone: Settings has a field for a SOCKS5 or HTTP proxy.

No key at all? Gemini, DeepSeek and ChatGPT open on their own sites right in the Chat tab: you only sign in.

<div align="center">
<img src="docs/img/en/settings-ai.png" width="860" alt="Settings: the AI sites with no key, AI services with free options, and voice to text">
</div>

The AI lives in three places: the buttons on the Text tab, a question from the command bar (`Tab`), and the
Chat tab. An answer from the command bar continues in the chat with `Ctrl+Enter`.

In the chat, pictures are scaled down and sent to the model as images; documents are read on your computer
and sent as text (a scanned PDF has no text: attach a screenshot of the page instead).

## Privacy

Island works on your computer and keeps its data there.

- Clipboard history, the shelf, the note and the chat are stored in a local SQLite database. Copies from password managers that mark them as private are never recorded; you can add your own list of apps to skip.
- Keys are encrypted by Windows (DPAPI) for the current user and leave the computer only in requests to the service they were issued for. No key is built into the app.
- The Island Pro key is checked on your computer and is not sent anywhere.
- What you dictate and what you attach in the chat goes to the service you chose, and nowhere else. A recording is not kept after it is recognised.
- The sites of Gemini, DeepSeek and ChatGPT in the Chat tab are those sites themselves: what you write there and your sign-in are between you and them. The island's commands are closed to them.
- The phone talks to the island directly, over your home network and only while the link is on; nothing goes through anybody's server. Like an ordinary http site, the link is not encrypted, so use it on your own network.
- What AI agents tell the island goes to it on this very computer and is kept nowhere. To connect them, the island adds its own lines to their settings (the hooks of Claude Code and Codex, a plugin for opencode), and a copy of the file is kept beside it.
- Notifications of other programs are read from Windows only when you turn that on; they are shown and kept nowhere. The names of your files, by which the command bar finds them, are held in memory only.
- Network requests, all of them optional or obvious: the AI endpoint you set up (through your proxy, if you gave one), the update check on GitHub and its clips of what is new, the forecast for the cities you chose (api.met.no; only their coordinates are sent), the city search when you look one up (nominatim.openstreetmap.org; what you typed), the song's words while they are turned on (lrclib.net; the name, the artist and the length of the song that plays), Bank of Russia exchange rates for the currency converter (cbr-xml-daily.ru), a country/IP lookup for the VPN chip (ipwho.is; can be switched off), the site of a link you add to the launcher, for its icon (only that site, only while the icon is found by itself), Imgur or ImgBB when you upload a screenshot, and OBS on this very computer (127.0.0.1) when you turn its status on.
- By default the island stays out of screenshots, screen recordings and streams; one setting shows it there.

## Limitations

- Paste on click does not work in windows running as administrator (Windows protects them). The entry still lands on the clipboard.
- Nothing can be drawn over games in exclusive full-screen mode, so the island hides there.
- The brightness is set only for monitors that take it over the cable (DDC/CI); a laptop's screen has its own slider in Windows' quick settings.
- Windows only.

## Data

The forecast is from [MET Norway](https://www.met.no/en) (CC BY 4.0), the city search from [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors (ODbL), time zones from [GeoNames](https://www.geonames.org/) (CC BY 4.0), the song's words from [LRCLIB](https://lrclib.net/).

</details>

<details open>
<summary><b>Русский</b></summary>
<br>

<div align="center">

Жидкая чёрная пилюля вверху экрана: показывает, что происходит прямо сейчас,<br>
и раскрывается в набор инструментов, когда к ней тянешься.

<img src="docs/img/ru/hero.png" width="860" alt="Island раскрыт на вкладке «Главная»: плеер, громкость, быстрые действия, лаунчер">

</div>

## Что это

Island висит поверх всех окон, по центру верхнего края. В свёрнутом виде это маленькая пилюля, которая
сообщает о музыке, загрузках, микрофоне, записи экрана. Задержи на ней курсор или упрись им в верхний
край, и она раскроется в панель: история буфера, полка для файлов, инструменты для текста, чат с ИИ,
скриншоты, командная строка, погода и центр управления.

Остров не забирает фокус у окна, в котором ты печатаешь. Поэтому клик по записи из буфера вставляет её
ровно туда, где стоит курсор.

<div align="center">
<img src="docs/img/demo-ru.webp" width="760" alt="«Глазки» просыпаются и здороваются; остров тянется к курсору, играет музыку, раскрывается по наведению и показывает все вкладки: «Главную», буфер, полку, текст, чат с ИИ, заметку, погоду, центр управления; дальше командная строка, загрузка, нагрузка ПК, автоскрытие, персонажи, Новый год и светлая тема">
</div>

## Пилюля живая

Сам остров сделан из магнитной жидкости. Нижний край тянется к курсору, под музыку идёт шипами в цвет
обложки, от хороших новостей роняет каплю, а когда тебя нет, устало провисает.

<div align="center">
<img src="docs/img/ru/live-pills.png" width="860" alt="Состояния пилюли: жидкий остров с часами и погодой, часы и заряд батареи, музыка, нагрузка компьютера и заряд наушников, таймер с подписью, занятые микрофон и камера, голос в текст, запись экрана, загрузка, файлы на полке, персонаж, снег и гирлянда">
</div>

События появляются сами и через мгновение сворачиваются:

<div align="center">
<img src="docs/img/ru/live-cards.png" width="860" alt="Карточки: напоминание, таймер с подписью, надиктованный текст, скриншот, пипетка, готовая загрузка, наушники садятся, VPN">
</div>

Музыка с эквалайзером и текстом песни · диктовка с индикатором голоса · напоминания и таймер · загрузки не только
из браузера · загрузки Steam · точки микрофона и камеры с кнопкой отключения · громкость колесом мыши · раскладка
и Caps Lock · заряд Bluetooth-наушников, мышей и клавиатур · нагрузка компьютера · уведомления Windows · VPN со
страной и IP · запись экрана · запись и трансляция OBS · работа ИИ-агентов (Claude Code, Codex, opencode) · обновления.

Посередине свёрнутого острова стоит время (по желанию с секундами), на ноутбуке рядом с ним заряд батареи, а
по краям погода. Туда же можно добавить раскладку клавиатуры, номер виртуального рабочего стола и нагрузку
компьютера; когда один край становится намного шире другого, пилюля выстраивает всё одной ровной строкой и не
оставляет пустого места.

А если остров закрывает вкладки браузера, есть три выхода. Автоскрытие: он уйдёт за край экрана и вернётся,
когда задержишь курсор у самого верхнего края над ним, или по своей клавише. Список программ: остров прячется,
только пока впереди одна из них, а если хочешь, только когда её окно подходит к самой пилюле. Режим выреза, как
на MacBook: полоса высотой с пилюлю остаётся за островом, и развёрнутые окна начинаются под ней.

<div align="center">
<img src="docs/img/ru/auto-hide.png" width="860" alt="Автоскрытие: остров спрятан, курсор у края экрана, остров вышел">
</div>

## Выбери персонажа

По умолчанию стоит жидкий остров. Если хочется компании, в разделе **Настройки → «Персонаж»** живут
30 персонажей, каждый с живым превью: Пиксель, хвост, остров на ножках, медуза, хомяк в колесе, костёр,
объектив, маятник Ньютона и другие, а к Новому году Снеговик, Дед Мороз, Снегирь, Пряник и Олень. Они
реагируют на музыку, на размышления ИИ, на готовые действия и тревогу, следят глазами за настоящим курсором и
засыпают, когда тебя нет. Персонажа можно сделать крупнее, а жидкий край оставить под любым из них. Жидкий
остров, Пиксель, Искра и Глазки бесплатные, остальные входят в [Island Pro](#island-pro-1).

<div align="center">
<img src="docs/img/ru/characters.webp" width="812" alt="30 персонажей и все их реакции: покой, музыка, ИИ думает, готово, внимание, файл, сон">
</div>

## Погода

Вкладка с прогнозом: погода сейчас на фоне неба, которое ей соответствует, ближайшие часы и неделя вперёд, а
рядом плитки, как на iPhone: ветер, влажность, давление, солнце, осадки и УФ-индекс. Городов может быть
несколько, они переключаются одним нажатием. Температура видна и на свёрнутом острове, а примерно за час до
дождя или снега появляется карточка-предупреждение. Когда на улице дождь, жидкий остров слегка капает.

<div align="center">
<img src="docs/img/ru/tab-weather.png" width="760" alt="Вкладка «Погода»: погода сейчас, по часам и плитки: ветер, влажность, давление, солнце, осадки, УФ-индекс">
</div>

Прогноз берётся у [MET Norway](https://www.met.no/en) без ключа и регистрации. Города выбираются по названию;
по адресу в сети они не определяются. Погода входит в [Island Pro](#island-pro-1).

## Что внутри

<table>
<tr>
<td width="50%" valign="top">
<img src="docs/img/ru/tab-clipboard.png" alt="Вкладка «Буфер»">
<b>Буфер.</b> История текста и картинок с поиском и закреплением. Клик вставляет запись в окно, где ты печатал; скопированную картинку можно ещё и открыть своей кнопкой, а из текста сделать QR-код. Записи экрана попадают сюда же: клик вставляет файл, его можно открыть или показать в папке.
</td>
<td width="50%" valign="top">
<img src="docs/img/ru/tab-shelf.png" alt="Вкладка «Полка» с телефоном">
<b>Полка и телефон.</b> Брось файлы на остров, и они подождут там, пока ты не вытащишь их в нужное окно: по одному или все сразу; на полке видно, откуда и когда пришёл каждый. Телефон подключается по QR-коду, без приложения и чужих серверов: фото, файлы и текст с него ложатся на полку и в буфер, а файлы с острова уходят на телефон. Нужна одна домашняя сеть.
</td>
</tr>
<tr>
<td valign="top">
<img src="docs/img/ru/tab-text.png" alt="Вкладка «Текст»">
<b>Текст.</b> Не та раскладка, регистры, транслит, JSON, Base64, URL, QR-коды и действия ИИ: перевести, исправить, сократить, объяснить, ответить.
</td>
<td valign="top">
<img src="docs/img/ru/tab-chat.png" alt="Вкладка «Чат»">
<b>Чат.</b> Диалог с ИИ, который помнит контекст. К сообщению можно приложить картинки и документы (PDF, Word, Excel, PowerPoint, текст): вставь, перетащи или выбери, а потом спрашивай. Сообщение можно надиктовать кнопкой с микрофоном. А если ключа нет совсем, во вкладке открываются Gemini, DeepSeek и ChatGPT на их собственных сайтах: нужен только вход в аккаунт.
</td>
</tr>
<tr>
<td valign="top">
<img src="docs/img/ru/command-bar.png" alt="Командная строка">
<b>Командная строка.</b> Программы (и те, что из Магазина), файлы и папки по имени, недавние файлы, калькулятор, перевод единиц и валют, поиск в интернете, вопрос ИИ, «таймер 30 мин отчёт», «напомни позвонить маме завтра в 9», «выключи компьютер через 30 минут», «яркость 50», «qr …»; строка после «>» выполняется в cmd или PowerShell. Команду можно и сказать голосом. <code>Alt+Space</code>; <code>Ctrl+Enter</code> открывает папку программы или файла, <code>Ctrl+Shift+Enter</code> запускает программу от имени администратора.
</td>
<td valign="top">
<img src="docs/img/ru/tab-note.png" alt="Вкладка «Заметка»: форматирование, папки, таймер и напоминания">
<b>Заметка, таймер и напоминания.</b> Заметка, которая сохраняется сама, с форматированием (жирный, курсив, зачёркнутый, выделение цветом, списки, нумерованные списки и задачи с галочками) и папками для задач и идей. Рядом с ней таймер (готовые отрезки или своё время и подпись, на что он; пока идёт, он виден в пилюле) и напоминания одной фразой: «позвонить маме завтра в 9», «таблетки каждый день в 23:00», «сдать отчёт 19 ноября в 16». Прочитанное время сдвигается кнопками, а напоминание можно изменить и после.
</td>
</tr>
<tr>
<td valign="top">
<img src="docs/img/ru/tab-controls.png" alt="Вкладка «Управление»">
<b>Управление.</b> Wi-Fi со списком сетей (или проводная сеть: по выбору или там, где Wi-Fi нет), Bluetooth со списком устройств (заряд, а наушники и колонки подключаются в одно нажатие), VPN (Happ, v2RayTun, Karing, Cloudflare WARP, Mullvad, Private Internet Access, Windscribe, OpenVPN, подключения самой Windows или свой клиент по его ссылке или команде) и тёмная тема одним нажатием. Под ними нагрузка компьютера (процессор, память, видеокарта, сеть) и яркость мониторов; блокировка, сон, перезагрузка и выключение. Три последних просят нажать дважды.
</td>
<td valign="top">
<img src="docs/img/ru/command-controls.png" alt="Системные команды в командной строке">
<b>Команды системы.</b> То же самое из командной строки: «wifi», «bluetooth», «тема», «заблокировать», «яркость 50».
</td>
</tr>
</table>

### Инструменты

- **Скриншоты** области и всего экрана, в буфер и в папку, с разметкой: стрелки, рамки, маркер, текст, размытие личных данных. Если хочешь, размечать можно прямо на выделении, как в Lightshot. Текст со скриншота переводится одной кнопкой.
- **Текст с экрана (OCR).** Русский и английский распознаватели Windows склеиваются построчно.
- **QR-коды** с экрана и из любого текста, и **пипетка** с лупой и историей цветов.
- **Запись экрана** в MP4 (H.264 через Media Foundation, 30 или 60 кадров в секунду, обычное или высокое качество, со звуком компьютера и, по желанию, микрофона) или GIF, в папку по твоему выбору.
- **Вставка без форматирования** по горячей клавише.
- **Вид острова.** Тёмная или светлая тема или как в Windows (и клавиша, чтобы переключать), любой цвет, размер от 80 до 200 %, прозрачность свёрнутого и раскрытого острова отдельно.
- **Своя «Главная».** Оставь на ней только нужное, например один плеер, и остров подстроится под то, что осталось; ненужные вкладки уходят из ряда.
- **Новый год на острове** (свой раздел «Праздники»): снег из-под пилюли, шапка снега на ней и гирлянда по краю, в выбранные дни или всегда; по желанию снег идёт по всему экрану.
- **Остров на скриншотах и в записи.** По умолчанию в захват экрана он не попадает; одна настройка показывает его на скриншотах, в записи и на трансляциях.
- **Громкость.** Колесо мыши над островом, громкость самого плеера и каждой программы на «Главной». Ещё можно выбрать, чью громкость регулирует остров и какой микрофон он выключает и записывает, если это не устройства Windows по умолчанию: удобно с виртуальным микшером.
- **Голос в текст.** Нажми сочетание (или кнопку вверху раскрытого острова), скажи, нажми ещё раз: текст в буфере (а если хочешь, сразу в окне, где стоял курсор). Голосовая команда отправляет сказанное в командную строку и выполняет его.
- **Напоминания и таймер**: появляются карточкой со звуком и ждут, пока на них не ответят; напоминания могут повторяться по тем дням, которые назовёшь.
- **Выбор плеера.** Когда их открыто несколько, кнопка в плеере выбирает, какой из них остров показывает и каким управляет. AIMP и Winamp тоже видны, хотя Windows о них не знает; плеер, которому не место на острове, можно скрыть.
- **Группы в лаунчере.** Перетащи один ярлык на другой, и они станут группой; группа раскрывается над рядом ярлыков. Плюс добавляет ссылку: сайт или команду другой программы (`steam://run/…`); значок подтягивается сам (сайта или программы) или берётся из файла, а правый клик по ссылке её меняет.
- **Клавиши для ярлыков.** Любому ярлыку лаунчера, и ссылке тоже, можно дать свою горячую клавишу (Настройки → Клавиши).
- **Где стоит остров.** На выбранном мониторе, со сдвигом вдоль его верхнего края; с панелью задач вверху экрана он встаёт под неё. Над играми и видео на весь экран он прячется, а клавиши острова по-прежнему вызывают его.
- **Пилюля во время музыки.** Обычная, пошире с названием трека и тонкой полосой времени или мини-плеер: обложка, трек, полоса и кнопки прямо в пилюле. Своя клавиша переключает вид.
- **Текст песни в такт музыке.** В мини-плеере и в своей пилюле подсвечивается строка, которая звучит сейчас. Бесплатно, включается в настройках; тексты — из открытой базы [LRCLIB](https://lrclib.net/), только для играющей песни.
- **ИИ-агенты в терминале** (Island Pro). Claude Code, Codex и opencode сообщают острову, что делают: в пилюле видно, что агент работает, ждёт ответа или закончил, а карточка приходит с его вопросом или началом ответа. Claude Code и Codex можно ответить прямо на острове: разрешить или запретить команду, а у Claude Code ещё и выбрать один из его вариантов. Подключаются в настройках одним нажатием.
- **Сквозной режим.** Свёрнутый остров пропускает клики и не раскрывается под курсором: он на виду и ничему не мешает. Включается и выключается в настройках, клавишей или из командной строки.
- **Край-эквалайзер.** У жидкого острова: при музыке край показывает звук по частотам, слева низкие, справа высокие.
- **Ссылка на скриншот.** Кнопка на карточке скриншота загружает его на Imgur или ImgBB со своим ключом (пока сервис не выбран, ничего не загружается) и копирует ссылку.
- **Уведомления Windows.** Сообщения и уведомления других программ показываются на острове карточкой со своим значком; нажатие открывает программу. Включается в настройках, там же список программ, которые показывать не нужно.
- **ИИ** через любой OpenAI-совместимый API, при необходимости через свой прокси; бесплатные сервисы подключаются в один клик.
- **Два языка.** Русский на русскоязычных системах, английский на остальных; переключается в настройках в любой момент.

Текст с экрана, запись экрана, голос в текст и ИИ входят в [Island Pro](#island-pro-1); всё остальное
здесь бесплатно.

<div align="center">
<img src="docs/img/ru/light.png" width="760" alt="Остров в светлой теме: вкладка «Главная»">
</div>

<div align="center">
<img src="docs/img/ru/settings.png" width="860" alt="Настройки: список страниц слева, галерея персонажей и общие параметры с живым островом над ними">
</div>

### Горячие клавиши

Все меняются в настройках.

| | |
|---|---|
| `Ctrl+Alt+I` | открыть или закрыть остров |
| `Alt+Space` | командная строка |
| `Ctrl+Alt+A` | чат с ИИ |
| `Ctrl+Alt+D` | голос в текст: начать и закончить |
| `Ctrl+Alt+V` | история буфера |
| `Ctrl+Alt+S` / `Ctrl+Alt+Shift+S` | скриншот области / экрана |
| `Ctrl+Alt+O` | текст с экрана |
| `Ctrl+Alt+Q` | QR-код с экрана |
| `Ctrl+Alt+C` | пипетка |
| `Ctrl+Alt+R` | запись экрана: начать и остановить |
| `Ctrl+Alt+Shift+V` | вставить без форматирования |
| `Ctrl+Alt+M` | микрофон: выключить и включить |

Остальным действиям клавиша назначается там же: сквозной режим, автоскрытие, VPN, тема острова, вид пилюли с
музыкой, голосовая команда, ярлыки лаунчера и другие.

## Island Pro

Island бесплатный, и большая его часть остаётся бесплатной навсегда: живая пилюля, история буфера, полка и
телефон, инструменты для текста, заметка с таймером и напоминаниями, скриншоты с разметкой, QR-коды, пипетка,
командная строка, центр управления, новогодний снег и гирлянда, жидкий остров и три персонажа (Пиксель, Искра
и Глазки).

**Island Pro** покупается один раз и добавляет остальное:

- остальных 26 персонажей, новогодних тоже, и жидкий край под любым из них;
- погоду: вкладку с прогнозом, температуру на острове, предупреждения о дожде и снеге;
- ИИ (чат, действия с текстом, перевод со скриншота, вопрос из командной строки) и голос в текст — со своим ключом сервиса ИИ, в том числе бесплатного; а Gemini, DeepSeek и ChatGPT на их сайтах во вкладке «Чат» — без ключа;
- голосовую команду;
- запись экрана и текст с экрана;
- статус ИИ-агентов в терминале (Claude Code, Codex, opencode) на острове и ответы им с острова.

Первые 14 дней весь Pro открыт, так что всё можно попробовать до покупки. Потом бесплатная часть
продолжает работать, и ничего из сохранённого не пропадает.

Ключ стоит **399 ₽**, бессрочный, проверяется на твоём компьютере без интернета и подходит для всех
своих компьютеров.

**[Купить Island Pro](https://islandapp.pro/?lang=ru#isl-pro)**, потом вставь ключ в **Настройки → Island Pro**.

Нравится проект? Его развитие можно **[поддержать](https://app.lava.top/3871177473?tabId=donate)** любой суммой.
Оплата картой или через СБП.

<div align="center">
<img src="docs/img/ru/settings-pro.png" width="620" alt="Настройки: блок Island Pro с пробой, кнопкой «Купить» и полем для ключа">
</div>

## Установка

Скачай свежий `Island_x.y.z_x64-setup.exe` из
[**Releases**](https://github.com/exuupery/island/releases/latest) и запусти.
Нужна Windows 10 или 11, 64-разрядная.

Island обновляется сам: проверяет новую версию при запуске и раз в 6 часов, показывает карточку
«Обновить», скачивает подписанный установщик и перезапускается. Что нового в версии, видно в **Настройки →
«Обновления»**, с короткими роликами о главном.

### ИИ

В Island не вшит ни один ключ: каждый подключает свой, и он остаётся на его компьютере. В разделе
**Настройки → «ИИ»** есть готовые сервисы, так что это занимает минуту и может ничего не стоить:

| Сервис | Бесплатно | Картинки | Диктовка тем же ключом |
|---|---|---|---|
| [Groq](https://console.groq.com/keys) | около 1000 запросов в день, без карты | да, до трёх в сообщении | да: Whisper, до 8 часов речи в день |
| [Google Gemini](https://aistudio.google.com/apikey) | бесплатный тариф AI Studio | да | да |
| [OpenRouter](https://openrouter.ai/keys) | 50 запросов в день на бесплатных моделях | да | нет |
| APINET | платно, в рублях | да | — |
| [DeepSeek](https://platform.deepseek.com/api_keys) | платно, российские карты не принимает | да | — |
| [Polza.ai](https://polza.ai) | платно, в рублях | да | — |
| OmniRoute | свой шлюз на этом компьютере | как у его моделей | — |

Выбери сервис, нажми «Получить ключ», вставь ключ, нажми «Проверить». Подойдёт и любой другой
OpenAI-совместимый адрес. Groq, Gemini и OpenRouter не отвечают на запросы из России: с ними нужен VPN.
APINET, DeepSeek и Polza.ai отвечают без него. А если VPN работает только как прокси, его можно дать одному
ИИ: в настройках есть поле для прокси SOCKS5 или HTTP.

Ключа нет совсем? Gemini, DeepSeek и ChatGPT открываются на своих сайтах прямо во вкладке «Чат»: нужен только
вход в аккаунт.

<div align="center">
<img src="docs/img/ru/settings-ai.png" width="860" alt="Настройки: сайты ИИ без ключа, сервисы ИИ с бесплатными вариантами и голос в текст">
</div>

ИИ работает в трёх местах: кнопки на вкладке «Текст», вопрос из командной строки (`Tab`) и вкладка «Чат».
Ответ из командной строки продолжается в чате по `Ctrl+Enter`.

В чате картинки уменьшаются и уходят модели как изображения; документы читаются на твоём компьютере и
уходят текстом (в отсканированном PDF текста нет: приложи вместо него снимок страницы).

## Приватность

Island работает на твоём компьютере и хранит данные там же.

- История буфера, полка, заметка и чат лежат в локальной базе SQLite. Копии из менеджеров паролей, которые помечают их как приватные, не записываются никогда; свой список программ-исключений можно добавить в настройках.
- Ключи шифруются Windows (DPAPI) для текущего пользователя и покидают компьютер только в запросах к тому сервису, для которого выданы. В программу не вшит ни один ключ.
- Ключ Island Pro проверяется на твоём компьютере и никуда не отправляется.
- То, что ты диктуешь и прикладываешь в чате, уходит в выбранный тобой сервис и больше никуда. Запись голоса после распознавания не хранится.
- Сайты Gemini, DeepSeek и ChatGPT во вкладке «Чат» — это сами эти сайты: что ты там пишешь и вход в аккаунт остаются между тобой и ими. Команды острова им закрыты.
- Телефон говорит с островом напрямую, через твою домашнюю сеть и только пока связь включена; ничьи серверы между ними не стоят. Как обычный сайт по http, эта связь не шифруется: пользуйся ею в своей сети.
- То, что сообщают ИИ-агенты, приходит острову на этом же компьютере и нигде не сохраняется. Чтобы их подключить, остров дописывает свои строки в их настройки (хуки Claude Code и Codex, плагин opencode), копия файла остаётся рядом.
- Уведомления других программ остров читает у Windows, только когда ты это включил; он их показывает и нигде не сохраняет. Имена твоих файлов, по которым их находит командная строка, держатся только в памяти.
- Сетевые запросы, все необязательные или очевидные: настроенный тобой адрес ИИ (через твой прокси, если он задан), проверка обновлений на GitHub и ролики о новом, прогноз для выбранных городов (api.met.no; уходят только их координаты), поиск города, когда ты его ищешь (nominatim.openstreetmap.org; уходит набранное название), текст песни, пока он включён (lrclib.net; название, исполнитель и длина играющей песни), курсы ЦБ для конвертера валют (cbr-xml-daily.ru), определение страны и IP для значка VPN (ipwho.is; отключается), сайт ссылки, которую ты добавил в лаунчер, ради её значка (только этот сайт и только пока значок подтягивается сам), Imgur или ImgBB, когда ты загружаешь скриншот, и OBS на этом же компьютере (127.0.0.1), если включить его статус.
- По умолчанию остров не попадает на скриншоты, в запись экрана и на трансляции; показать его там можно одной настройкой.

## Ограничения

- Вставка кликом не работает в окнах, запущенных от администратора (защита Windows). Запись при этом остаётся в буфере.
- Над играми в эксклюзивном полноэкранном режиме ничего не рисуется, поэтому остров там прячется.
- Яркость меняется только у мониторов, которые принимают её по кабелю (DDC/CI); у экрана ноутбука свой ползунок в быстрых настройках Windows.
- Только Windows.

## Данные

Прогноз — [MET Norway](https://www.met.no/en) (CC BY 4.0), поиск городов — участники [OpenStreetMap](https://www.openstreetmap.org/copyright) (ODbL), часовые пояса — [GeoNames](https://www.geonames.org/) (CC BY 4.0), тексты песен — [LRCLIB](https://lrclib.net/).

</details>
