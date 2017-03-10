---
distro: Compile
data-content: source
---
<h3><small>You will need the following packages installed:</small></h3>
<h4><small>(names can differ depending on the distribution)</small></h4>
<pre><ul><li>build-essential</li><li>cmake</li><li>vala (>=0.26)</li><li>pkg-config</li><li>libgirepository1.0-dev</li><li>libgtk-3-dev (>= 3.22)</li><li>libsoup2.4-dev</li><li>libjson-glib-dev</li><li>libwebkit2gtk-4.0-dev (or 3.0)</li><li>libsqlite3-dev</li><li>libsecret-1-dev</li><li>libnotify-dev</li><li>libxml2-dev</li><li>libunity-dev (optional)</li><li>librest-dev</li><li>libgee-0.8-dev</li><li>libgstreamer1.0-dev</li><li>libgstreamer-plugins-base1.0-dev (gstreamer-pbutils-1.0)</li><li>libgoa-1.0-dev (>= 3.20)</li><li>libcurl-dev</li><li>libpeas-dev</li></ul></pre>
Navigate to the directory which contains the source and create a new folder for the build:
<pre>mkdir build</pre>
Then navigate to the just created build folder:
<pre>cd build</pre>
Run CMake to generate all the required build-files:
<pre>cmake ..</pre>
Compile the source-code:
<pre>make</pre>
And install the binaries:
<pre>make install</pre>

<h1><small>NOTE: Building on Ubuntu is currently unsupported..</small></h1>