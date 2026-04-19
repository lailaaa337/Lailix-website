# 🎬 LAILIX – Netflix-Inspired Streaming UI

LAILIX is a Netflix-inspired streaming web interface built using HTML and CSS. 
The project focuses on recreating a modern streaming platform UI with a clean layout, 
interactive elements, and a cinematic hero section.

## What's In Here

The main stuff:
- A navigation bar at the top with the branding and menu items
- A featured video section that plays in the background (I used an auto-playing video and overlay text)
- Multiple image galleries organized by category
- Search, notifications, and profile icons (ready to be interactive with JavaScript later)
- Everything's supposed to look good and be pretty responsive

## How to Set It Up

Just grab the files and you're good to go:

1. Clone or download the repo
2. Make sure you have a `pics/` folder with all the images and video
3. Open `project.html` in your browser (literally just double-click it)
4. Check that all the images and video load properly

## File Structure

```
HTML/
├── project.html          # Main HTML file - has all the structure
├── style.css             # All the styling
├── pics/                 # Folder with images and video
│   ├── background-video.mp4
│   ├── tall.jpeg
│   ├── love.jpeg
│   ├── noel.jpeg
│   ├── dog.jpeg
│   ├── adamjpeg.jpeg
│   ├── beautiful.jpeg
│   ├── search-icon.png
│   ├── notifications-icon.png
│   └── profile-icon.png
└── README.md             # This file
```

## What You Need

You'll need these images and the video file in the `pics/` folder:
- A video file (background-video.mp4) for the hero section
- 6 gallery images (I called mine tall.jpeg, love.jpeg, noel.jpeg, dog.jpeg, adamjpeg.jpeg, beautiful.jpeg)
- 3 small icons for search, notifications, and profile

I just used JPGs and PNGs, nothing fancy. The video is MP4 because it works everywhere.

## Preview

Here's what the website looks like:

![Screenshot 1](Screenshot%202026-02-09%20195741.png)

![Screenshot 2](Screenshot%202026-02-09%20195748.png)

![Screenshot 3](Screenshot%202026-02-09%20195755.png)



## Technologies & Stuff

Just HTML5 and CSS3. No crazy frameworks or anything. 

**HTML5** - I used semantic elements like `<header>`, `<nav>`, `<video>` to make the structure clean. Added video with autoplay, mute, and loop so it plays automatically when you load the page. Made sure to include alt text for images too.

**CSS3** - Used flexbox for the navigation and grid layouts for the image galleries. Added some media queries to make it responsive on smaller screens. The styling includes transitions, background positioning, and all that to make it look smooth. Dark theme with some accent colors cause that's what Netflix does and it looks good.

## The Files

**project.html** - This is where everything lives. Header with nav, the featured video section, the image galleries, and the icons. Pretty straightforward structure.

**style.css** - All the styling. Colors, fonts, layout, effects. If you want to customize colors or change fonts, you'd mess with this file.

**pics/** - Folder with all the media (images and video).

## Changing Stuff

**Want to change the colors?** Open style.css and look for the color values. Modify them to whatever you want. Simple as that.

**Want different fonts?** Also in style.css. Just change the font-family.

**Want to change text on the page?** Edit project.html. Change menu items, titles, button text - whatever.

**Want to use different images?** Drop them in the `pics/` folder and update the image paths in the HTML. Just make sure they're named correctly or the paths match.

**Want to resize things?** Change the width, height, padding, margin values in CSS.

## Browser Support

Works in all modern browsers - Chrome, Firefox, Safari, Edge. IE might have issues with the video but honestly who uses IE anymore.

## What I Learned

This was a good project for learning HTML5 and CSS3. Got to practice semantic HTML, flexbox, grid layouts, and responsive design. Also figured out how to embed videos properly. Could add JavaScript stuff later to make it actually interactive (the search, notifications, stuff like that).

## Improvements I Could Make

- Add JavaScript so buttons actually do things
- Make it better on mobile devices
- Add more accessibility features (ARIA labels and stuff)
- Add more animations
- Maybe add filters or categories that actually work

## Other Notes

It's just a college project so feel free to use it as reference or whatever. If you want to fork it and improve it, go ahead.

---

**Made by Layla** - [@lailaaa337](https://github.com/lailaaa337)