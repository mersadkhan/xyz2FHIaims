# xyz2FHIaims
 this code is under license of CC BY-NC 4.0 watch https://creativecommons.org/licenses/by-nc/4.0/

writed by: Mersad Mostaghimi
Email:Mersadkhan@gmail.com
version 0.2

INSTALLATION:
enter to the folder of the code and install it by :
        $sh install.sh
you code from its folder too.just ienter the to the folder and do this:
        $chmod +x xyz2FHIaims
now use it by:
        $/path/to/your/install/folder/xyz2FHIaims /path/to/your/xyzfile y/n
example:
        $./xyz2FHIaims /home/mersad/ch-4.xyz n

USE:
just call it with the path of your xyz file.if you want save the output to a file use "y" as third switch and if not use "n" that just display the answer:
       $xyz2FHIaims /path/to/your/xyzfile y/n

     example:
        $xyz2FHIaims /home/mersad/ch-4.xyz n

it will show you the FHI-aims geometry
 if you want save to a file ude the command below:
        $xyz2FHIaims /home/mersad/ch-4.xyz y


TEST:
enter in test folder for test see the benzen geometry:
     $cd test
     $xyz2FHIaims benzen.xyz
