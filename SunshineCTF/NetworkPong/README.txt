After connected I played arround with the input and tried to figure out what worked and didnt work. I did some research
on different bash formating and found out about {} command notation. This program expects a ip address as input.
It worked with the input of "127.0.0.1" and "127.0.0.1}&&{echo 'hello'". Both worked the same so the program is using the {} command notation.
Then I tried "127.00.0.1} && {cat,flag.txt". This did not work as it appears that it is scannning the input for key words such as cat.
We recieved an error message of "Error: Do not mention body parts, felines, or body parts of felines."
Next I tried "127.00.0.1} && {grep,-r"
After looking through the output I found the flag.
Flag: sun{pin9_pin9-pin9_f1@9_pin9}