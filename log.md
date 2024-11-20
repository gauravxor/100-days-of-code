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

<details>
  <summary><h3>Day 2: November 17, 2024</summary>

**Today's Progress**:

- Solved : Leetcode problem [Sort-Colors](https://leetcode.com/problems/sort-colors/)
- Learnt about the concepts OOPs in Java.
- Started a personal project "[project_l](https://github.com/gauravxor/project_l)" which is intented to let two people watch a video together, remotely.

**Thoughts:**

- Fu\*k around till it works.
- Did not deep dived much into java today.
- Solving "real" problems is an absolute joy. Faced an issue recently when I had to watch a video together with someone living at a remote place.
  Dicovered a lack of peoper free services, so trying to build something that atleast I can use. Have very limited knowledge about web-sockets and how they
  work, but look a dive, lets see how deep I can go.

**Link to work:**

- [Solution](https://leetcode.com/submissions/detail/1454975211/) to LC problem
- [Github Repo](https://github.com/gauravxor/project_l) for "project_l".
</details>

<details>
  <summary><h3>Day 3: November 18, 2024</summary>

**Today's Progress**:

- Solved : Leetcode problem [Maximum SubArray ](https://leetcode.com/problems/maximum-subarray/description/)
- Learnt about software desgin principles [Blog](https://medium.com/cognitivecraftsman/design-patterns-every-software-engineer-should-know-c4f83c32a7d8)
- Bought a domain for my personal website [clumsycoder.com](https://clumsycoder.com/).

**Thoughts:**

- Feels good when we do something for ourself. Had a dream to buy a domain of and on my own. Fulfilled that today.

**Link to work:**

- [Solution](https://leetcode.com/submissions/detail/1456492632/) to LC problem

</details>

<details>
  <summary><h3>Day 4: November 19, 2024</summary>

**Today's Progress**:

- Made the HTML video player of 'project_l' working. Now it syncs the video state data like
  play, pause and seek with other users connected with same websocket.

**Thoughts:**

- Too much workload in office. Exhausted AF. But need to move on.
- HTML video player is simple yet damn powerful stuff. Starting to love JS a bit :)

**Link to work:**

- [Project_l](https://github.com/gauravxor/project_l/commit/e643f068b9f2aceff498f0ba791f6a4d3bd95dae), with working video
  player.

</details>
