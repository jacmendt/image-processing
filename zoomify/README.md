# CreateZoomifyTiles

For proper working of the script ImageMagick (it uses the `convert` command via command line) and gdal pythin bindings have to be installed. Example commands for running the script are:

	python zoomify/CreateZoomifyTiles.py /test/df_dk_0010001_0697.tif /test/test-results
	
The script parameters have to be passed as absolute paths. If you want to use the script from within the python environment call the function `processZoomifyTiles` as a starting point.
