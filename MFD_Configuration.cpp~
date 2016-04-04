#include<iostream>
#include<string>
#include<map>
#include<stdlib.h>
#include<sstream>

#include"MFD_Configuration.h"


using namespace std;

/*************************************************************************
 *
 * Constructor for MFD_Configuration
 *
 * **********************************************************************/

MFD_Configuration::MFD_Configuration(int argc,char* argv[]) : Configuration(argc,argv){
 
   //Initializing the default values for MFD parameters
 
   // Four types of Kernels:
   // kernel0: mini_flux_div_mini
   // kernel1: mini_flux_div_explain
   // kernel2: mini_flux_div_baseline
   // kernel3: mini_flux_div_overlapped
   addParamInt("kernel", 'k' , 4 , "--The kernel");

   // Number of Cells in a single dimension of a single box.
   addParamInt("numCell", 'c' , 128 , "--Number of Cells in a single dimension of a single box");

   //Number of independent boxes to process.
   addParamInt("numBox",'b', 32 , "--Number of independent boxes to process");
  

}  

