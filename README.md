# copy

There is nothing more frustrating that waiting for a cp to finish on the command line...

Just use [pv](http://www.ivarch.com/programs/pv.shtml) to monitor it...

On Debian-like OS :

> apt-get install pv
> copy input output
>> 47.7MiB 0:00:00 [ 134MiB/s] [=====================================================================>] 100%            
>> 97635+1 records in
>> 97635+1 records out
>> 49989534 bytes (50 MB) copied, 0.317964 s, 157 MB/s
