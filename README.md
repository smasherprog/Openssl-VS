<h2>Openssl Visual Studio projects</h2>
<p>This repository contains Visual studio projects for openssl.</p>
<p>Requirements: Perl for windows. I use http://strawberryperl.com/</p>
<p>Make sure the openssl submodule is present. After cloning this repo, check the openssl folder. If its empty, open a command window to the repository folder.</p>
<p>Type <b>git submodule update --init --recursive</b></p>
<p>This will download the correct version of openssl into the folder.</p>
<p>Another issue to watch for are NDK compile issues. I have ran into some instances where the 64 bit NDK has subtle bugs that prevent compilation and the 32 bit works better.</p>
<h3>After that, your done. Open visual studio and build.</h3>
