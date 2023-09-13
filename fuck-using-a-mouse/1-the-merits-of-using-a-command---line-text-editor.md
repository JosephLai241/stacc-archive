# Fuck Using a Mouse | [1] The Merits of Using a Command-Line Text Editor

I would like to talk about why you should consider using a classic command-line text editor on top of just learning the Vim keybindings. The thing is, you can hit up `vimtutor`, learn the keybindings, and then just install a Vim keybindings plugin for VSCode or some shit and completely avoid living in the terminal like a fucking nerd. However, I would argue there are merits to sticking with the classics instead of using a modern GUI-based text editor.

**You should consider sticking with the classic command-line text editor if...**

## You're a Minimalist

"Stock" Vim/Neovim is super barebones out of the box, but you can create configuration files for whichever flavor of Vim you're using to customize the editor to your liking with the things you want it to have, no more and no less.

Years ago, I was doing everything on a shitty Dell 2-in-1 laptop with an Intel i3 processor and 8GB of RAM. I can't even tell you the number of times that laptop has crashed because I had ran out of memory. I had to go to extreme lengths to mitigate system resource consumption, including completely wiping my hard drive and switching from Windows 10 to Arch Linux so I could fully control what my system was running. Switching from VSCode to Neovim was part of my workflow overhaul to minimize system resource consumption. Switching made a significant difference as I experienced much fewer crashes during development compared to when I was using VSCode (yes, _fewer_, not no more crashes. It really was a shitty laptop).

![Ron Swanson Trashing a Computer][Ron Swanson Trashing a Computer]

All this is to say -- if you're concerned with the amount of bloat from both a user and resource perspective, you should consider fully switching from a GUI-based text editor.

## You Like Something Portable/SSH Into Linux Servers Often

If you SSH into Linux servers and edit text within those servers often, you should seriously consider switching over. Vim is typically already installed by default within many Linux distributions, so there's no need to manually go about installing your development environment if Vim is your preferred editor. Even if it isn't your preferred editor (if you primarily use Neovim, for example), it's so convenient to just open a text file in Vim real quick and be in a familiar environment. No need for any additional setup.

If there are some nice amenities you like to set up for Vim, you can easily copy over or clone the configuration file from somewhere else, such as GitHub. Setting up a fully working IDE environment within Vim is typically only a few extra steps if copying the configuration file doesn't do it.

## You Want to Strengthen Your Command-Line Skills

All this talk about SSH'ing allows me to segue into something that I think is really important for all software engineers regardless of the stack they're working with -- being comfortable with the command-line.

I think the command-line may invoke some strong emotions whenever engineers who aren't familiar are forced to interact with it. "How the hell do I do _x_?" "I'm going to fuck something up!" "Why bother when we have GUIs now? Isn't it more convenient with a GUI?" These are just some of the things I've heard people say when discussing the command-line.

![COLD SWEAT][cold sweat]

While these definitely are valid questions, I believe any software engineer worth their salt should at least have some basic knowledge of how to interact with a Linux command-line, even if they primarily work on the frontend. I believe a good software engineer is well-rounded in the world of computer science, and a well-rounded software engineer is more likely to be a good software engineer than one who has tunnel vision. You might not typically need to interact with the command-line, or maybe it's much more convenient to do something via the GUI than the command-line; however, there will be a time where you'll wish you knew how to do something via the command-line.

## You Want to Be a _HaCkErMaN_

![HACKERMAN][hackerman]

This one's more for shits and giggles, but it is kind of true if you're a fucking nerd.

Many of us have been exposed to hacking scenes in movies as we were growing up, where one of the protagonists have some sort of terminal open on the computer, frantically mashing random keys, then a few seconds later they proclaim "_I'm In ThE mAiNfRaMe!_". Maybe younger you thought that was pretty cool, and you might've wanted to emulate that at some point. If so, I have good news for you -- some childhood dreams aren't just dreams; you can start making this dream a reality today by just using a command-line text editor instead of a GUI-based one.

This is definitely subjective, but I've always thought command-line tools have looked much more aesthetically pleasing compared to their GUI counterparts. Then again, maybe I just have an affinity for old-school shit.

# In Summary

At the end of the day, you should do whatever the fuck you want. You're in control of your life. I do hope you'll try, or at the very least consider trying, Vim/Neovim or Tmux, though. It has changed my life for the better and maybe it can for you too. Even if you're not looking to change your current workflow, why not learn something new? Who knows when this knowledge will come in handy? I'll leave you with this quote.

> “Anyone who stops learning is old, whether at twenty or eighty. Anyone who keeps learning stays young.”
>
> > -- Henry Ford

![the more you know][the more you know]

[cold sweat]: https://imgur.com/QvaLsvT.gif
[hackerman]: https://imgur.com/T8rBXwc.png
[Ron Swanson Trashing a Computer]: https://i.imgur.com/jZb4rPB.gif
[the more you know]: https://i.imgur.com/zsSZjls.gif
