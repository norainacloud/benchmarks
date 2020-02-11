All executions with `openssl speed ecdsa`, no multi xxx or other options.\
Openssl on updated Ubuntu 18.04 (Openssl 1.1.1-1ubuntu2.1~18.04.5)

# A1.large
|                            | sign   | verify  |  sign/s | verify/s|
|----------------------------|--------:|---------:|--------:|--------:|
| 160 bits ecdsa (secp160r1) |  0.0006s |  0.0005s |  1733.8|  2118.2|
| 192 bits ecdsa (nistp192)  | 0.0007s  | 0.0006s  | 1478.6 | 1767.8|
| 224 bits ecdsa (nistp224)  | 0.0010s  | 0.0007s |  1025.0 | 1343.2|
| 256 bits ecdsa (nistp256)  | 0.0001s  | 0.0002s | 14115.7 | 4370.1|
| 384 bits ecdsa (nistp384)  | 0.0029s  | 0.0020s |   344.0 |  490.1|
| 521 bits ecdsa (nistp521)  | 0.0075s  | 0.0048s |   133.4 |  209.6|
| 163 bits ecdsa (nistk163)  | 0.0008s  | 0.0016s |  1252.9 |  634.0|
| 233 bits ecdsa (nistk233)  | 0.0012s  | 0.0023s |   865.9 |  439.4|
| 283 bits ecdsa (nistk283)  | 0.0024s  | 0.0048s |   410.8 |  208.2|
| 409 bits ecdsa (nistk409)  | 0.0050s  | 0.0099s |   198.9 |  101.1|
| 571 bits ecdsa (nistk571)  | 0.0107s  | 0.0212s |    93.1 |   47.3|
| 163 bits ecdsa (nistb163)  | 0.0008s  | 0.0017s |  1193.1 |  603.1|
| 233 bits ecdsa (nistb233)  | 0.0012s  | 0.0024s |   807.6 |  417.5|
| 283 bits ecdsa (nistb283)  | 0.0026s  | 0.0052s |   380.3 |  192.3|
| 409 bits ecdsa (nistb409)  | 0.0055s  | 0.0109s |   180.5 |   91.4|
| 571 bits ecdsa (nistb571)  | 0.0120s  | 0.0236s |    83.4 |   42.4|
| 256 bits ecdsa (brainpoolP256r1)  | 0.0011s  | 0.0009s  |  932.5  | 1098.6|
| 256 bits ecdsa (brainpoolP256t1)  | 0.0011s  | 0.0008s  |  941.3  | 1187.0|
| 384 bits ecdsa (brainpoolP384r1)  | 0.0029s  | 0.0022s  |  346.9  |  459.4|
| 384 bits ecdsa (brainpoolP384t1)  | 0.0029s  | 0.0020s  |  350.2  |  502.6|
| 512 bits ecdsa (brainpoolP512r1)  | 0.0056s  | 0.0039s  |  177.1  |  254.2|
| 512 bits ecdsa (brainpoolP512t1)  | 0.0056s  | 0.0036s  |  178.4  |  277.9|
 
# RPI 4B
|                            | sign   | verify  |  sign/s | verify/s|
|----------------------------|--------:|---------:|--------:|--------:|
 160 bits ecdsa (secp160r1) | 0.0011s | 0.0009s |  924.7 | 1168.4
 192 bits ecdsa (nistp192) | 0.0015s | 0.0012s |  651.3 |  844.0
 224 bits ecdsa (nistp224) | 0.0022s | 0.0017s |  446.7 |  593.5
 256 bits ecdsa (nistp256) | 0.0002s | 0.0006s | 4133.1 | 1602.4
 384 bits ecdsa (nistp384) | 0.0081s | 0.0056s |  123.1 |  180.1
 521 bits ecdsa (nistp521) | 0.0201s | 0.0134s |   49.7 |   74.5
 163 bits ecdsa (nistk163) | 0.0017s | 0.0033s |  594.9 |  302.4
 233 bits ecdsa (nistk233) | 0.0033s | 0.0065s |  304.7 |  154.6
 283 bits ecdsa (nistk283) | 0.0059s | 0.0116s |  168.7 |   85.9
 409 bits ecdsa (nistk409) | 0.0139s | 0.0272s |   71.8 |   36.7
 571 bits ecdsa (nistk571) | 0.0326s | 0.0636s |   30.7 |   15.7
 163 bits ecdsa (nistb163) | 0.0018s | 0.0035s |  554.1 |  283.7
 233 bits ecdsa (nistb233) | 0.0036s | 0.0071s |  278.3 |  141.6
 283 bits ecdsa (nistb283) | 0.0066s | 0.0130s |  151.5 |   77.1
 409 bits ecdsa (nistb409) | 0.0158s | 0.0310s |   63.2 |   32.2
 571 bits ecdsa (nistb571) | 0.0373s | 0.0728s |   26.8 |   13.7
 256 bits ecdsa (brainpoolP256r1) | 0.0030s | 0.0024s |  338.1 |  423.9
 256 bits ecdsa (brainpoolP256t1) | 0.0029s | 0.0022s |  342.2 |  457.3
 384 bits ecdsa (brainpoolP384r1) | 0.0081s | 0.0061s |  123.5 |  163.9
 384 bits ecdsa (brainpoolP384t1) | 0.0081s | 0.0056s |  123.4 |  177.9
 512 bits ecdsa (brainpoolP512r1) | 0.0176s | 0.0129s |   56.8 |   77.8
 512 bits ecdsa (brainpoolP512t1) | 0.0175s | 0.0118s |   57.0 |   85.0

