# gst

a small go gstreamer binding



## Install 

Ubuntu or Dedian

```sh
apt-get install pkg-config
apt-get install libgstreamer1.0-dev libgstreamer-plugins-base1.0-dev libgstreamer-plugins-good1.0-dev libgstreamer-plugins-bad1.0-dev gstreamer1.0-plugins-ugly gstreamer1.0-libav
```

Mac os

```sh
brew install gstreamer
brew install gst-plugins-base
brew install gst-plugins-good
brew install gst-plugins-bad
brew install gst-plugins-ugly


// set GST_PLUGIN_PATH
export GST_PLUGIN_PATH=/opt/homebrew/lib/gstreamer-1.0/
```

Then

```sh
go get github.com/notedit/gst
```





## Examples

https://github.com/notedit/gst-go-demo




