### ECG Classification with CNN (Compare with filter num & size ) 



### 1. Install package for read datafile



- use mitdb

  

1. Install wfdb for open data file

   ```shell
   $ sudo apt-get install gcc libcurl4-openssl-dev libexpat1-dev
   $ wget https://physionet.org/physiotools/wfdb.tar.gz
   $ tar xvfz wfdb.tar.gz
   $ cd wfdb-10.m.n
   $ ./configure
   $ sudo make install
   $ make check
   ```

   

2. Install python package

   ```shell
   $sudo pip3 install wfdb
   ```

   

3. Download data

   ```shell
   python3 get_data.py
   ```

   

### 2. Run



1. **run cnn_compare_kernel.ipynb with jupyter-notebook**

