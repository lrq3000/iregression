Description of supplement files.

# Applying [BitBlaze](http://bitblaze.cs.berkeley.edu/) to Diff #

We use temu-1.0 to obtain a trace file named "diff.p.tr" when invoking diffutils-2.8.1 with the command
```
diff -u a b
```
(for details of the command, see [this link](http://bugs.debian.org/cgi-bin/bugreport.cgi?bug=577832)). However, vine-1.0 failed to convert the trace file into VINE intermediate representation, raising an error message
```
Fatal error: exception Vine.VineError("label_to_addr given non address-like label")
```

# Test Input of libPNG #
The regression-revealing input is
```
pngtest bug.png
```

# Test Input of TCPflow #
The regression-revealing input is

```
tcpflow -r 36.pcap
```