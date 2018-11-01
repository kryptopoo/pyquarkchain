### TPS Competition Questionnaire

*Please replace the square brackets and the text in it with your answers*

**Number of CPUs**

160 cpus

**Memory (GB)**

3844 GB

**Storage (GB)**

SSD 500GB

**Network**

Google VPC Network

**Machine Type (Optional)**

Google Cloud Compute

**Command Lines for Running Cluster**

pypy3 pyquarkchain/quarkchain/cluster/cluster.py --clean --num_shards=1024 --num_slaves=128 --root_block_interval_sec=60 --minor_block_interval_sec=10 --devp2p_enable --devp2p_ip=35.224.102.139

pypy3 pyquarkchain/quarkchain/cluster/cluster.py --clean --mine --num_shards=1024 --num_slaves=128 --devp2p_enable --root_block_interval_sec=60 --minor_block_interval_sec=10 --devp2p_ip=35.232.32.169 --devp2p_bootstrap_host=35.224.102.139

pypy3 pyquarkchain/quarkchain/cluster/cluster.py --clean --num_shards=1024 --num_slaves=128 --devp2p_enable --root_block_interval_sec=60 --minor_block_interval_sec=10 --devp2p_ip=35.232.176.204 --devp2p_bootstrap_host=35.224.102.139

**Peak TPS**

16959.93

**Video URL**

https://youtu.be/9lmjkTqMVrY

**Output From `stats` Tool**

https://imgur.com/a/BeAV2mL


**Additional Comment**

[If you have special setup, e.g., running a single cluster over multiple machines, the above questionnaire might not fit. Note down
whatever you want us to know here to help evaluate the result.]
