# 100 Days Of Code - Log

<details>
  <summary><h3>Day 1: November 16, 2024</summary>

**Today's Progress**:

- Solved : Leetcode problem [Two-Sum](https://leetcode.com/problems/two-sum/submissions/1453932224/)
- Learnt about HashMap in Java Collection. How deep & shallow copy works internally wrt Objects and reference. Java's type erasure at runtime.

**Thoughts:**

- Java's type erasure at runtime is pretty interesting. I see the thought process & design principle behind it, i.e. keep things generic at the lowest level.
- Even if everything in Java boils down to type "Object", but on casting any Object to another type, it warns about it, which is impressive. When I tried to create a shallow copy of a HashMap like this `HashMap<String, String> hmap1 = (HashMap<String, String>)(hmap2.clone())`, it started giving me warnings, which upon deep diving, I dicovered the `type erasure at runtime` feature where .clone() returns the data of HashMap in `Object` type which contains references to the values of original HashMap but now the `Object` have lost the type details, hence the warnings, because compiler cannot confirm the type safety, which I think is pretty amazing!

**Link to work:**

- [Solution](https://leetcode.com/problems/two-sum/submissions/1453932224/) to LC problem
</details>
