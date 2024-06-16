class Solution(object):
    def numIdenticalPairs(self, nums):
        x=0
        n=len(nums)
        for i in range(n):
            for j in range(i+1,n):
                if nums[i]==nums[j]:
                    x+=1
        return x
