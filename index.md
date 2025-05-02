$page[title:"My Slamhaus Site"description:"A blank Slamhaus template demonstrating rich media embeds."keywords:"slamhaus, template, markdown, embeds"]()

:hero[](#hero)

# 🚀 Welcome to Your Slamhaus Site!

This is the out-of-the-box hero section. Replace me with your own content.

?button[action:"/about.html" text:"Learn More"](#learn-btn)

:/hero

<br>

---

<br>

:section[align:center](#media-demo)

## 🎨 Image Embeds

:column[size:2](#images-demo)
:column[left]()

### Plain Image

![width:"100%":height:"300px"](assets/media/demo.jpg)

:column[right]()

### Clickable Image

![width:"50%":link:"https://piledriver-playhouse.com/slamhaus"](assets/media/demo.jpg)

:/column

:/section

<br>

---

<br>

:section[align:center](#video-audio-svg)

## 🎞️ Video, 🔊 Audio & 🖼️ SVG

:column[size:3](#media-variety)
:column[1]()

### Video

!video[width:"100%"height:"360px" Demo Clip](assets/media/demo.mp4)

:column[2]()

### Audio

!audio[controls loop](assets/media/demo.mp3)

:column[3]()

### SVG

!svg[width:"100"](assets/icons/demo.svg)

:/column

:/section

<br>

---

<br>

:section[align:center](#form-demo)

## 📬 Simple Contact Form

?form[action:"https://formsubmit.co/you@example.com":method:"post"](#contact-form)

?input[type:"email":name:"email":placeholder:"Your email":required:""](#email-field)

?input[type:"text":name:"name":placeholder:"Your name":required:""](#name-field)

?textarea[name:"message":placeholder:"Your message":rows:"4":required:""](#message-field)

?button[text:"Send"](#send-btn)

?/form[]()

:/section