# i5-6200U WSL
|                            | sign   | verify  |  sign/s | verify/s|
|----------------------------|--------:|---------:|--------:|--------:|
 160 bits ecdsa (secp160r1) | 0.0003s | 0.0003s | 3293.4 | 3550.4
 192 bits ecdsa (nistp192) | 0.0004s | 0.0003s | 2345.4 | 3017.6
 224 bits ecdsa (nistp224) | 0.0001s | 0.0002s | 11902.6 | 5227.8
 256 bits ecdsa (nistp256) | 0.0000s | 0.0001s | 31772.0 | 9849.4
 384 bits ecdsa (nistp384) | 0.0014s | 0.0011s |  696.9 |  898.2
 521 bits ecdsa (nistp521) | 0.0005s | 0.0009s | 2092.8 | 1123.0
 163 bits ecdsa (nistk163) | 0.0003s | 0.0006s | 2975.3 | 1543.7
 233 bits ecdsa (nistk233) | 0.0005s | 0.0010s | 2065.8 | 1022.3
 283 bits ecdsa (nistk283) | 0.0008s | 0.0016s | 1203.5 |  629.6
 409 bits ecdsa (nistk409) | 0.0014s | 0.0027s |  703.0 |  369.4
 571 bits ecdsa (nistk571) | 0.0031s | 0.0062s |  318.6 |  160.5
 163 bits ecdsa (nistb163) | 0.0004s | 0.0007s | 2745.6 | 1391.7
 233 bits ecdsa (nistb233) | 0.0005s | 0.0009s | 2065.0 | 1078.3
 283 bits ecdsa (nistb283) | 0.0009s | 0.0017s | 1175.2 |  605.8
 409 bits ecdsa (nistb409) | 0.0014s | 0.0028s |  692.8 |  351.7
 571 bits ecdsa (nistb571) | 0.0032s | 0.0060s |  308.3 |  166.9
 256 bits ecdsa (brainpoolP256r1) | 0.0006s | 0.0006s | 1554.6 | 1544.1
 256 bits ecdsa (brainpoolP256t1) | 0.0007s | 0.0005s | 1462.5 | 1918.3
 384 bits ecdsa (brainpoolP384r1) | 0.0014s | 0.0011s |  690.5 |  935.8
 384 bits ecdsa (brainpoolP384t1) | 0.0014s | 0.0011s |  703.5 |  950.9
 512 bits ecdsa (brainpoolP512r1) | 0.0021s | 0.0017s |  487.6 |  575.4
 512 bits ecdsa (brainpoolP512t1) | 0.0020s | 0.0015s |  488.3 |  659.1
 
