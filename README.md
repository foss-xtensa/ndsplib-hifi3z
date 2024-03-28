
# HiFi_3z_NDSP
* NatureDSP Library for HiFi3 & HiFi3z DSP cores
* The source code is common to both HiFi-3 and HiFi-3Z cores.
* The xws provided supports both HiFi3 and HiFi3z.  
* Select the required HiFi-3 or HiFi-3z core for building, in both xws and linux environments. 

# The repo is organized as follows.

## xws:
  * Last stable release version of the NDSP contains two xws files.
  * An xws each, for the library-kernels and the test-driver.
    Ex : HiFi3z_VFPU_Library_v4_2_0.xws & HiFi3z_VFPU_Demo_v4_2_0.xws
  * Building and executing the xws in Xtensa Xplorer is described in the API Reference Document. 
  * Building and executing the source code in linux is described in the https://github.com/foss-xtensa/ndsplib-hifi3z/tree/main/doc. 
  * Detailed release documentation can be extracted from lib.xws/doc folder.

### Release v4.2.0 Brief: 
* Release Date : Mar 2024
* The source code has been updated to make it compatible with RJ-2024.3 tool chain.
* Verification & testing has been done with a very limited number of HiFi-3 and HiFi-3z cores,  RJ-2024.3 tool chain (LX8.0.3).
* Sanity testing has been done for backward compatibility on xt-clang using RI-2023.11 tool chain (LX7.1.10) cores.   

* Known issues: 
  - For dct functional regression in both -brief and -full, the test vectors are picked up from the sanity folder.   
   
## NDSP_HiFi3z
* This contains the source code (NDSP_HiFi3_v420.zip) along with make files that will build in linux environment.  

## doc folder
This contains help documentation on how to build the source code in linux and run the performance and functional regressions. 
