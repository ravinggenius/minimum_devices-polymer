Simple translation of [Minimal Devices](http://labs.jaredhardy.com/minimal-devices/) to use [Polymer](http://www.polymer-project.org/).

## Usage

View index.html source to see how to use. Be sure to include the custom elements. You need to serve the files from some webserver for everything to work. If you have Ruby (and the Rack gem) installed, `rackup -b "use Rack::Static, :index => 'index.html'; run Rack::File.new('.')"` should work.

## Issues

Landscape doesn't play nice with the iPhone and iPad elements. I'm happy to take patches, but I'm not much interested in maintaining this repository. I just threw this together as an excuse to play with Polymer.