# Gold 6134
|                            | sign   | verify  |  sign/s | verify/s|
|----------------------------|--------:|---------:|--------:|--------:|
 160 bits ecdsa (secp160r1) | 0.0002s | 0.0002s | 4739.5 | 5479.1
 192 bits ecdsa (nistp192) | 0.0003s | 0.0002s | 3928.7 | 4546.9
 224 bits ecdsa (nistp224) | 0.0001s | 0.0001s | 16663.9 | 7429.2
 256 bits ecdsa (nistp256) | 0.0000s | 0.0001s | 47634.3 | 15412.7
 384 bits ecdsa (nistp384) | 0.0010s | 0.0007s | 1024.8 | 1415.4
 521 bits ecdsa (nistp521) | 0.0003s | 0.0006s | 3403.2 | 1745.1
 163 bits ecdsa (nistk163) | 0.0002s | 0.0004s | 4431.8 | 2312.5
 233 bits ecdsa (nistk233) | 0.0003s | 0.0006s | 3226.2 | 1666.6
 283 bits ecdsa (nistk283) | 0.0005s | 0.0010s | 1936.1 |  960.2
 409 bits ecdsa (nistk409) | 0.0009s | 0.0017s | 1134.3 |  583.4
 571 bits ecdsa (nistk571) | 0.0021s | 0.0038s |  479.9 |  259.9
 163 bits ecdsa (nistb163) | 0.0002s | 0.0004s | 4448.6 | 2248.2
 233 bits ecdsa (nistb233) | 0.0003s | 0.0006s | 3246.2 | 1623.6
 283 bits ecdsa (nistb283) | 0.0005s | 0.0011s | 1864.4 |  942.6
 409 bits ecdsa (nistb409) | 0.0009s | 0.0018s | 1101.8 |  562.0
 571 bits ecdsa (nistb571) | 0.0021s | 0.0042s |  473.3 |  239.0
 256 bits ecdsa (brainpoolP256r1) | 0.0004s | 0.0003s | 2416.5 | 2863.1
 256 bits ecdsa (brainpoolP256t1) | 0.0004s | 0.0004s | 2466.8 | 2721.8
 384 bits ecdsa (brainpoolP384r1) | 0.0010s | 0.0007s | 1036.7 | 1352.1
 384 bits ecdsa (brainpoolP384t1) | 0.0009s | 0.0007s | 1059.3 | 1441.2
 512 bits ecdsa (brainpoolP512r1) | 0.0014s | 0.0010s |  718.5 |  967.0
 512 bits ecdsa (brainpoolP512t1) | 0.0014s | 0.0010s |  726.6 | 1014.6
 
 
# i7-8550U (Fedora 31, Openssl 1.1.1d)
|                            | sign   | verify  |  sign/s | verify/s|
|----------------------------|--------:|---------:|--------:|--------:|
224 bits ecdsa (nistp224) | 0.0001s | 0.0001s | 19643.6 | 8538.7
 256 bits ecdsa (nistp256) | 0.0000s | 0.0001s | 43604.6 | 15020.2
 384 bits ecdsa (nistp384) | 0.0010s | 0.0007s | 1025.9 | 1362.6
 521 bits ecdsa (nistp521) | 0.0003s | 0.0006s | 3424.5 | 1715.5 

# c5.large Xeon 8124M
|                            | sign   | verify  |  sign/s | verify/s|
|----------------------------|--------:|---------:|--------:|--------:|
 160 bits ecdsa (secp160r1) | 0.0002s | 0.0002s | 4726.4 | 5265.8
 192 bits ecdsa (nistp192) | 0.0003s | 0.0002s | 3865.6 | 4385.9
 224 bits ecdsa (nistp224) | 0.0001s | 0.0001s | 16898.0 | 7212.7
 256 bits ecdsa (nistp256) | 0.0000s | 0.0001s | 46503.4 | 14933.2
 384 bits ecdsa (nistp384) | 0.0010s | 0.0007s | 1000.4 | 1355.3
 521 bits ecdsa (nistp521) | 0.0003s | 0.0006s | 3282.6 | 1693.3
 163 bits ecdsa (nistk163) | 0.0002s | 0.0005s | 4302.4 | 2172.0
 233 bits ecdsa (nistk233) | 0.0003s | 0.0006s | 3101.0 | 1570.0
 283 bits ecdsa (nistk283) | 0.0005s | 0.0011s | 1827.4 |  927.5
 409 bits ecdsa (nistk409) | 0.0009s | 0.0018s | 1078.4 |  551.5
 571 bits ecdsa (nistk571) | 0.0021s | 0.0041s |  483.4 |  246.9
 163 bits ecdsa (nistb163) | 0.0002s | 0.0005s | 4098.9 | 2077.3
 233 bits ecdsa (nistb233) | 0.0003s | 0.0007s | 2993.4 | 1514.5
 283 bits ecdsa (nistb283) | 0.0006s | 0.0011s | 1735.3 |  880.6
 409 bits ecdsa (nistb409) | 0.0010s | 0.0019s | 1023.4 |  521.3
 571 bits ecdsa (nistb571) | 0.0022s | 0.0043s |  450.0 |  230.0
 256 bits ecdsa (brainpoolP256r1) | 0.0004s | 0.0004s | 2386.0 | 2664.7
 256 bits ecdsa (brainpoolP256t1) | 0.0004s | 0.0004s | 2377.2 | 2774.2
 384 bits ecdsa (brainpoolP384r1) | 0.0010s | 0.0008s | 1004.3 | 1272.2
 384 bits ecdsa (brainpoolP384t1) | 0.0010s | 0.0007s | 1018.8 | 1356.2
 512 bits ecdsa (brainpoolP512r1) | 0.0014s | 0.0011s |  699.2 |  909.2
 512 bits ecdsa (brainpoolP512t1) | 0.0014s | 0.0010s |  703.3 |  964.5
 
 
