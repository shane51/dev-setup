dev-setup
============

<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/dev-setup-resources/master/res/repo-header.gif">
</p>

## Motivation

### Sections Summary
* Section 1 contains the dotfiles/scripts and instructions to set up your system.
* Sections 2 through 7 detail more information about installation, configuration, and usage for topics in Section 1.

## Section 1: Installation

**Scripts tested on OS X 10.10 Yosemite and 10.11 El Capitan.**

* [Single Setup Script](#single-setup-script)
* [bootstrap.sh script](#bootstrapsh-script)
    * Syncs dev-setup to your local home directory `~`
* [osxprep.sh script](#osxprepsh-script)
    * Updates OS X and installs Xcode command line tools
* [brew.sh script](#brewsh-script)
    * Installs common Homebrew formulae and apps
* [pyauto.sh script](#pyauto-script)
    * Set up Python mobile automation development environment.
* [appium.sh script](#appium-script)
    * Set up appium development environment.
* [android.sh script](#androidsh-script)
    * Sets up Android development
* [CI.sh script](#CI-script)
    * Sets up CI environment for mobile

## Section 2: Start installing
#### Running with Git

##### Clone the Repo

    $ git clone https://github.com/shane51/dev-setup.git && cd dev-setup

##### Run the .dots Script with Command Line Arguments

**Since you probably don't want to install every section**, the `.dots` script supports command line arguments to run only specified sections.  Simply pass in the [scripts](#scripts) that you want to install.  Below are some examples.

**For more customization, you can [clone](#clone-the-repo) or [fork](https://github.com/shane51/dev-setup/fork) the repo and tweak the `.dots` script and its associated components to suit your needs.**

Run all:

    $ ./.dots all

Run `bootstrap.sh`, `osxprep.sh`, `brew.sh`:

    $ ./.dots bootstrap osxprep brew

Run `bootstrap.sh`, `osxprep.sh`, `brew.sh`, `pyauto.sh`, `appium.sh`,`android.sh`, and `CI.sh`, :

    $ ./.dots bootstrap osxprep brew pyauto appium android CI

#### Running without Git

    $ curl -O https://raw.githubusercontent.com/shane51/dev-setup/master/.dots && ./.dots [Add ARGS Here]



### Credits

See the [Credits Page](https://github.com/donnemartin/dev-setup/blob/master/CREDITS.md).

## Contact Info

Feel free to contact me to discuss any issues, questions, or comments.

My contact info can be found on my [GitHub page](https://github.com/donnemartin).

### License

This repository contains a variety of content; some developed by Donne Martin, and some from third-parties.  The third-party content is distributed under the license provided by those parties.

The content developed by Donne Martin is distributed under the following license:

*I am providing code and resources in this repository to you under an open source license.  Because this is my personal repository, the license you receive to my code and resources is from me and not my employer (Facebook).*

    Copyright 2015 Donne Martin

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
