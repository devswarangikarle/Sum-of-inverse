# Sum-of-inverse
You're given an array A[] of n integers A1, A2,. ., AN. You're asked to calculate the value of following equation -   f = 1⁄(1⁄A1 + 1⁄A2 +.. + 1⁄AN) Input The first line of the input contains a single integer N The next line contains N integers, A1, A2,. ., AN.  Constraints: 1) 1 ≤ N ≤ 100 2) 1 ≤ Ai ≤ 100 Output Output the answer 

N = int(input())
array = list(map(int, input().split()))
sum_of_reciprocals = sum(1/x for x in array)
result = 1 / sum_of_reciprocals
print("{:.8f}".format(result))
