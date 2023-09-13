# Fuck Using a Mouse | [0] Why the Fuck Should I Bother?

I'm just playing -- there are definitely times when the mouse is superior to doing everything with just the keyboard. If you're not a fucking nerd, you probably can't even imagine doing any sort of navigation on your computer using just your keyboard outside of copying/pasting something or maybe the occasional keyboard shortcut in an internet browser. You might be thinking, "why are you trying to fight what's natural, _tHe wAy gOd iNtEnDeD_?" Moving into the terminal, learning how to use [Tmux][tmux] and [Neovim][neovim]/[Vim][pictures of trash], and eventually being assimilated by the cult of TmuxVim will change that for you.

In this blog post, I'll be talking about why you should consider reducing your reliance on the mouse, and why you should consider using Vim/Neovim within the terminal.

> I will note the benefits of this workflow becomes drastically apparent if you know how to touch type. If you can't touch type yet, I strongly recommend [practicing][monkeytype].

# Why Not Use a Mouse?

Thinking about not using a mouse really does seem kind of crazy at first, yet all these fucking nerds on the internet are always raving about the TmuxVim synergy. What the hell is all that about? Well, as a fucking nerd and someone who has used a combination of Tmux and Neovim for about 3 years, here are some of the biggest reasons why I encourage software engineers to at least give it a shot before just spewing speculations and remaining ignorant to the culture.

From this point on, I will primarily be referring to Vim when discussing the merits of keybindings since Vim's keybindings are somewhat universal and have been ported to many different platforms such as Tmux, terminal emulators, VSCode, etc.

## "Speed, agility, and responsiveness are the keys to future success." - Anita Roddick

Are we software engineers not using an **AgIlE wOrKfLoW** everyday to ensure project efficiency and progression towards success? Are we not striving to build **rEsPoNsIvE uSeR iNtErFaCeS** that will ensure client satisfaction and hence increase revenue for the company? For the sake of this argument, these two aspects of future success may be more attributed to team dynamics/synergy than personal ability. The question now becomes, "how can I get faster at shipping code?" Fair warning again -- if you're a normal person, this is where it's going to start sounding like I just escaped from a mental asylum and am just ranting about numbers.

![the numbers mason][the numbers mason]

I don't think many of us stop and think about it, but a lot of time is wasted in the motion of moving your hand from the keyboard to your mouse, clicking and moving the mouse around to navigate, and then moving your hand from the mouse back onto the keyboard. One could argue that's just how the cookie crumbles when you use a modern computer, and it's mostly true if we're talking about interacting with a computer outside of a terminal (with the exception of using a [tiling window manager][tiling window manager]). However, if you're reaching the mouse merely to interact with text in your text editor, that's a whole lot of time wasted on just that movement. Once you learn Vim keybindings, you'll be able to move around better and much, much faster than using the mouse. And once that muscle memory is fully developed, you're going to wish those keybindings were available everywhere outside of Vim.

## Fuck Carpal Tunnel Syndrome

As software engineers, we spend countless hours in front of the computer typing and clicking away. Consequently, we're unfortunately more prone to developing carpal tunnel syndrome. The most straightforward way to mitigate the risk of developing CTS is to have an ergonomic setup, but another way is to reduce how frequent we move our hands from the keyboard to the mouse. According to [Mayo Clinic][mayo clinic cts] and [Cleveland Clinic][cleveland clinic cts], research suggests using a keyboard does not cause carpal tunnel syndrome. Rather, using a mouse may be more likely to cause CTS.

I used to suffer from CTS prior to being initiated into the cult of TmuxVim. It was partially my fault for not properly setting up an ergonomic workspace back then, but I was able to eliminate CTS symptoms just by learning to rely on the keyboard. Nothing else about my setup changed with the exception of the development tools I used to write code. You'll be able to find personal anecdotes online from people who have experienced the same health improvements (like [this post][reddit vim cts] and [especially this comment and its replies][reddit vim cts 2]) after switching over.

If you already suffer from CTS, hit up `vimtutor` and give Vim keybindings a chance.

## Working Hard to Be More Lazy

If I had to describe my initial learning experience with Vim in one sentence, it would be "I worked hard back then to be lazy now."

![vim learning curve graph][vim learning curve graph]

If you're into programming memes, you have have already seen this graph somewhere. Not trying to scare you here, but whoever made this graph did a damn good job because this is a spot-on illustration of just how hard you will have to work in the beginning if you really want to get proficient with the keybindings. Vim and its related text editors just feel completely different from anything else you've likely used. That being said, it's like anything else in life -- you can and will get used to it.

Once you get used to it and your muscle memory has developed, it's _mostly_ like the graph says: smooth sailing from here on out. If you stick to it, you _will_ reach a point where you wish you had Vim's keybindings available anytime you touch some sort of text editing area because using a mouse or any other keybindings feels way too slow and somehow outdated (even though it should be the exact opposite since [Vim is pretty old][vim initial release]).

I digress. This point is a minor one, but I would argue less movement and using less tools to achieve the same goal is successfully being lazier. If your hands aren't leaving your keyboard to reach for your mouse as a part of your text editing workflow, you have successfully become lazier while paradoxically becoming more efficient.

![few word do trick][few word do trick]

# In Summary

I think the main appeal to switching to Tmux and/or Vim/Neovim is the speed at which you can achieve what you want to do when editing text. You can get shit done faster and with less effort once you've learned to reduce your reliance on the mouse, all while potentially mitigating the risk of injuring yourself from long hours of interacting with a computer (carpal tunnel syndrome). Sounds pretty good, does it not?

If any of this interests you, check out the next blog post where I discuss the merits of using a command-line text editor like Neovim as opposed to a GUI-based text editor such as VSCode.

[cleveland clinic cts]: https://health.clevelandclinic.org/does-typing-cause-carpal-tunnel-syndrome/
[few word do trick]: https://imgur.com/a0CfKDO.gif
[mayo clinic cts]: https://www.mayoclinic.org/diseases-conditions/carpal-tunnel-syndrome/symptoms-causes/syc-20355603
[monkeytype]: https://monkeytype.com/
[neovim]: https://neovim.io/
[pictures of trash]: https://www.google.com/search?q=trash&tbm=isch
[reddit vim cts]: https://www.reddit.com/r/vim/comments/7a7g0q/how_vim_saved_my_wrist/
[reddit vim cts 2]: https://www.reddit.com/r/cscareerquestions/comments/bcr76c/im_19_and_my_carpal_tunnel_syndrome_has_gotten/eksu5fh/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button
[the numbers mason]: https://i.imgur.com/EQHHhZy.gif
[tiling window manager]: https://en.wikipedia.org/wiki/Tiling_window_manager
[tmux]: https://github.com/tmux/tmux
[vim initial release]: https://www.google.com/search?q=when+was+vim+initially+released
[vim learning curve graph]: https://imgur.com/9ZHGp71.png
