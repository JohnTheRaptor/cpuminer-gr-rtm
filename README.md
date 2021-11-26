cpuminer-gr-rtm
===============

It is higly optimized raptoreum miner from original code.


What is the goal ?
------------------

The original raptoreum miner have several third party llibraries
and normally, they are configured to produce native code to run on any x86 platform.
In this repo, all libraries configured and compiled separately for each platform to gain the maximum performace.

Update 19.11.2021
-----------------

Original miner's windows binaries had been built on linux via cross compiler tools.
From now on, all windows binaries will be built on windows by GCC 11.2 to ensure maximum hash rates.

Usage
-----

Open config.json with a text editor and edit.

On Windows (64 bit versions only) run cpuminer.bat

On Linux (64 bit versions only) run cpuminer.sh

For the first time, it will create tune.config file. (it takes about 70 to 155 mins)

Happy minig!
