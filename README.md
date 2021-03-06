# spark-music-recommender
Implementing a music recommendation algorithm and testing on the Audioscrobbler dataset

## Intro

(Under construct)

## How To

###### Init
- `$ git clone https://github.com/redouane-dev/spark-music-recommender.git`
- `$ cd spark-music-recommender`

###### Fetch the Data

For the time being, the link provided by the book (See references) is no longer available; however I found a link in the repo maintained by S. Ryza (Co-author of the book) to the dataset.
- `$ wget -c https://storage.googleapis.com/aas-data-sets/profiledata_06-May-2005.tar.gz`
- `$ tar -xvf profiledata_06-May-2005.tar.gz`
- `$ mv profiledata_06-May-2005 data`
- (Optionaly remove the archive file) `$ rm profiledata_06-May-2005.tar.gz`

###### Build
- `$ ./gradlew build`

###### Run
- `$ ./gradlew run`



## References
- "Advanced Analytics with Spark by Sandy Ryza, Uri Laserson, Sean Owen, and Josh Wills (O’Reilly). Copyright 2015 Sandy Ryza, Uri Laserson, Sean Owen, and Josh Wills, 978-1-491-91276-8."