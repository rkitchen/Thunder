# Thunder
Miscellaneous tools for RNA and protein analysis

Usage:	 java -Xmx2G -jar Thunder.jar \<Command\>

Available \<Command\> options: 

	GetSequenceLengths            | Get the distribution of sequence lengths in a FASTA/Q file
	FastaHeaderGrep               | Filter fasta sequences based on the sequence ID
	RemoveFastaDuplicates         | Filter fasta sequences to remove duplicate sequence headers
	FilterFastxByIDList           | Filter fasta/q sequences based on a list of sequence IDs
	FilterSequencesByLength       | Filter fasta or fastq sequences based on some maximum sequence length
	ProcessFastqWithRandomBarcode | Filter fasta or fastq sequences based on some maximum sequence length
	FindAdapter                   | Determine most likely 3' adapter sequence from fastq reads
	RemoveHomopolymerRepeats      | Filter fasta or fastq sequences based on sequence composition
	MatchPairedEndSequences       | Match paired-end fastq sequences based on readID
	GTF2Fasta                     | Extract GTF coordinates from FASTA sequence(s)
	Fasta2Fastq                   | Convert FASTA sequence(s) to FASTQ sequence(s)
	Fastq2Fasta                   | Convert FASTQ sequence(s) to FASTA sequence(s)
	Fastx_ReverseComplement       | Reverse complement FASTA or FASTQ sequence(s)
	ParseTandemOutput             | Process X!Tandem MS/MS-spectra alignments and output summary table
	CIGAR_2_PWM                   | Reads SAM alignments and converts the CIGAR strings to a position-weight matrix
	ReadCoverage                  | Reads SAM/BAM alignments to the TRANSCRIPTOME and calculates read coverage consistency
	FootprintFrameAnaysis         | Analyse ribosome footprint alignments in terms of fidelity to annotated coding frames
	PeptideDigest                 | Enzymatically digest a protein reference
