# Make Claude Code Build Beautiful Websites (Not AI Slop)

Every prompt from the Zoomproof video, in the order I used them.

▶ **Watch the video:** _(link added after upload)_  
🌐 **The site from the video:** https://flowpilot-mocha.vercel.app/

---

These are the exact prompts I typed, in order (spelling tidied, meaning unchanged).
Tools: Claude Code (Claude app) · Pinterest · Google Flow · Vercel.

## 0. Before you start: references
Search Pinterest for the kind of site you want (I searched **saas landing page**) and download 3–4 pictures that agree
with each other (same colours, same feeling), plus one short video of the scroll animation you like.

## 1. The brief (Claude chat): no client? ask Claude to play one
```
i want you to give me a data about an imaginary saas business for which act like you want me to create a website and give me some information from which i can create your website
```
Then click **Create a Claude Doc from your last answer** and download it as a PDF.

## 2. The build prompt (Claude Code, with the PDF + pictures + video attached)
```
I have uploaded a pdf and some images and a video.
I want you to create me a beautiful website for a SaaS business which I have provided all the information in the pdf and I want the website to look beautiful clean and premium like the reference images and I want it to have that scroll animation that the video have where that application interface moves to different sides and feels like a 3d object on the page. Give me prompts for every image you need me to generate and I will generate them for you and for now create the website with placeholders to replace with the real images after.
```

## 3. When the image prompts are hard to follow
```
i can't understand the prompts give me the clear prompts just prompts for me to copy paste.
```

## 4. After making the images (I used Google Flow, free credits)
```
I have generated all images and downloaded them in the asset, image folder.
update the website with real images.
```

## 5. Round 1
```
it looks great, but I want some changes
I think it will be better to have the dashboard a little visible in the landing page so viewers can know there is something waiting for them after scroll.
The scroll feels too random and if I scroll a little fast I can skip some sections, so I want you to add something like if I scroll more or scroll a little it automatically and smoothly scroll me to the next or previous section.
Next I want you to change the CTA and other things dark blue color to a lighter accent color to match the overall website aesthetic.
And I want you to add real logos and icons to the whole website and create the remaining screens like the login or start free trial and other remaining sections.
```
Claude asked which lighter accent colour to use. I picked **Sky blue**.

## 6. Round 2 (I saved one more Pinterest picture of a login form into the reference folder first)
```
It looks great, but there is room for some improvements
1. I want you to make some changes to the login screen it looks too flat and doesn't feel like its from our site, I have downloaded some new login form reference in the reference folder take a look at them.
2. the Have an account? login? is in the wrong place.
3. the you are all set screen look flat too.
add some slight animations to make the login page screens feel alive.
Then I want you to add a working demo product for viewers to interact with so they can test the product inside the website without leaving it.
```

## 7. Round 3
```
OK its good but i wanted the simulation to be in the template that was like the 3d object in the website like it shouldn't be the real product on full screen it should be like just a demo inside the website.
```

## 8. Round 4
```
OK can you make the default theme the light theme because the dark theme doesn't match the aesthetics we are trying to achieve.
After that give me a local host link for the website for me to test it.
```

## 9. Round 5
```
Everything looks great, but the top navigation bar looks a little big can you make it a bit smaller.
Once everything is done i want you to host the website on my vercel account.
```

## The pattern for your own rounds
**What you see · where it is · how it should feel instead.**
Example: "The scroll feels random. Snap me to the next section."

---

# The 17 image prompts Claude wrote for me (paste each into your image generator)
## 1. hero-sky.jpg

```
Photorealistic photo of a bright blue daytime sky. Deep blue at the top, fading to soft light blue lower down. The top and middle of the image are mostly clear and empty. Soft white fluffy clouds only along the bottom edge and bottom corners. Calm, clean, airy. No sun, no birds, no planes, no text. Wide 3:2 image.
```

## 2. clouds-front.jpg

```
Photorealistic thick bank of soft white fluffy clouds, like a sea of clouds, filling the bottom half of the image with a soft rolling top edge. Pure solid black background (#000000) above the clouds. Nothing else in the image. No text. Very wide 21:9 image.
```

## 3. cloud-puff-1.jpg

```
Photorealistic single small soft white fluffy cloud in the centre of the image, fully visible with empty space around it. Pure solid black background (#000000). Nothing else in the image. No text. 16:9 image.
```

## 4. cloud-puff-2.jpg

