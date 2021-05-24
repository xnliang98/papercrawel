# papercrawler
Python script to download conference paper automatically, including the conferences and journals listed in https://aclweb.org/anthology/, such as ACL/EMNLP/NAACL/COLING/CL.

**TODO** Download from other conference (e.g. nips) 

# Requirement
python 3.6

# Example
To download summarization-related papers in ACL2020
```shell
python papercrawl.py --event naacl --year 2021 --keywords summ --data_dir data/ --cpus 8
```
If some papers fail to download, just run this script again.


> Copy from https://github.com/Zhujunnan/papercrawler.