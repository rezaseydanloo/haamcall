# Ham Call

A secure, browser-based communication experience built for instant rooms, clear calls, and frictionless collaboration.

## معرفی محصول (فارسی)
**هم کال ** یک راهکار تماس آنلاین سریع و ساده است که برای شروع فوری جلسه طراحی شده است.  
کاربر فقط با ساخت یک اتاق و ارسال یک لینک می‌تواند دیگران را دعوت کند و بدون نصب ابزار اضافی، گفت‌وگو را آغاز کند.

هم کال  برای این ساخته شده که ارتباط تیم‌ها، مدرس‌ها، مشاورها و کاربران عادی سریع‌تر و روان‌تر باشد؛ با تمرکز روی تجربه کاربری ساده، ارتباط پایدار و حس حرفه‌ای در مکالمه.

### مزیت‌های کلیدی
- ورود سریع به اتاق با لینک یا شناسه
- تماس صوتی و تصویری بلادرنگ
- چت متنی در کنار تماس
- اشتراک‌گذاری صفحه برای ارائه، آموزش یا پشتیبانی
- نمایش وضعیت شرکت‌کنندگان (آنلاین بودن، میکروفون و دوربین)
- تجربه مناسب در موبایل و دسکتاپ

### امنیت و پایداری ارتباط
- ارتباطات با لایه‌های امن انتقال داده انجام می‌شود.
- معماری ارتباطی بر پایه **WebRTC** با رویکرد **P2P-first** طراحی شده است.
- هماهنگی نشست و پیام‌رسانی بلادرنگ از طریق **WebSocket signaling** انجام می‌شود.
- برای شبکه‌های سخت، از مکانیزم‌های **STUN/TURN** و حالت relay پشتیبانی می‌شود تا تماس‌ها در شرایط پیچیده NAT و Firewall نیز پایدار بمانند.

### فناوری‌ها و زبان‌های استفاده‌شده
- زبان اصلی توسعه: **JavaScript** (سمت کاربر و سمت سرور)
- بک‌اند: **Node.js** + **Express**
- ارتباط بلادرنگ و سیگنالینگ: **Socket.IO** (بر پایه WebSocket)
- موتور تماس صوتی/تصویری: **WebRTC** با الگوی **P2P-first**
- مدیریت ارتباط همتا: **PeerJS / PeerServer**
- فرانت‌اند: **EJS**, **HTML5**, **CSS3**, **Vanilla JavaScript**
- سازگاری شبکه: **ICE + STUN/TURN** برای پایداری بهتر در اینترنت‌های دشوار

### مناسب برای چه سناریوهایی؟
- جلسات سریع تیمی
- کلاس و آموزش آنلاین
- مشاوره و گفت‌وگوی راه دور
- دمو و پشتیبانی محصول با اشتراک صفحه

## Product Overview (English)
**Ham Call** is a fast and lightweight online calling experience designed for instant room-based communication.  
Users can create a room, share one link, and start collaborating immediately without extra installation.

The product is built to make communication simple, reliable, and professional for teams, educators, consultants, and everyday users.

### Core Benefits
- Quick room access by link or room ID
- Real-time audio and video communication
- Built-in text chat during calls
- Screen sharing for demos, support, and teaching
- Live participant visibility (presence, mic, and camera state)
- Smooth experience across desktop and mobile

### Security & Network Reliability
- Communication channels use secure transport layers.
- **WebRTC** powers low-latency media with a **P2P-first** approach.
- Real-time coordination is handled through **WebSocket signaling**.
- **STUN/TURN** support and relay-capable behavior improve reliability under difficult network conditions, including complex NAT and restrictive firewalls.

### Built With
- Primary language: **JavaScript** (frontend and backend)
- Backend: **Node.js** + **Express**
- Real-time signaling/events: **Socket.IO** (WebSocket-based)
- Audio/video engine: **WebRTC** with a **P2P-first** model
- Peer session layer: **PeerJS / PeerServer**
- Frontend stack: **EJS**, **HTML5**, **CSS3**, **Vanilla JavaScript**
- Network resilience: **ICE + STUN/TURN** for stronger connectivity under hard network conditions

### Ideal Use Cases
- Team sync meetings
- Online tutoring and learning
- Remote consulting sessions
- Product walkthroughs and support calls

## License
ISC
