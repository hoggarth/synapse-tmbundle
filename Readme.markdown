Installation
============

To install via Git:

		mkdir -p ~/Library/Application\ Support/TextMate/Bundles
		cd ~/Library/Application\ Support/TextMate/Bundles
		git clone git://github.com/hoggarth/synapse-tmbundle.git "Synapse.tmbundle"
		osascript -e 'tell app "TextMate" to reload bundles'

Source can be viewed or forked via GitHub: [http://github.com/hoggarth/synapse-tmbundle/tree/master](http://github.com/hoggarth/synapse-tmbundle/tree/master)

To install without Git:

		mkdir -p ~/Library/Application\ Support/TextMate/Bundles
		cd ~/Library/Application\ Support/TextMate/Bundles
		wget http://github.com/hoggarth/synapse-tmbundle/tarball/master
		tar zxf hoggarth-synapse-tmbundle*.tar.gz
		rm hoggarth-synapse-tmbundle*.tar.gz
		mv hoggarth-synapse-tmbundle* Synapse.tmbundle
		osascript -e 'tell app "TextMate" to reload bundles'

