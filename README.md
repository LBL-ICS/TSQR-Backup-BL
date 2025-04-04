# TSQR-Backup-BL
This is a backup repository for the TSQR design by Blair

PMAXIMOFF: 
The 2 sets of test environments for the TSQR can be found at pmaximoff at /home/taylorb8409/Desktop/TSQR_test_environments/. 
The folder named TSQR_functional_verification has the test environment for the real number version, and the other folder called TSQR_Chisel_BRAM_IP_Complex is for the complex version. These test benches were manually manipulated for different test cases, so they may need some adjustments to work correctly. (edited) 

The vivado project at pmaximoff: /home/taylorb8409/st16_cplx/ is ready to run simulation and get results with no changes
There is also a /home/taylorb8409/ST_32_cplx/ and /home/taylorb8409/ST_64_cplx/ which should be good to go as well

WMAXIMOFF
•	/home/taylorb8409/Desktop/new_mosaic_131  contains the real number TSQR mosaic project. 
•	/home/taylorb8409/Desktop/complex_tsqr_mosaic/ contains the complex version mosaic. 
•	/home/taylorb8409/Desktop/open-nic-shell_mosaic_cplx_tsqr/ should be the opennic shell that runs the complex tsqr on the FPGA. 
•	/home/taylorb8409/Desktop/open-nic-shell-lbnl-newMosaicIP_int/ contains the real version TSQR FPGA stuff. 
•	/home/taylorb8409/Desktop/new_ver/ contains the mosaic of the real tsqr and fft integration. 
Which one is the tsqr complex verification env? Or how do you verify the complex tsqr?
•	/home/taylorb8409/Desktop/TSQR_Chisel_BRAM_IP_Complex/. This has all the files. I believe I always added the files to a Vivado project, but I cannot recall. Let me see if it works with modelsim really quick
