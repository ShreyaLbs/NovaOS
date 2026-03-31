NovaOS 98 — Nova Tech Fest Event Website

A retro Windows 98-styled hackathon event website built with pure HTML, CSS, and JavaScript.

OUTPUT:  
<img width="1920" height="1080" alt="Screenshot (665)" src="https://github.com/user-attachments/assets/c67e7ee2-97f9-403b-96a9-5d59fd74c662" />
<img width="1920" height="1080" alt="Screenshot (666)" src="https://github.com/user-attachments/assets/f1d65dd7-22fa-4d8a-ab16-ce1d24e1cb13" />
<img width="1920" height="1080" alt="Screenshot (669)" src="https://github.com/user-attachments/assets/85b6d275-77a2-4125-98ce-473a961f2c48" />
<img width="1920" height="1080" alt="Screenshot (668)" src="https://github.com/user-attachments/assets/be0e19ec-b497-4e81-92da-519f9d5f12b1" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/23432931-b4be-4fc1-957c-6f991cea69b7" />

Live Demo: 
```bash
shreyalbs.github.io/NovaOS/
```

Overview   
NovaOS 98 is a fully interactive Windows 98 desktop simulation built as an event website for Nova Tech Fest 1998 — a fictional retro hackathon. Every detail is designed to feel authentic to the late 90s computing era, from the CRT scanline overlay to the chunky inset window borders.

Pages  
Desktop — novaos-index.html 
The main OS desktop experience: 

Boot sequence — green-on-black terminal with progress bar, live % counter, and BIOS-style hardware log lines  
6 desktop icons — double-click any to open a window (touch-friendly too) 
3 draggable windows — About NovaFest, Events & Schedule, Register Now 
Authentic Win98 windows — inset borders, title bar gradients, minimize/close buttons, menu bars 
Live taskbar clock + Start Menu with sidebar 
CRT scanlines + vignette overlay across the entire page 
Shut Down easter egg in the Start Menu 

Help Viewer — novaos-about.html 
Styled exactly like a Windows 98 Help viewer: 

Sidebar TOC with scroll spy — active section highlights as you scroll  
6 content sections — Welcome, Features grid, Hackathon rules & prizes, Workshops schedule, Keynotes, Pass types, FAQ, Sponsors, Contact 
FAQ accordion — click to expand, others auto-close 
Tip / Note / Warning boxes in classic yellow, blue, and orange  
Toolbar with Back, Home, Print, and Register Now buttons   


Features:
 ->Boot animation with a progress bar, live percentage counter, and BIOS-style hardware log   
 ->Draggable windows with full mouse and touch support  
 ->Window focus system where the active window gets a blue gradient title bar and inactive ones go grey  
 ->Live taskbar clock that updates every second 
 ->Start Menu with app shortcuts and a working Shut Down easter egg 
 ->CRT scanline effect and radial vignette overlay across the entire page 
 ->Notepad-style registration form with a success dialog popup  
 ->Scroll spy TOC that auto-highlights the current section while scrolling  
 ->FAQ accordion with smooth open/close and arrow rotation animation  
 ->Fully mobile responsive layout for phones and tablets  


🛠️ Tech Stack 
HTML5 — page structure and semantics 
CSS3 — all styling, animations, and layout using Grid and Flexbox  
Vanilla JavaScript — interactivity, drag & drop, and DOM manipulation 
Google Fonts — VT323 for the pixel display font and Share Tech Mono for system UI text 

Project Structure
NovaOS/
├── index.html          ← Entry point (redirects to desktop)
├── novaos-index.html   ← Main desktop page
└── novaos-about.html   ← Help viewer page

Getting Started 
View locally 

1)Clone the repo:

 ```bash
  git clone https://github.com/ShreyaLbs/NovaOS.git
```

2)Open novaos-index.html in your browser — or use VS Code Live Server  

No build step needed  
This is pure HTML/CSS/JS — just open and run.  

Design Highlights 

Authentic Win98 aesthetics — silver #c0c0c0 chrome, navy #000080 title bars, inset borders  
VT323 pixel font for all retro display text   
Share Tech Mono for system UI elements   
CRT scanlines via repeating-linear-gradient   
Glow pulse animation on the boot logo   
Window open animation — subtle scale + fade on spawn   


Event Details:

Nova Tech Fest 1998 · September 12–14, 1998  
Silicon Valley Convention Center, CA  
Theme: "Beyond the Browser" · Prize Pool: $50,000 USD  


Author 
Shreya — @ShreyaLbs 
