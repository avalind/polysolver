BootStrap:docker
From: sachet/polysolver:v3

%post

     mkdir /data/
     # mv /home/polysolver /usr/local/libexec/polysolver
     # mv /home/samtools /usr/local/libexec/samtools
     export PSHOME=/home/polysolver
     export SAMTOOLS_DIR=/home/samtools
     export JAVA_DIR=/usr/bin
     export NOVOALIGN_DIR=$PSHOME/binaries

     export GATK_DIR=$PSHOME/binaries
     export MUTECT_DIR=$PSHOME/binaries
     export STRELKA_DIR=/usr/local/libexec

     chmod 777 -R /usr/local/libexec
