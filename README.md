NovaOS 98 — Nova Tech Fest Event Website

A retro Windows 98-styled hackathon event website built with pure HTML, CSS, and JavaScript.

OUTPUT:  
<img width="1920" height="1080" alt="Screenshot (665)" src="https://github.com/user-attachments/assets/c67e7ee2-97f9-403b-96a9-5d59fd74c662" />
<img width="1920" height="1080" alt="Screenshot (666)" src="https://github.com/user-attachments/assets/f1d65dd7-22fa-4d8a-ab16-ce1d24e1cb13" />
<img width="1920" height="1080" alt="Screenshot (669)" src="https://github.com/user-attachments/assets/85b6d275-77a2-4125-98ce-473a961f2c48" />
<img width="1920" height="1080" alt="Screenshot (668)" src="https://github.com/user-attachments/assets/be0e19ec-b497-4e81-92da-519f9d5f12b1" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/23432931-b4be-4fc1-957c-6f991cea69b7" />

Live Demo: 
shreyalbs.github.io/NovaOS/

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


Features
FeatureDetailsBoot AnimationProgress bar + live % counter + BIOS hardware logDraggable WindowsMouse and touch drag supportWindow Focus SystemActive = blue gradient title bar, Inactive = greyTaskbarLive clock, app buttons, Start MenuStart MenuSidebar, app shortcuts, Shut DownCRT EffectScanlines + radial vignette overlayRegistration FormNotepad-style with success dialog popupScroll Spy TOCAuto-highlights current section while scrollingFAQ AccordionSmooth open/close with arrow rotationMobile ResponsiveWorks on phones and tablets

Tech Stack
TechnologyUsageHTML5Page structure and semanticsCSS3Styling, animations, layout (Grid + Flexbox)Vanilla JavaScriptInteractivity, drag & drop, DOM manipulationGoogle FontsVT323 (pixel font) + Share Tech Mono
Zero dependencies. Zero frameworks. Zero build tools.

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


Event Details (fictional)

Nova Tech Fest 1998 · September 12–14, 1998
Silicon Valley Convention Center, CA
Theme: "Beyond the Browser" · Prize Pool: $50,000 USD


Author
Shreya — @ShreyaLbs
