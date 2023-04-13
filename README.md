# Image-Compressing-DCT-Quality_Factor
A General Image Compression using DCT was empployed. 

Rather than proceeding with the Standard Quantization matrix which is needed during the process of Quantization, A Qualtiy Factor(QF) parameter is introduced to control the rate of Compression by manipilating the standard Quantization Matrix.

QF range could vary, although lower value would imply lower Quality of Image and hence Higher Compression.
Whereas, Higher QF value would imply Higher Quality of Image and therefore lower compression.


Various Quality parameters are taken into consideration(PSNR,SSNM,MSE). A parameter called Brisque score could also be used which results in a range of(1-100) where lower value being a good quality Image and Higher value represent a bad quality.  


Code Execution:

1.Download this Jupyter file and add it in your Google Colab

2.Upload your testing Image in Sample data section of Colab

3.Copy the Image path

4.Modify the path in Section1 imread part.

5.Under Runtime section in Navbar, select "Run all"
