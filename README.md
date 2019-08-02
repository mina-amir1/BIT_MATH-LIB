# BIT_MATH-LIB
Make an easy bit math logic with this library that contains +10 functions that handle all the bit math level for you.
#BIT_MATH LIB CREATED BY MINA AMIR
				0  1  0  1  0  1  0  1   YOUR BYTE
				----------------------
				7  6  5  4  3  2  1  0   YOUR BIT ORDER IN BIT_MATH LIB

                                           		        SYNTAX OF FUNCs                                                                                             

   RTRN_TYPE  |      FUNC_NAME(ARGUMENTS TYPES_DESCREPTION);//FUNC DISCREPTION                                                                                            
--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------
1. u8 (char)  |  set_bit(u8_byte needed to set, u8_no of bit needed CONCERNING THE ABOVE ORDER);//setting a bit from zero to one    
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2. u8 (char)  |  clr_bit(u8_byte needed to clear, u8_no of bit needed CONCERNING THE ABOVE ORDER);//clearing a bit from one to zero                                       
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
3. u8 (char)  |  get_bit(u8_byte needed to get the bit within it, u8_no of bit needed CONCERNING THE ABOVE ORDER);//return the status of a bit zero or one				   
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
4. u8 (char)  |  togg_bit(u8_byte needed to toggle, u8_no of bit needed CONCERNING THE ABOVE ORDER);//toggle a bit from a status to a different one    
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
5. u8 (char)  |  set_register(u8_byte needed register);//setting all bits of a byte to 1s				
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
6. u8 (char)  |  set_low_nibble(u8_byte needed);//setting the right 4 bits of a byte to 1s    
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
7. u8 (char)  |  clr_low_nibble(u8_byte needed);//clearing the right 4 bits of a byte 			
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
8. u8 (char)  |  set_high_nibble(u8_byte needed);//setting the left 4 bits of a byte to 1s		
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
9. u8 (char)  |  clr_high_nibble(u8_byte needed);//clearing the left 4 bits of a byte            
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
10.u8 (char)  |  togg_low_nibble(u8_byte needed);//toggle the right 4 bits of a byte from a status to a different one    
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
11.u8 (char)  |  togg_high_nibble(u8_byte needed);//toggle the left 4 bits of a byte from a status to a different one      
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
11.u8 (char)  |  assign_low_nibble(u8_byte needed , u8_number <=15 to assign);//put a number <=15 in the right 4 bits without changing the left ones   
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
12.u8 (char)  |  assign_high_nibble(u8_byte needed , u8_number >15&&<255 to assign);//put a number >15 and <255 in the left 4 bits without changing the right ones    
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 
