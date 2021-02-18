# Web Typography, 2020/2021

**First thing I did was obviously watch the film because the fragment made little to no sense to me.**

The scene of the film starts with Constant K (a bio human) heading to his baseline test. Contant K is reffered to as a replicant which is actually the most compliant bio human. They have an open lifespan. Which means that once they fail the baseline test, they get deemed deffect. 
During the baseline test, the replicant is supposed to say the poem and then answer the questions as quickly as possible after the questioner. Taking time between sentences means a failed test.
Because replicants are actually robots with a perfect human paintjob, they get called slurs like skinjob or skinner.

## Getting to know Darice
**Before starting to modify the ccs of the closed captions, we got the chance to get to know Darice a little bit and know more about what she would expect / wants to see from us.**


### Things Darice mentioned in regards to the styling of the closed captions

- She likes minimalism. 
Darice mentioned that most of the stuff she makes herself are always minimal.

- One thing that she likes about films is the feeling she can get from them. (Like Nostalgia when watching old films.)

- Darice became deaf so she could still imagine sounds as she's heard them before. 
So it should be straight forward to just add the names of the sounds we hear.

- She's not a fan of too much movement of the video, it's not supposed to take away from the film itself. 
Like it could move a bit sometimes but she wouldn't like 2 hours of a moving movie frame. 

- The thing she thinks is missing the most when it comes to subtitles is the lack of subtitles for the sounds. 
Sounds really set the tone for what kind of scene your watching and she obviously cant experience this at all if barely any closed captions include sounds.

- When different people are talking, use another color for the subtitles. 
If people are speaking fast or simultaneously colors would be the best way to let the viewer know. 

- Besides colors it would also be good to just add who's talking in front of every sentence. 
(Example: Questioner: Why dont you say that three times)

- Use different font styling. Examples: **Bold** for screaming. *Italic* for whispering.


## First css changes

**The first thing I did was go over the top, to be able to really see what Darice dislikes.**

- I made the video big and put the text on top of the video.
Darice mentioned that its good if the subtitles are in the middle of the video at the bottom. That way she doesnt have to look side to side every time someone speaks. As it is easier to bring everything to the middle to not take away from the movie.

- I made the different speakers get a different color when they spoke. 
The questioner; yellow, Contant K; white and the random man; orange.

- The first few sounds repeat themselves 3 times. The sound to me felt like some kind of computerized object opening and closing so I wanted to alternate between black and another color. I chose green, red and blue. 

- Theres also a frantic beeping sound which I wanted to style by having the background color flicker between red and black repeatedly.

## Feedback 1

- Color changes for different speakers is effective but I should think about the typography as well. 
- Green red and blue for the background every time a sound comes on, doesn't really say anything.
- Frantic beeping works well and is well timed


## Second ccs changes

**With my team we decided to each test a specific thing in our video so that we can get as much insight as possible as to what Darice would like and what she wouldn't like. We tested text placement, background colors and movement, movement when it comes to the video itself and sound closed captions /  descriptions.**

- I added descriptions for the sounds. 
I made them bright blue to be a different from the closed captions of the people that speak. I wasn't sure what sounds they were myself at first but i settled on, "short beep", "distant buzzes" and a "short whirl."

- I also added who is speaking before every sentence.
- I decided to change background color of the first few sounds (that I initially made green red and blue.) 
A light cream greenish tone (#B7BFAE) So now the sounds go from that color to black. Its well timed and somehow makes the illusion good because I added a smooth transition.

- I made Constant K Brenner `font-family: "Brenner Sans Medium";` because he's supposed to be the regular human person in this scene. So he gets a basic font and font style.
- The questioner, out of sight and his voice comes from speakers of some kind of computer `font-family: "Brenner Mono Light";` a more computer / typewriter font styling.
- The random man, also human, but whispering  `font-family: "Brenner Sans Light Italic";` 
- The sounds `font-family: "Brenner Mono Light Italic"; `because they all sound a bit computerized.

## Feedback Darice

**Darice really liked my video especially because I had the sounds as closed captions.
She did tell me to make sure my contrast on the sounds' closed captions is a little higher to be more visible.
Darice didnt really care much for moving videos or floating subtitles so I decided to leave that as it is**



## Last changes

- I made the sounds' closed captions dark red instead, improving the contrast.
- Lastly I made my blinking animation go from dark red to to bright red, so it can seem like its gets more intense as the baseline test goes on.


### Principles

**The 4 principles:**
I think I did pretty well when it comes to the 4 principles.

**Study the situation**
We got to know Darice, asked her questions about her likes and dislikes. Got feedback from her and listened to her tips.
We studied her situation in specific, we asked if shes always been deaf what movies she likes, why these movies speak to her the most and what she finds so great about watching movies. Also what she feels like she misses when watching a movie now that she can't hear anymore.

**Ignore Conventions**
Subtitles are usually white boring standard font. By doing this asignment and catering to Darice we already ignored most conventions when it comes to subtitles. Background changing colors, different fonts for different people speaking, putting the frame somewhere else / it not being fullscreen.

**Prioritize identity**
Since this assignment wasn't one with a targeted group rather just one targeted person. we had to make something Darice was happy with. while also still making it something that we were happy with. Darice said when we got to know her that her things are always minimal. 

The baseline test itself has like a mysterious aura. If you watch the video on it's own you actually wouldn't really know what was going on. I wanted the sounds to really be made clear with my css styling, while still being minimal. 

**Add nonsense**
I addedn a changing the background color every time another sound comes on. besides that i also added a blinking background animation when the sound is rapidly beeping and made it brighter as the questioning goes on. Is it needed? no. But it makes the sound more obvious and gives you the ability to feel the sound with just visuals. 


