MATLAB stands for MATrix LABoratory.  It is a FORTRAN package developed by 
Argonne National Laboratories for in-house use.  It provides comprehensive
vector and tensor operations in a package which may be programmed, either
through a macro language or through execution of script files.

Matlab is reentrant and recursive.  Functions supported include (but not 
by any means limited to) sin, cos, tan, arcfunctions, upper triangular,
lower triangular, determinants, matrix multiplication, identity, hilbert 
matrices, eigenvalues and eigenvectors, matrix roots and products, inversion
and so on and so forth.

The file available on the bulletin board as Matlab.arc contains an Amiga-ized
executable copy of MATLAB and the online help file, as well as this intro.

If you want the source code (over 300K) and a manual, or if your bulletin 
board only has this message and not the package, send $5.00 and a 3.5" 
disk to:

                           Jim Locker
                           4443 N. Hyland Ave.
                           Dayton, Oh 45424

The package is public domain, but of course postage and reproduction cost
money.  Believe me, this package is a bargain at the price.  Please feel free
to distribute the package.

The source was taken off a VAX 11/780.  It ran without modification (except the
file handler and some minor error handling) on an Amiga 1000 using ABSoft 
Fortran v2.2.  It will run in 512K environment.  I have seen it on IBM 
mainframes and IBM PCs.  

********************** A Sample Session ***********************************

For this session the <> character is the MATLAB prompt.

 <> a=<1 2 3;5 4 6;7 8 9>            <---  you enter this

 A     =                             <---  MATLAB response

     1.    2.    3.
     5.    4.    6.
     7.    8.    9.

 <> b=<5;6;7>                        <--- you enter this

 B     =                             <--- MATLAB response

     5.
     6.
     7.

 <> a*b             <--- you enter "multiply a and b"

 ANS   =            <--- MATLAB response

    38.
    91.
   146.

 <> b*a             <---you enter "multiply b and a"
    /--ERROR                         <--- MATLAB response
 INCOMPATIBLE FOR MULTIPLICATION

 <> det(a)         <--- Take the determinant of a

 ANS   =           <---MATLAB response

    18.

 <> exit           <--- you quit MATLAB

 total flops        34

 ADIOS
