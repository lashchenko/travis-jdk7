[![Build Status](https://travis-ci.org/lashchenko/travis-jdk7.svg?branch=master)](https://travis-ci.org/lashchenko/travis-jdk7)

The build with JDK7 on Travis was failed as expected:

`$ ~/bin/install-jdk.sh --target "/home/travis/oraclejdk7" --workspace "/home/travis/.cache/install-jdk" --feature "7" --license "BCL"
 install-jdk.sh 2018-10-17`

 *`Expected feature release number in range of 9 to 13, but got: 7`*

 `The command "~/bin/install-jdk.sh --target "/home/travis/oraclejdk7" --workspace "/home/travis/.cache/install-jdk" --feature "7" --license "BCL"" failed and exited with 3 during .
 Your build has been stopped.`

https://travis-ci.org/lashchenko/travis-jdk7/builds/474112959