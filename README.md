# JAVE

The JAVE (Java Audio Video Encoder) library is Java wrapper on the ffmpeg
project. Developers can take take advantage of JAVE2 to transcode audio 
and video files from a format to another. In example you can transcode
an AVI file to a MPEG one, you can change a DivX video stream into a
(youtube like) Flash FLV one, you can convert a WAV audio file to a MP3 or a
Ogg Vorbis one, you can separate and transcode audio and video tracks, you can
resize videos, changing their sizes and proportions and so on.
Many other formats, containers and operations are supported by JAVE2.


## Requirements

JAVE requires a Java 8 or higher and a Windows, Linux OS or OS-X
on a i386 / 32 bit or amd64 / 64 bit hardware architecture.
JAVE can also be easily ported to other OS and hardware configurations, 
see the JAVE manual for details.


## Usage
For the documentation, please have a look at the project wiki pages here:
https://github.com/a-schild/jave2/wiki

or at this file 

https://github.com/a-schild/jave2/blob/master/jave-example/src/main/java/ws/schild/jave/example/DefaultFFMPEGLocatorTest.java

###For maven users, add this to your pom file.
It includes all binaries for the supported platforms
```
<!-- https://mvnrepository.com/artifact/ws.schild/jave-all-deps -->
<groupId>ws.schild</groupId>
<artifactId>jave-all-deps</artifactId>
<version>2.4.1</version>
```

###For gradle us this:
It includes all binaries for the supported platforms
```
// https://mvnrepository.com/artifact/ws.schild/jave-all-deps
compile group: 'ws.schild', name: 'jave-all-deps', version: '2.4.1'
```


Jave2 consists of two main components:
1. The `jave-core` dependency, which includes all the java code, which is platform independent
2. The `jave-native-<platform>` dependencies, which include the binary executables per platform

There exists a jave-all-deps project, which includes core and all windows und linux binaries.

## License

JAVE2 is Free Software and it is licensed under GPL 2 (you will find a copy of
the license bundled into the downloadable software distribution).


## Feedback

You can send comments to andre@schild.ws
For bug reports use the github site https://github.com/a-schild/jave2/issues


## Credits

Jave is based on the jave version from Carlo Pelliccia
The original project page with source code can be found here:

http://www.sauronsoftware.it/projects/jave/
