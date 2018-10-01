# Script to identify take DNA sequence to be split into siRNA sized probes and matched against a reference database

```
usage: ProbeTest.py [-h] -i I -d D [-w W] [-a A] [-e E] [-p P]

Provide a region of DNA/RNA to be sliced to test for matches against a
reference

optional arguments:
  -h, --help  show this help message and exit
  -i I        [REQUIRED] | DNA segment you want to slice for probes (FASTA
              FORMAT)
  -d D        [REQUIRED] | Blast database you want to search against (make
              sure it is discoverable or give full path)
  -w W        Window length of the probes you want to test | default = 21
  -a A        Number of cores you want to blast with | default = 1
  -e E        Maximum e-value for blastn-short | default = 0.05
  -p P        Minimum required percentage identity for blastn-short | default
              = 80
```
