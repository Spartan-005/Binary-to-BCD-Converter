##Overview
I designed a digital circuit to convert an 8-bit binary number into Binary Coded Decimal (BCD) format by implementing the Double Dabble Algorithm. This approach allows for efficient conversion within a minimal number of clock cycles. The converted BCD result is then displayed on a 7-segment display, providing a clear and immediate representation of the binary input number in a decimal format.


##Task
To convert an 8-bit binary number into Binary Coded Decimal (BCD) format.


##Skills
Digital Electronics, Proteus


##Approach
+ **Shift and Process:** Shift the binary number left into a BCD shift register, while processing each bit.
+ **Adjust BCD Digits:** After each shift, add 3 to any 4-bit BCD group that is 5 or greater to ensure valid BCD representation.
+ **Obtain BCD Output:** After completing the shifts and adjustments, the BCD representation of the binary number is extracted from the register.


##Main Circuit
![image](https://github.com/user-attachments/assets/02893f9e-6487-4c82-8e6a-47f274d7953c)


##Subcircuit
![image](https://github.com/user-attachments/assets/2833d70b-e685-4981-8753-4c52b6b0fd0e)