```
Photorealistic single small wide flat white cloud, soft and wispy, in the centre of the image, fully visible with empty space around it. Pure solid black background (#000000). Nothing else in the image. No text. 16:9 image.
```

## 5. cta-sky.jpg

```
Photorealistic photo of a calm bright blue sky. Blue at the top, fading to almost white at the bottom. A thin layer of soft white clouds along the bottom edge. The centre is clear and empty. Peaceful and clean. No sun, no text. Wide 2:1 image.
```

## 6. testimonial-sara.jpg

```
Bright natural-light photo of a smiling woman in her early 30s sitting at a light wooden desk with an open laptop, looking at the camera in a friendly confident way. Modern minimal office, white walls, a few green plants, soft blurry background. Soft daylight from a window, airy white and light blue colours. Waist-up shot. No text, no logos. 4:3 image.
```

## 7. avatar-tom.jpg

```
Head and shoulders portrait photo of a friendly man in his mid 30s with short brown hair, wearing a navy sweater, gentle smile, looking at the camera. Plain light grey-blue background. Soft natural light, sharp face, realistic skin. No text. Square 1:1 image.
```

## 8. avatar-aisha.jpg

```
Head and shoulders portrait photo of a friendly woman in her late 20s with dark hair, wearing a cream blouse, warm smile, looking at the camera. Plain light grey-blue background. Soft natural light, sharp face, realistic skin. No text. Square 1:1 image.
```

## 9. about-founders.jpg

```
Bright natural-light photo of two co-founders, a man in his late 30s and a woman in her mid 30s, sitting side by side at a desk, looking at one laptop and laughing together. Sticky notes and printed spreadsheets on the desk. Modern minimal office, white and light blue colours, soft window light, blurry background. No text, no logos. Tall 4:5 image.
```

## 10. team-daniel.jpg

```
Waist-up portrait photo of a man around 40 with short dark hair and light stubble, wearing a light blue shirt, relaxed smile, looking at the camera. Standing in front of a plain soft light-blue wall. Soft even natural light, realistic, professional but friendly. No text. Tall 4:5 image.
```

## 11. team-priya.jpg

```
Waist-up portrait photo of a woman in her mid 30s with long dark hair, wearing a dark grey knit top, relaxed smile, looking at the camera. Standing in front of a plain soft light-blue wall. Soft even natural light, realistic, professional but friendly. No text. Tall 4:5 image.
```

## 12. team-lena.jpg

```
Waist-up portrait photo of a woman around 30 with a short blonde bob haircut, wearing a white t-shirt and a light grey overshirt, relaxed smile, looking at the camera. Standing in front of a plain soft light-blue wall. Soft even natural light, realistic, professional but friendly. No text. Tall 4:5 image.
```

## 13. team-omar.jpg

```
Waist-up portrait photo of a man in his early 30s with a neat short beard, wearing a dark indigo sweater, relaxed smile, looking at the camera. Standing in front of a plain soft light-blue wall. Soft even natural light, realistic, professional but friendly. No text. Tall 4:5 image.
```

## 14. blog-7-tasks.jpg

```
Clean minimal 3D illustration on a soft light blue background. Seven small white rounded tiles floating in a gentle curve, each with a simple office icon: envelope, receipt, calendar, chat bubble, chart, folder, credit card. Small purple and mint green accents. A thin glowing line connects the tiles. Soft studio lighting, matte materials. Everything in the centre with empty space around it. No text. 16:10 image.
```

## 15. blog-zapier-vs-flowpilot.jpg

```
Clean minimal 3D illustration on a soft light blue background. On the left, a messy tangled knot of grey cables. On the right, one smooth clean purple line curving upward and ending in a small white paper plane. Soft studio lighting, matte materials. Everything in the centre with empty space around it. No text, no logos. 16:10 image.
```

## 16. blog-kite-studio.jpg

```
Bright natural-light photo of a woman in her early 30s in a small creative design studio, leaning back from her desk with a relaxed happy smile, holding a coffee cup, laptop open in front of her. Colourful design posters softly blurred on the wall behind. Soft afternoon window light. Person in the centre. No text, no logos. 16:10 image.
```

## 17. og-image.jpg (optional, the picture shown when someone shares your link)

```
Bright blue sky with soft white clouds along the bottom. In the centre, a blank white rounded rectangle like an app window, floating and slightly tilted in 3D with a soft shadow. Clean and minimal. No text. Wide 1.91:1 image.
```
