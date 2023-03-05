# 2i Assessment
Function that removes duplicates and sorts the list in descending order. Completes in O(nlogn) time.

```python
def removeDuplicatesAndSortDesc(arr):
	"""
	:type arr: List[int]
	:rtype List[int]

	Time complexity: O(nlogn)
	Space complexity: O(n)
	"""
	# - Assuming we are allowed to use standard library functionality

	s = list(set(arr)) #convert input to set to remove duplicates in O(n) time
	s.sort(reverse=True) #sort array reversely in O(nlogn) time
	return s
```