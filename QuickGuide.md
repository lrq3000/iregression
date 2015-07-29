A quick guide to use Delta Debugging (DD) and Augmented Delta Debugging (ADD)


## Download and decompression ##
Download [expr.tar.gz](http://iregression.googlecode.com/files/expr.tar.gz) and
decompress it:

```
tar zxvf expr.tar.gz
```

## Isolate failure-inducing changes ##
Go to directory 'find-a/experiment' and just type:
```
python dd.py
```
After several minutes, the failure-inducing change is identified and stored in a file named `isolated`.

or
```
python add.py
```
After several minutes, the failure-inducing change is identified and stored in a file named `isolated_add`.