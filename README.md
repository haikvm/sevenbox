# jQuery.sevenBox
Cool Windows7 like window with blured overlay

# Default options
	width: 500,
		height: 300,
		blur: 3,
		draggable: true,
		color: '#FFFFFF',
		ajax: false,
		transparent: false,
		headerHeight: 40,
		footerHeight: 40,
		buttons: {
			ok: {
				name: 'Ok',
				position: 'center',
				callback: function() {
					$.sevenbox.destroy()
				}
			}
		}
