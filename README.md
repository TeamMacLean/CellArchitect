# CellArchitect

Version: 1.07 	

The Silke Robatzek Group
The Sainsbury Laboratory, Norwich Research Park, Norwich, UK

## Contact
Dr Ji Zhou
email: ji.zhou@tsl.ac.uk, silke.robatzek@tsl.ac.uk

## System Requirements:
To allow use of this script, the Acapella framework (v2.0 or above) and Windows XP are required. 

## User Manual: 
This software solution is designed to recognise microtubule (MT) and monitor MT pattern changes induced by  different chemicals. The algorithm can be used for actin as well. Output fields (in a variety of CSV files) quantify features such as size, shape, fluorescent signal intensity, and pathogen growth patterns (e.g. total length and spreading area). In order to measure callose deposits as well as detect callose spreading networks, users need to follow the following instructions: 

		*Selecting "Image Directory" selection to tell CalloseMeasurer where to read microscopic images  
		*If users would like to only detect only big callose deposits, please tick the "Include large callose" selection 
		*If users would like to only detect only small callose deposits, please tick the "Include small callose" selection
  	*If users would like to only detect both small and big callose deposits, please tick both "Include small callose" and "Include large callose" selections
		*If users would like to preview analysed images within the Acapella framework, please tick "Show Illustration" selection, otherwise analysed images will be exported to the result folder, which will be generated by CalloseMeasurer during the batch process 
		*If users would like to remove detected objects attached to the image border, please tick the "Remove objects 
			attached to the image border" selection.
 		*If users would like to detect spreading callose networks, please tick the "Detect Callose Network" selection -  be aware that this function is time-consuming. Although the computation time depends on computer hardware,  the version of the Acapella system used for the analysis, and the complexity of the pathogen growth patterns, CalloseMeasurer normally needs to spend 5-6 minutes to construct a modestly complicated callose network. However users could always enter a smaller distance threshold (in pixel value) before constructing spreading callose networks. The distance threshold can be entered in the input box "The Distance Threshold of Callose Networks". The default value is 25 pixels, which can be changed by the software according to the average size (callose diameters and full length of recognised objects) of callose deposits.  
		* Users can select the input image format on the "Image Format" dropdown list - TIFF, PNG, BMP, and JPG 
			formats can be read and processed by CalloseMeasurer. The default input image format is TiF/TIFF files

This software solution performs image analysis functions such as image enhancement, object segmentation, filtering  noise objects, splitting fused callose signals, edge-based measurement, and construct networks for detecting pathogen growth patterns in leaf tissues. New functions can be added as external procedures or internal functions. 
		 
 
 	Copyright: (C) The Sainsbury Laboratory


