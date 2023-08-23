HR>
HR>
HR>en
HR#
HR#
HR#

HR#conf term
Enter configuration commands, one per line.  End with CNTL/Z.

HR(config)#int f0/0
HR(config-if)#ip helper-address 11.0.0.2
HR(config-if)#
HR(config-if)#exit
HR(config)#
HR(config)#
HR(config)#end

HR#
HR#show ip dhcp binding
IP address       Client-ID/              Lease expiration        Type
                 Hardware address
10.0.0.2         0002.1755.A575           --                     Automatic
10.0.0.3         0090.2114.5818           --                     Automatic
HR#
HR#
