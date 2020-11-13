 A food fest is organised at the  JLN stadium. The stalls from different sates and cities have been set up. To make the fest more interesting, multiple games have been arranged which 
 can be played by the people to win the food vouchers. One such game to win the food vouchers is described below:
 
 There are N number of boxes arranged in a single queue. Each box has an integer I written on it. From the given queue, the particular has to select two contiguous subsequences A and B of the same size. The selected subsequences should be such that the summation of the product of the boxes should be maximum. The product is not calculated normally though. To make the game interesting, the first box of subsequences A is to be multiplied by the last box of subsequence B. The second box of subsequence A is to be multiplied by the second last box of sequence B and so on. All the products thus obtained are then added together.
 If the participant is able to find the correct such maximum summation, he/she will win the game and will be awarded the food voucher of the same value.
 
 NOTE: The subsequences A and B should be disjoint.
 
 Example:
 Number of boxes, N=8
 The order of the boxes is provided below:
  1 9 2 3 0 6
  
  Subsequence A  
  9 2 3
  
  Subsequence B 
  6 7 8
  
  P1 = 9*8 = 72
  P2 = 2*7 = 14
  P3 = 3* 6 = 18
  
  Summation, S = P1 + P2 + P3 = 72 + 14 + 18 = 104
  
  This is the maximum summation possible as per the requirement for the given N boxes.
  
  Buddy is also in the fest and wants to play this game. She needs help in winning the game and is asking for you help. Can you help her in winnning the food vouchgers?
  
  Input Format
  
  The first line of input consists of the n umber of boxes, N.
  The second line of input consists of N space-seperated integers.
  
  
  Output Format 
  
  Print the maximum summation of the product of the boxes in a seperate  line.
  
  Input
  
  8
  1 9 2 3 06 7 8
  
  Constraints
  1 <N <=3000
 -108 <= I <=108
 
 Output
  104
