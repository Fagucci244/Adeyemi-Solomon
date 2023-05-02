My Answers to subnet masking questions       

These are the explanations to all my answers:

1.    Answer 4.(30) = (255.255. 255.224) an octet is 0-254.. 254-224=30

2.    Answer 2.(255.255.224) = 255.224 classful subnet mask can be used.

3.    Answer 4.(16.45.12) =This means we have a block size of 4 and our subnets are 0, 4, 8, 12, 16, etc. Address 14 is in the 12 subnet.

4.    Answer 3. (10.5.64)255.255.255.240, which means that our block size is 16 in the fourth octet. 0, 16, 32, 48, 64, 80,etc.The host is in the 64             subnet.

5.    Answer 1.(255.255.255.248) has a block size of 8 in the fourth octet. This means the subnets are 0, 8, 16, 24, etc. 10 is in the 8 subnet. The             next subnet is 16, so 15 is the broadcast address.

6.    Answer 3.(510 subnets and 126 hosts) Class B network has the form N: N: H: H, the default subnet mask is 16 bits.
      There are additional 7 bits to the default subnet mask. the total number of bits in 
      the subnet are 16+7 = 23.
      while the host is 32-23 = 9 bits for assigning to hosts
      7 bits of subnet mask corresponds to 2^7-2 = 128-2 reserved for the host = 126 subnets
      9 bits belonging to host addresses correspond to 2^9-2 reserved for the host = 512-2 = 510 hosts
      The answer will  510 hosts and 126 subnets
 
7.    Answer 4. 2^16-2=65534. The number of host that can be addressed is 65534

8.    Answer 2. converting this binary–01101101 to decimal 64+32+8+4+1=109

9.    Answer 2&3

10.   Answer 1&4

11.   Answer 1. 1.1.1.0/24 is a class A address 0-126 range.

12.   Answer 2. The mask 255.255.255.224 provides 8 subnets, each with 30 hosts.

13.   Answer 3. The mask 255.255.255.224 provide 30 host each

14.   Answer 1. 172.16.112.0... A /25 mask is 255.255.255.128. Used with a Class B network, the third and fourth octets are used for subnetting with a           total of 9 subnet bits, 8 bits in the third octet and 1 bit in the fourth octet.

15.   Answer 1. /25 mask is 255.255.255.128. Class B network, the third and fourth octets are used for subnetting with a total of 9 subnet bits, 8 bits in       the third octet and 1 bit in the fourth octet.

16.   Answer 1. /29 (255.255.255.248), has only 3 host bits. Six hosts is the maximum number of hosts on this LAN.

17.   Answer 3. /221 is 255.255.248.0, which means we have a block size of 8 in the third octet, so we just count by 8 until we reach 66. The subnet is           64.0

18.   Answer 2. (8 subnets, 8,190 hosts each) 19-32=13bits for the host portion 2^13-2 = 8,190.

19.   Answer 1.  /29 (255.255.255.248) has a block size of 8 in the fourth octet. This means the subnets are 0, 8, 16, 24, 32, etc. 10 is in the 8 subnet.       The next subnet is 16, so 15 is the broadcast address.

20.   Answer 4.  00101001 - 32+8+1=41.

21.   Answer 4.  To delineate the network portion of the address from the host portion.

22.   Answer 2.  ipconfig - use this command on a Windows system to find your IP address.

23.   Answer 2.  There's 8bits in every octect.



Here is the PDF version of my answers.



[Subnetting Questions1.pdf](https://github.com/Fagucci244/Adeyemi-Solomon/files/11365883/Subnetting.Questions1.pdf)








