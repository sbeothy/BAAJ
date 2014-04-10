mapMain.on("extent-change",function(getCenter){
        var centerLocation = mapMain.extent.getCenter();
        console.log(centerLocation.getLatitude());
        console.log(centerLocation.getLongitude());
		});
