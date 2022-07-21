# 2010 IEEE SECON Conference Paper

RFID Trees: A Distributed RFID Tag Storage Infrastructure for Forest Search and Rescue

https://ieeexplore.ieee.org/document/5508249

## Abstract

We create a distributed storage infrastructure by embedding passive RFID tags in trees, for forest search and rescue. As a hiker moves through the forest, her reader writes a unique identifier (ID) and increasing sequence numbers (SNs) to tags, called (ID,SN) pairs. This creates a digital path for searchers to follow if the hiker is lost. Since tag memory is limited, hikers must share this constrained resource to preserve their digital paths. At each tag, we consider a hiker overwriting an existing (ID,SN) pair if the tag is already full, according to one of four algorithms. In Oldest Selection (OS), the hiker deletes the oldest (ID,SN) pair. In Random Selection (RS), the hiker randomly deletes an (ID,SN) pair. In Highest Frequency Selection (HFS), the hiker deletes the (ID,SN) pair associated with the ID that she has seen the most in previous tag encounters. In Lowest Delete Frequency Selection (LDFS), the hiker deletes the (ID,SN) pair associated with the ID that she has deleted the least in previous tag encounters. HFS performs the best, but requires hikers to remember the number of ID encounters in the past, for each hiker ID.
