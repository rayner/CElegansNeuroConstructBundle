CElegansNeuroConstructBundle
============================

This file contains instructions for installing the software bundle and
running neuroConstruct.

A full guide to getting started is on the OpenWorm Wiki:
https://github.com/openworm/OpenWorm/wiki/Running-the-C.-elegans-model-in-neuroConstruct


Mac / Linux / Unix:
-------------------

Prerequisites:

  To run this software, you will need the Java Development Kit (JDK).

  You can download the right version for your machine from the Oracle website:
  http://www.oracle.com/technetwork/java/javase/downloads/index.html

  You may need to set up your PATH environment variable so that your system can 
  find the Java installation. Instructions on how to do this are here:
  https://www.java.com/en/download/help/path.xml

Setup instructions:

  unzip CElegansNeuroConstructBundle-snapshot-{{DATE}}.zip
  cd CElegansNeuroConstructBundle-snapshot-{{DATE}}
  ./setup.sh

To run:

  cd CElegansNeuroConstructBundle-snapshot-{{DATE}}/neuroConstruct
  ./nC.sh


Windows:
--------

Prerequisites:

  To run this software, you will need the Java Development Kit (JDK).

  You can download the right version for your machine from the Oracle website:
  http://www.oracle.com/technetwork/java/javase/downloads/index.html

  You may need to set up your PATH environment variable so that Windows can 
  find the Java installation. Instructions on how to do this are here:
  https://www.java.com/en/download/help/path.xml

Setup instructions:

  Extract the zip file by right-clicking and selecting "Extract all".
  Browse to the extracted folder.
  Run the file "setup.bat".

To run:

  Go to folder "CElegansNeuroConstructBundle-snapshot-{{DATE}}/neuroConstruct"
  Run the file "nC.bat".

