# You have one too many monitors

And if you do have only one monitor... It's probably too big. I work exclusively off my Macbook Pro. No external monitor. No mouse. I recently started a job where their twenty-five or so developers are treated well. Everybody gets the tools they believe will help them be productive. Even though I'm one of a half-a-dozen remote developers, I was required to be on site  my first week. I got my brand new Mac and sat down at my designated work area. It had a monstrosity of a monitor, an external keyboard, and a mouse. The coder beside me was the guy that recruited me. I'd known him for over a decade. I picked up the mouse by its tail, dangled it in mid air and said: "What's this?"

My problems were just beginning. I plugged in the mouse and keyboard. Apparently, even after a  couple years of rodent free development, I was still able to use a mouse. But when I plugged in the monitor, the iMax-like screen scared me. I yelped and pushed my roller chair back into another programmer (who was otherwise happily coding on a similar Mac and monster screen configuration.) I apologized and rolled back to my workspace. I figured I better use this somewhat standard configuration or I'd look like I was more familiar with mainframe mouse-less green screens (of which I am very familiar.)

A half-day later I unplugged the mouse (resisting the urge to step on it) and disconnected the keyboard. Moving my hand continually away from the keyboard seemed a waste of time. My thumbs worked the Mac trackpad quite effortlessly. But I kept the iMax screen attached. I was being on-boarded by my friend and the monitor made it easier for him to see my screen from his pod beside me.

The next day, I gave up on the monster monitor. I unplugged the screen and happily went back to the workspace configuration with which I felt most productive: the MacBook Pro monitor, keyboard, and trackpad.

## What's my deal with monster monitors?

What was wrong with the endless real estate of a grandios monitor? Developers love them. My nephew, a Drexel grad, has three of them -- forming a one eighty around him -- in his home office. Let me give a quick rundown on my issues with the iMax monitor madness before elaborating in detail in the remainder of this post:

 1) The font was too big and my eyes labored over them like text on neon signs.
 2) The width of the editor was too wide, my eyes tired from incessant movement, and I was less able to grok code quickly.
 3) The browser and editor windows were so far apart that my neck tired from side to side movements.
 4) Noise. The voluptuous windows of the editor, browser, Slack, bash, and documentation were distracting.

Balderdash you say. Studies have shown that developers are more productive with, not just big monitors, but multiple monitors. Understand that these studies were financed by monitor manufacturers.

iMax and monster monitors are great for big scenes. We've been viewing big scenes for several hundred thousand years. Our brains evolved to process that pictorial style of information. But we've been reading for merely hundreds of years. Written words, maybe 9,000 years, but alphabetical, phonetical systems have been around far, far less. My point is that the human brain hasn't evolved to the point that it can comprehend some four to five hundred square inches of text as easily as it understands graphics.

As to multiple monitors -- my chickens can process two monitors at the same time. But their eyes are at the side of their heads to look for predators. We humans have eyes at the front to focus on one thing.

