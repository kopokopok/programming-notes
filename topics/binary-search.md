# Binary Search

[Reference Link](https://www.topcoder.com/community/competitive-programming/tutorials/binary-search)

Only works if the ordered data is either constantly increasing or decreasing (non-changing is fine too).
- If the condition is viewed as a boolean return, then if the data looks like this (FFFFFFFTTTTTTT), then binary will work.

<br/>

Pseudocode:
```
binary_search(lo, hi) {
	while lo < hi:
		mid = (lo + hi) / 2

		if f(mid) == true:
			hi = mid
		else:
			lo = mid + 1

	if f(lo) == false:
		// there is no solution

	return lo;
}
```

Time complexity - O(log n)

<details>
	<summary>Examples</summary>

Work in progress.

</details>