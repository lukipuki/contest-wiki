This chapter talks about various tools that can help you. I only write about the tools I know and it's not meant to be a comprehensive guide to all editors, shells, version control systems and command line utilities that exist. It rather shows some examples how various tools can help you, but you might have a different preference when it comes to an editor, shell etc.

## Vim
Vim is a very powerful text editor you probably heard about.
<blockquote>Vim is not about speed, it's about comfort. — ''JHChabran''</blockquote>

Imagine your friend invited you for dinner and you are helping him in his kitchen. He only has a quite dull knife. The knife will do the job and it will take you a couple of minutes more, but most importantly, you will have to give more focus on the dull knife and how ineffective it is compared to your knife at home. You might also need to use more force. All of this will result with less comforting experience than with a sharp knife, the right tool for the job.

You can often hear people saying that they use Vim because of the speed of editing it provides. Personally, I don't think the speed gain is so noticable and I agree with JHChabran's quote above. It is much more about ''your own comfort'', it is the metaphorical sharp knife you need to edit text.

Suppose you want to swap 2 lines of code, because you wrote them in the wrong order. You would be surprised how often this happens. In a classic editor you could move your hand to the mouse, select a line, press Ctrl-X, move the cursor one line up and press Ctrl-V. Or you can press Home-Shift-End to select a line instead of using the mouse. In Vim, all you need to do is type ddP. The sequence "dd" deletes the line and "P" pastes it above the current line.

Yes, Vim saves you one or two seconds with this operation. But it's more important that you barely need to focus on the action. The sequence "ddP" is so short and you probably use it so often, that it becomes a muscle memory and you barely have to think about it. The beauty of Vim is that it is a tool that doesn't get in the way.

###=External links
* [http://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/ Learn Vim Progressively] by Yann Esposito
* [http://www.viemu.com/a-why-vi-vim.html Why, oh WHY, do those #?@! nutheads use vi?] by Jon Beltran de Heredia
* [http://stevelosh.com/blog/2010/09/coming-home-to-vim/ Coming Home to Vim] by Steve Losh
* [http://www.viemu.com/a_vi_vim_graphical_cheat_sheet_tutorial.html Graphical vim Cheat Sheet and Tutorial]
* [http://vimbits.com/bits?sort=top Vimbits], the best settings for .vimrc voted by other users.
* [http://vimawesome.com/ Vim Awesome]

## zsh
A shell more user-friendly than bash.


### External links ===
* [http://friedcpu.wordpress.com/2007/07/24/zsh-the-last-shell-youll-ever-need/ zsh: The last shell you’ll ever need!]
* [http://grml.org/zsh/zsh-lovers.html zsh-lovers man page] with a lot of useful examples
* [http://www.bash2zsh.com/zsh_refcard/refcard.pdf zsh reference card] with all important information condensed into a few pages.
* [http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/] great tutorial on zsh.
* [https://github.com/zsh-users/antigen Antigen] is a plugin manager for zsh similar to Vundle for Vim.
http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/

## Mercurial
Version control system simpler than git but still better than SVN or CVS, which should suit your needs in most cases.
