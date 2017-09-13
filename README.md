
Case generated with [Swill's case builder](http://builder.swillkb.com/) 
with the following settings:

Switch Type: MX {_t:3}
Stabilizer Type: Cherry Only {_s:2}
Case Type: Sandwich
USB Cutout: ON, Center = -104.775, Width = 1
Mount Holes: Count = 4, Size = 0, Edge Width = 7
Edge Padding: ON, Top = 8, Left = 8, Right = 8, Bottom = 8
Plate Corners: 4
Custom Polygons:
	# Mount holes - 3 mm
	Layers: All, 
	Cut Polygon, 
	Circle, 
	Radius = 3.1, 
	Reference = [0,0];[0,0];[0,0];[0,0], 
	Center = [-127.601,-51.401];[127.601,-51.401];[-127.601,51.401];[127.601,51.401]
	
	# Mount holes - 5 mm
	Layers: All, 
	Cut Polygon, 
	Circle, 
	Radius = 5.1, 
	Reference = [0,0];[0,0];[0,0];[0,0], 
	Center = [-127.601,-51.401];[127.601,-51.401];[-127.601,51.401];[127.601,51.401]
	
	# Reset hole
	Layers: Bottom, 
	Cut Polygon, 
	Circle, 
	Radius = 2, 
	Reference = [0,0], 
	Center = [-59.404,-9.525]
	
	# USB Cutout - Side
	Layers: Open,
	Cut Polygon, 
	Custom, 
	Reference = [-104.775,-55.701], 
	Points = [-9,0];[9,0];[5.5,8.5];[-5.5,8.5]
	
	# USB Cutout - Bottom
	Layers: Bottom
	Cut Polygon,
	Custom,
	Reference = [-104.775,-55.701],
	Points = [-9,0];[9,0];[6.06875,6.7];[-6.06875,6.7]
	
	# Stabilizer cavity
	Layers: Open, Closed,
	Cut Polygon,
	Custom,
	Reference = [0,48.701],
	Points = [-47.625,-1];[47.625,-1];[42.85,3];[-42.85,3]

Kerf: 0.15
Key Unit Size: OFF
Line Color: OFF
Line Weight: OFF
	
