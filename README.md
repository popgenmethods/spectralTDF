`spectralTDF`, version 1.0.0

### Table of Contents
* [SUMMARY](#SUMMARY)
* [LICENSES](#LICENSES)
* [REQUIREMENTS](#REQUIREMENTS)
* [USAGE](#USAGE)
* [EXTERNAL LIBRARIES LICENSES](#EXTERNAL-LIBRARIES-LICENSES)
* [CONTACT](#CONTACT)
* [VERSION HISTORY](#VERSION-HISTORY)


### SUMMARY:

`spectralTDF` is a software program for computing the transition density function of the Wright-Fisher diffusion process in a population of piecewise constant size. spectralTDF is an implementation of the method described in:

Matthias Steinrücken, Ethan M Jewett, and Yun S. Song (2016). [SpectralTDF: transition densities of diffusion processes with time-varying selection parameters, mutation rates and effective population sizes](https://doi.org/10.1093/bioinformatics/btv627). Bioinformatics. 32:795–797.



### LICENSES:

The source code is released under the GNU General Public License, version 3.  The full text of the license can be found at http://www.gnu.org/licenses/.

This software comes packaged with several external libraries. See Section [EXTERNAL LIBRARIES LICENSES](#EXTERNAL-LIBRARIES-LICENSES), for the respective license information and download links.


### REQUIREMENTS:

`spectralTDF` requires JRE 1.7 or higher to run.


### USAGE:

Download the java-executable file [spectralTDF.jar](https://github.com/popgenmethods/spectralTDF/raw/main/spectralTDF.jar) and place it in a convenient location on your computer.  To run `spectralTDF`, open a command terminal and switch to the directory containing `spectralTDF.jar`. Execute

```
java -cp spectralTDF.jar TDF.spectralTDF <arguments>
```

See the [user manual](https://github.com/popgenmethods/spectralTDF/raw/main/SpectralTDFuserManual.pdf) for further details.



### EXTERNAL LIBRARIES LICENSES:

The following external libraries are included in this release of spectralTDF:


- `JSAP-2.1.jar`
	Download from http://sourceforge.net/projects/jsap/files/jsap/2.1/ (alt: http://www.martiansoftware.com/jsap/).
	License: GNU Library or Lesser General Public License version 2.0 (LGPLv2) (http://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)

- `arpack_combined_all.jar`
	Download from http://en.sourceforge.jp/projects/sfnet_f2j/releases/
	License: BSD License

- `lapack_simple.jar`
	Download jlapack-0.8.tgz from http://www.netlib.org/java/f2j/ and unpack. lapack_simple.jar can be found in this archive.
	License: Custom License:
	Copyright © 2015 The University of Tennessee. All rights reserved.

	Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met: 
	- Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer. 
	- Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer listed in this license in the documentation and/or other materials provided with the distribution. 
	- Neither the name of the copyright holders nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

	This software is provided by the copyright holders and contributors "as is" and any express or implied warranties, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose are disclaimed. in no event shall the copyright owner or contributors be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or profits; or business interruption) however caused and on any theory of liability, whether in contract, strict liability, or tort (including negligence or otherwise) arising in any way out of the use of this software, even if advised of the possibility of such damage.


### CONTACT:

Please contact ejewett@berkeley.edu or steinrue@uchicago.edu with bugs, comments, or questions regarding the software.


### VERSION HISTORY:

1.0.0: Initial release.