![alt text](https://github.com/dondenoncourt/too_many_monitors/blob/master/chicken%20mac%20coder.png)

## Consider the Real World

Hundreds of years ago, when printers began to mass produce books, a page size was carefully selected. That page size has been extremely successful and it is one we know and expect today. Web designers know this. Try as you might to expand your browser of a well designed page to the full width of your iMax-like screen, the text stays at the accepted standard of a readable 45-75 characters per line.

Quick tip: if you are reading text you'd like to comprehend and it doesn't wrap at at least 95 characters per line, narrow your page and things will come to you more clearly.

The Benjamin Franklins of the world -- a few hundred years before today's mega monitors -- knew what they were doing. They figured out that you should not have to move your head to read. Furthermore, they understood that you can only comprehend so many  words at one time. Think about the limit of short term memory: five to seven things. If the average word length is say five to nine letters and you divide your character width of 45-75 (or up to 95) characters, you get your five to seven things. Especially when you consider your brain clumps (in a process known as chunking) words into single concept phrases. Five to seven clumps and that line break comes at the perfect time because that brief pause from consumption gives your brain an opportunity to digest those words into information.

The Kindle reader on my Kindle Fire 10 and iPad automatically switches to a  two pages display when I switch to landscape. Why? Because the designers at Amazon and Apple know it's easier to read when line lengths are a comprehensible 65-95 characters.

Still skeptical? Consider shop and industry standard for statement length limits in code. Typically the limit is around 80 characters. Those limits are for comprehension. If you agree that 80 characters is a reasonable limit, why would you need a monitor that supports line widths that would show short stories in a single line?

Code analyzers (like Rubocop, for Ruby; or eslint, for JavaScript) check not only widths but also height. JavaScript length limits are around 100-500 lines but Ruby constraints are often only 10-30 lines per method with total file length of 150-250. These coding constraints evolved because we've learned too deep and too wide is too much [to comprehend].

## Information Overload

Certainly you don't read one file at a time. You need to look at several. Perhaps code for a model, controller, and a view. And perhaps coding examples from another application. But it's often more than that. You a!so want to see the rendering of that page in a browser. You may need documentation in yet another page. And you need a shell session. All that stuff, you tell me, fills up your monster monitor.

But all those open windows cause your brain to go into information overload. Your eyes and concentration get all befuddled and confused. It's kind of like you're playing whack a mole. There it is. No over here. Your head moves back and forth and you get nothing done. What you need is to limit the mole holes to a manageable couple. Some holes close to one another... where you can just whack that hammer back and forth between two mole holes. Bam. Got it!

If you reduce your whack a mole holes to a manageable three or four, you can master the game. Leave the holes -- the windows -- at nine or so and your eyes unconsciously travel over every hole looking for that damn mole. You eyes, and brain, waste time glancing at windows even when you are pretty sure a hole won't produce a mole. Basically they are noisy distractions.

It boils down to focus. I think of it as view ports. Think of filmmaker putting up their index fingers in the air with hands joined at the thumbs. They are limiting the view port to focus on what is important. Like blinders on a horse.

I've established that there are often times where a half a dozen files are part of a contextual problem. You need to compare files. Understand that the human brain has problems choosing between more than two things at one time. Even with copious amounts of screen real estate at your disposal, you really should only be focused on two files at one time. Context should be split out into tabbed editor sections.

## My layout

Code Editor: I put my code editor to the top left of the screen. It takes 40-60% of the screen real-estate.
Browser: My browser I put on the top right.
Shell: My bash tabbed terminal session goes in the bottom left.
Slack: Slack goes in the bottom right and is most always (but for one character height) is overlayed by the browser or bash window.
Others: Like Activity Monitor, SQL Editor, and Evernote,  get plopped in the middle and are closed as soon as I’m done looking at it.

![alt text](https://github.com/dondenoncourt/too_many_monitors/blob/master/screen%20full.png)

First note that I hide the top menu on my Mac. That gives me an itty bitty bit more real estate. If I move my mouse up, the top menu appears -- otherwise you don’t need it... as it’s just noise. 

![alt text](https://github.com/dondenoncourt/too_many_monitors/blob/master/screen%20top%20menu.png)

And I also shrink the dock icon size.

![alt text](https://github.com/dondenoncourt/too_many_monitors/blob/master/screen%20dock.png)

### Editor

I could write a whole piece on my editor of choice -- Mac Vim. But I’ve seen too many other developers with better Vim development strategies so I won’t be writing that piece. Nevertheless, I will summary my strategy here. I open one Mac Vim session per application and make sure I overlay each vim application window. Tab-tilde toggles quickly between Vim application editor sessions. Every now and again I might drag a Vim editor window to the right side of my screen for comparison. I use Vim tabs with veritical and horizontal split screens heavily. All editors have similar vertical and horizontal code splitting features. Yet I still see folks with too many tabs open for each of the dozens of files they’ve taken a look at. I put vertical and horizontal split often for code that I’m working one. For instance, unit test code goes at the horizontal bottom with the code it tests above it. When copying or referencing similar code, I use vertical splits.

Back to my comment about viewable height of code, If I have a huge file I split the source or use folding option. Most IDEs have this feature.

When my Mac Vim tabs get past 3 or 4, I close some. If I have a crazy amount of splits in one tab, I close some sections. If I have a beautiful set of split code windows showing insightful information, I take a screenshot and name the image appropriately.

### Browser

For my browser, I use the Chrome pin feature and put my common use tabs to the left: email, corporate docs (Confluence), project management (JIRA), and calendar. I open standard tabs for other stuff. Here’s my rule for tabs: If I can’t read the titles, I have too many tabs open and need to close some. If you have a bunch of really, really important tabs you think you need open, I say book mark it. I use the bookmarks bar for heavily used links and I abbreviate or completely remove the textual title. And then I make good use of nested bookmark folders (as I covered in [Relearning to Learn](https://www.infoq.com/articles/relearning-learn/) ). Sometimes, every so often, I’ll pull a tab into its own browser window -- so I can compare it with another -- but I put it back as a tab when done.

### Bash

I use a single tabbed bash terminal window. Typically I have a tab for each application running in a Docker session, I probably resize my bach window more often than any of my other Mac application windows. Typically the only line of interest in a bash session is the last line output from a running process. So my bash is typically (but for the last couple of character lines) overlayed by my editor window. I resize my bash window if I’m using a debugger or browsing through logs.

### Slack

Slack is a wonderful piece of software. But it is noise as it provides the human interaction we all crave. If I see a message pop into a channel, I can’t help but read it. It may be that someone’s cat did something funny and I can’t miss that! So I make sure Slack is overlaid but for the bottom. And, even then that’s only so I can quickly thumb mouse and click to open it -- when I’m ready for distractions. I enable Slack notifications for important channels.

### Font Size

I always use a crisp san-serif font. A bit of an aside on how I remember what san-sarif is:
Omar Sarif was the mustasiod man of Dr. Shivago and Lawrence of Arabia (if you aren't a boomer and haven't watched these movies, you need to.) He had a thick richly curly mustache. San means without so pick a font without thickly curly mustaches. Sorry Mr. Sarif, you can be on my big screen TV but not on my text as code on my Mac.

I also use an easily readable font size. That would be two-thirds times bigger than the smallest you can read. If you visit [Mozilla Fonts](https://www-archive.mozilla.org/newlayout/testcases/css/sec526pt2.htm) You can see what size works well for you. For me the smallest font size I can read is 4 so that suggests that I should use 8 or 14 for my standard font size. Note: as my old eyes get tired during the day, I increase my font size. The Control plus, or minus works in most apps on my Mac including Vim and Chrome.

For code reading, as to color, myself (and [eyecare professionals](https://www.essilorusa.com/newsroom/be-careful-color-and-font-choice-could-hurt-your-eyes)) recommend black on white or black on yellowish better than dark mode. The only time I use dark mode when it is, well, dark, where I am working.

### Transient Applications

My transient apps include Evernote, Activity Monitor, and an SQL Editor. So I can open them easily, I put them in the Dock. And I close them as soon as I am done the one-off task that I’m using them for.


## Close It

Regarding applications and tabs, if you don’t know why it's open, close it.

All those open and viewable Windows are **noise distractions**. Close or overlap them. In the early 2000s I did a lot of onsite training. I found many developers would maximize their editor on their screen. I would say to them: "You aren't running Microsoft Windows, your running Microsoft Window." And then I'd recommend tiling application windows. Really think you need to compartmentalize with multiple monitors? Try virtual desktop options. Turning your head is harder than a simple control key stroke. When I was a free-lance contractor I used a virtual desktop for each client.

I do have to admit that a big reason I like to Mac-only development is freedom. As you can see from the chicken photo above, one of my offices is my front porch. Another one is my hammock. I have the freedom to work anywhere: the beach, the doctor's office waiting room, or at the park. I'm not hampered by the unjustified requirement of an external monitor.