# z1d.large Xeon 8151
|                            | sign   | verify  |  sign/s | verify/s|
|----------------------------|--------:|---------:|--------:|--------:|
 160 bits ecdsa (secp160r1) | 0.0002s | 0.0002s | 5524.3 | 6191.7
 192 bits ecdsa (nistp192) | 0.0002s | 0.0002s | 4501.7 | 5174.5
 224 bits ecdsa (nistp224) | 0.0001s | 0.0001s | 19897.2 | 8496.8
 256 bits ecdsa (nistp256) | 0.0000s | 0.0001s | 54820.9  |17564.1
 384 bits ecdsa (nistp384) | 0.0008s | 0.0006s | 1189.3 | 1573.6
 521 bits ecdsa (nistp521) | 0.0003s | 0.0005s | 3867.5 | 1993.9
 163 bits ecdsa (nistk163) | 0.0002s | 0.0004s | 5063.1 | 2534.6
 233 bits ecdsa (nistk233) | 0.0003s | 0.0005s | 3637.3 | 1845.8
 283 bits ecdsa (nistk283) | 0.0005s | 0.0009s | 2149.6 | 1089.2
 409 bits ecdsa (nistk409) | 0.0008s | 0.0015s | 1270.2 |  650.1
 571 bits ecdsa (nistk571) | 0.0018s | 0.0034s |  566.1 |  290.4
 163 bits ecdsa (nistb163) | 0.0002s | 0.0004s | 4832.1 | 2436.3
 233 bits ecdsa (nistb233) | 0.0003s | 0.0006s | 3521.5 | 1784.8
 283 bits ecdsa (nistb283) | 0.0005s | 0.0010s | 2043.9 | 1036.8
 409 bits ecdsa (nistb409) | 0.0008s | 0.0016s | 1205.6 |  613.7
 571 bits ecdsa (nistb571) | 0.0019s | 0.0037s |  527.7 |  270.8
 256 bits ecdsa (brainpoolP256r1) | 0.0004s | 0.0003s | 2803.3 | 3189.7
 256 bits ecdsa (brainpoolP256t1) | 0.0004s | 0.0003s | 2807.8 | 3267.1
 384 bits ecdsa (brainpoolP384r1) | 0.0009s | 0.0007s | 1159.4 | 1494.6
 384 bits ecdsa (brainpoolP384t1) | 0.0008s | 0.0006s | 1203.3 | 1633.3
 512 bits ecdsa (brainpoolP512r1) | 0.0012s | 0.0010s |  817.2 | 1046.2
 512 bits ecdsa (brainpoolP512t1) | 0.0012s | 0.0009s |  833.9 | 1135.8

 # E5-2687Wv3 (3.1GHz)
|                            | sign   | verify  |  sign/s | verify/s|
|----------------------------|--------:|---------:|--------:|--------:|
 521 bits ecdsa (nistp521)  | 0.0004s  | 0.0010s  | 2388.9  |  975.9

 #  AMD EPYC 7401P (2GHz)
 |                            | sign   | verify  |  sign/s | verify/s|
|----------------------------|--------:|---------:|--------:|--------:|
 160 bit ecdsa (secp160r1) | 0.0004s | 0.0003s | 2621.7 | 3626.2
 192 bit ecdsa (nistp192) | 0.0004s | 0.0003s | 2240.2 | 3031.1
 224 bit ecdsa (nistp224) | 0.0001s | 0.0002s | 12009.5 | 5075.5
 256 bit ecdsa (nistp256) | 0.0000s | 0.0001s | 20062.4 | 7900.9
 384 bit ecdsa (nistp384) | 0.0016s | 0.0011s |  625.4 |  940.7
 521 bit ecdsa (nistp521) | 0.0004s | 0.0007s | 2229.1 | 1344.7
 163 bit ecdsa (nistk163) | 0.0019s | 0.0006s |  524.8 | 1736.3
 233 bit ecdsa (nistk233) | 0.0039s | 0.0008s |  258.2 | 1239.4
 283 bit ecdsa (nistk283) | 0.0061s | 0.0013s |  163.7 |  746.7
 409 bit ecdsa (nistk409) | 0.0138s | 0.0022s |   72.6 |  444.7
 571 bit ecdsa (nistk571) | 0.0299s | 0.0045s |   33.4 |  219.8
 163 bit ecdsa (nistb163) | 0.0019s | 0.0006s |  527.5 | 1665.7
 233 bit ecdsa (nistb233) | 0.0038s | 0.0008s |  266.3 | 1239.7
 283 bit ecdsa (nistb283) | 0.0059s | 0.0014s |  169.3 |  724.3
 409 bit ecdsa (nistb409) | 0.0136s | 0.0024s |   73.3 |  421.1
 571 bit ecdsa (nistb571) | 0.0299s | 0.0049s |   33.4 |  204.3