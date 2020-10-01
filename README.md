Miscellaneous dotfiles

Quick install:

	git clone https://github.com/pawel-slowik/dotfiles-misc.git ~/dotfiles/misc
	ln -si ~/dotfiles/misc/.tmux.conf ~/.tmux.conf
	mkdir -p ~/.config
	ln -si ~/dotfiles/misc/.config/git ~/.config/git
	ln -si ~/dotfiles/misc/.config/xmodmap ~/.config/xmodmap

	sudo make -C /usr/share/doc/git*/contrib/diff-highlight
	sudo cp /usr/share/doc/git*/contrib/diff-highlight/diff-highlight /usr/local/bin/
	sudo chmod 755 /usr/local/bin/diff-highlight
