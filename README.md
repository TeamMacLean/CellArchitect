# CellArchitect


 Version: 1.15
 Changes: Changed the density calculation, update stomata detection, and cell selection criteria to includedensity detection at the cell level

The Silke Robatzek Group
The Sainsbury Laboratory, Norwich Research Park, Norwich, UK

## Contact
Dr Ji Zhou
email: ji.zhou@tsl.ac.uk, silke.robatzek@tsl.ac.uk

## System Requirements:
To allow use of this script, the Acapella framework (v2.0 or above) and Windows XP are required. 

## User Manual: 

This software solution is designed to recognise microtubule (MT) and measure MT pattern changes induced by different chemicals. The algorithm is capable of detecting other microfilament structure such as actin as well. Output fields (in a variety of CSV files) quantify features such as size, shape, fluorescent signal intensity, and MT patterns (e.g. MT lengths). Users need to follow the following instructions to execute the CellArchitect:

		* Selecting "Image Directory" to choose the image location of Opera images.
		* If the user wants to use Voronoi diagrams to present MT distribution, tick the "Produce Voronoi
          Diagram" selection.
		* If the user wants to generate a time-lapse movie of the flex file to present the morphological changes
          of MT structure, tick "Produce an AVI video".
		* Users can change the value in "Stack No" input box to defined the number of z-stacks in a flex file that
          need to be analysed.
		* Users can change the value in "Camera No" input box to defined the number of laser cameras used in imaging.
		* If users want to preview analysed images within the Acapella framework, tick "Show Illustration".
		* A user can change the frames per second input to produce avi movies with different key frames.


This software solution performs traditional image analysis functions such as image enhancement, object segmentation, denoise, edge-based measurements, and skeletonisation. When adding new functions to CellArchitect, please add them as external procedures or internal functions to maintain software architecture.
		 
 
