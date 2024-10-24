install:
	echo "Installing to /usr (which may prompt for your password)"
	sudo cp rcm /usr/local/bin/rcm
	sudo cp rcm-alias /usr/local/bin/rcm-alias

tests:
	echo "This assumes rcm is installed"
	rcm test1_mcro 0.0.0.0 user1 pass1
	rcm-alias test2_mcro 0.0.0.0 user2 pass2
