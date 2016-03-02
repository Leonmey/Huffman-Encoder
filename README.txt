Q8 is implemented in Compress. Compress takes a PGM image and compresses it.
	compile Compress by inputting into the command line:
	gcc -std=c99 compress.c libpnm.c -o Compress

	Compress takes two arguments: filename of the image to be compressed, and filename to save compressed image as.
	run with ./Compress Argument1 Argument2



Q9 is implemented in Decompress. Decompress takes a compressed PGM image and decompresses it.
	compile Decompress by inputting into the command line:
	gcc -std=c99 decompress.c libpnm.c -o Decompress

	Decompress takes two arguments: filename of the compressed image, and filename to save decompressed image as.
	run with ./Decompress Argument1 Argument2



Q10 is implemented in Mae. Mae computes the Mean Absolute Error between two PGM images of the same dimensions.
	compile Mae by inputting into the command line:
	gcc -std=c99 mae.c libpnm.c -o Mae

	Mae takes two arguments: filename of the first PGM image, and filename of the second PGM Image.
	run with ./Mae Argument1 Argument2

