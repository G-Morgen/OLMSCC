Below you can find TAppEncoder.exe for our OLMSCC.

The implementation is tested using:

Opencv version 2.4.9

HEVC test model: HM 16.0

Visual Studio 2013

Windows 10

Result: This folder contains the .txt file of 4  videos encoded by our OLMSCC. 

Streaming: This folder contains the .bin file of 4  videos encoded by our OLMSCC.If you want to obtain the .yuv file you can decode the .bin file using HM16.0 decoder (TAppDecoder.exe).

TAppEncoder.exe: Our OLMSCC encoder.

TAppDecoder.exe: HM16.0 decoder.

test.bat: Before testing, you need to install opencv 2.4.9 at disk E. Besides, you also need copy the corresponding sequence (YUV file) to the current folder.

Calculate_BDBRandBDPSNR.xlsm: You can use it to calculate BDBR and BDPSNR.
 
If you find any bug, or have some questions, please contact Chao Huang: huangchao_08@126.com