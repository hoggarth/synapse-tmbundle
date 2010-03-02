Installation
============

To install via Git:

		mkdir -p ~/Library/Application\ Support/TextMate/Bundles
		cd ~/Library/Application\ Support/TextMate/Bundles
		git clone git://github.com/hoggarth/Synapse.tmbundle.git "Synapse.tmbundle"
		osascript -e 'tell app "TextMate" to reload bundles'

Source can be viewed or forked via GitHub: [http://github.com/hoggarth/Synapse.tmbundle/tree/master](http://github.com/hoggarth/Synapse.tmbundle/tree/master)

To install without Git:

		mkdir -p ~/Library/Application\ Support/TextMate/Bundles
		cd ~/Library/Application\ Support/TextMate/Bundles
		wget http://github.com/hoggarth/Synapse.tmbundle/tarball/master
		tar zxf hoggarth-Synapse.tmbundle*.tar.gz
		rm hoggarth-Synapse.tmbundle*.tar.gz
		mv hoggarth-Synapse.tmbundle* GitHub.tmbundle
		osascript -e 'tell app "TextMate" to reload bundles'

