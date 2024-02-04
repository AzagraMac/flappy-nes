OUTFILE 	= flappy-bird.nes
PATHBUILD  	= ../build

default:
	nesasm flappy-bird.asm
	mv ${OUTFILE} ${PATHBUILD}
	
clean:
	rm -f ${PATHBUILD}/${OUTFILE} 
