Real-Time Map
=================

This code periodically checks a [CartoDB](http://www.cartodb.com) table and refreshes a map in real-time when it detects that the data was updated <sup><a href="#note">1</a></sup>.

### Usage

1. Signup for a [CartoDB](http://www.cartodb.com/signup) account.
2. Upload the data (you can use the CSV files stored in the ```data``` folder).
3. Download this repo.
4. Edit the ```CONFIG``` hash in ```js/app.js``` with your CartoDB username.
5. Open the page in a browser.
6. Update some data and watch how the map refreshes itself.

### Powered by

* [Leaflet 0.4.4](leafletjs.com)
* [CartoDB Leaflet](http://vizzuality.github.com/cartodb-leaflet)

### Demo

http://cartodb.github.com/real-time-map

--

<span id="note">1</span>: But you can bind the refresh code to anything you want!
