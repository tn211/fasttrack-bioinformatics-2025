### All commands below were executed using `fish` as my default shell.

---

#### displaying `samtools` version:

	[I] 01-quality-control ➜ micromamba list samtools                                                          (bioinfo)

	 ✭ List of packages in environment: "/Users/benzenesea/micromamba/envs/bioinfo"

	| Name      | Version  | Build       | Channel  |
	|-----------|----------|-------------|----------|
	| samtools  | 1.22.1   | h267f7b9_0  | bioconda |
  
---

#### creating a nested directory structure:

	[I] fasttrack-bioinformatics-2025 ➜ mkdir notes exercises data scripts
	 [I] fasttrack-bioinformatics-2025 ➜ ls                                                                     (bioinfo)

	README.md                                     notes/
	data/                                         scripts/
	exercises/

---

#### populating the directories with files:

	[I] fasttrack-bioinformatics-2025 ➜ touch notes/.gitkeep                                                   (bioinfo)
										 touch exercises/.gitkeep
										 touch data/.gitkeep
										 touch scripts/.gitkeep
                                      
---

#### using absolute paths:

	cd /Users/benzenesea/fasttrack-bioinformatics-2025/exercises

#### using relative paths:

	cd excersises
	nano exercises/01-quality-control.md

---

































  