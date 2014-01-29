Wifi Access Point Mapping App

This app will automatically scan the area for open (no wireless authentication like WEP or WPA/WPA2) access points in the current vicinity, and mark the open access points on a map.  This can be done in the background as long as app was started.  Access points found will be persisted so they will appear on a map even if that's not your current GPS location.


Start Location Activity

1.  User starts at this activity on app launch

2.  User needs to set location to load the initial map using two options:

  a.  Search box - like google maps, must enter city+state (or zipcode), and street address (optional)
  
  b.  Use current location - use GPS to get current coordinates (requires location access)
  
  
Map View Activity

3.  After location set, Google map is loaded

  a.  Location (from #2) will be centered on and marked at all times with a YELLOW marker
  
  b.  Persisted open access point metadata will be accessed by the app to determine color of access point markers. 
  
  c.  Open  Wifi access points will be marked with a BLUE marker
  
  d.  Confirmed free wifi access points will be marked with a GREEN marker
  
    - A wireless point could be open, but actually require payment to use such as most hotels
    
  e.  Confirmed "not free" wifi points will be marked with a RED marker
  
  f.  User can use standard map features such as scroll, pinch zoom, tap to zoom, etc.  
  
  g.  As the map zooms, new markers will pop up based on "view area"
  
 	

Access Point Activity

4.  Upon clicking on a marker (access point), map will zoom in and center on the accesspoint.  A tooltip type dialog box will pop up (similar to Google maps where it displays address, nearby businesses, search for directions link)

  a.  User can add a short persisted text note for the access point.
  
  b.  User can check a box that confirms it to be free vs. not free which will change the color of the marker (See 3.d and 3.e).
  
  c.  Access point name will be displayed.
  
  d.  User can save the note and confirmation.  
  
    - The access point will implicitly be added to the favorites list if it is confirmed free.  
    
  e.  Marker colors will be updated when user goes back to Map View.
  
  f.  Will be a "Get directions to" link that will link to google maps and autofill the current GPS location as start and access point coordinates as the end
  

Favorites List Activity

5.  User can get a list of all open access points that they confirmed to be "free"

  a.  List item will show access point name, city, state, and the user note if any

  b.  Clicking on list item will brink up Access Point Activity for that access point, with Map View Activity in the background
  
  c.  User can delete items by long clicking on list item.
  
  d.  User can "delete all" items.
  
  e.  User can "bulk delete" items by checkmarking each one and clicking delete.

