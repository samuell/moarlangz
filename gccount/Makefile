chr_y.fa:
	wget ftp://ftp.ensembl.org/pub/release-67/fasta/homo_sapiens/dna/Homo_sapiens.GRCh37.67.dna_rm.chromosome.Y.fa.gz
	gunzip Homo_sapiens.GRCh37.67.dna_rm.chromosome.Y.fa.gz
	mv Homo_sapiens.GRCh37.67.dna_rm.chromosome.Y.fa chr_y.fa

get_rawdata: chr_y

all: get_rawdata
