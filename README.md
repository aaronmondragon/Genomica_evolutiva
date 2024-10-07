# Genomica_evolutiva
Clases de la Maestria en Bioinformática y ciencias ómicas
#Código 1: Descargar sratoolkit
mkdir genomas;
grep ">" genomas.fasta ;
ls ;

wget https://ftp-trace.ncbi.nlm.nih.gov/sra/sdk/3.1.1/sratoolkit.3.1.1-ubuntu64.tar.gz -O stk.tar.gz
chmod +x stk.tar.gz #activar permisos
tar -vxzf stk.tar.gz  #descomprimir

export PATH=$PATH:$PWD/sratoolkit.3.0.10-ubuntu64/bin

