class Solution:
    def twoSum(self, nums, target):
        # Create a dictionary to store the complement and its index
        complement_map = {}
        
        # Iterate through the list
        for i, num in enumerate(nums):
            # Check if the current number's complement (target - num) is in the map
            complement = target - num
            if complement in complement_map:
                return [complement_map[complement], i]
            
            # Otherwise, add the number and its index to the map
            complement_map[num] = i

# Example usage:
solution = Solution()
nums = [2, 7, 11, 15]
target = 9
result = solution.twoSum(nums, target)
print(result)  # Output: [0, 1]
