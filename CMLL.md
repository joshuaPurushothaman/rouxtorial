# CMLL
Corners of the Last Layer (ignoring the M slice). Yes, the name is confusing.

You can solve this with as little as 1 alg and as many as 42 (or more!).

> Side note: Some CMLLs can be referred to by their name, such as "sune". You don't need to remember the name at all. :) In fact, you don't even need to know the algs' moves... just the muscle memory! If you can remember it by the "shapes" it moves on the cube, that works too :)

A "look" means you look at the cube and execute 1 alg, after which some step is done. With "full CMLL", you'd know 42 algs and be able to 1-look CMLL.

2-look CMLL uses only 9 algs, and is worth knowing until you can get through the rest. CMLL is a fairly small and easy algset though, so you can learn it whenever! I know only partial CMLL because I'm lazy :)


# 2-look CMLL
For 2-look CMLL, the steps are:
- Orient the top layer corners (assumed to be yellow usually) in one look
  - 7 algs
- Permute the top layer corners in one look
  - 2 algs

Here's an [algsheet for 2-look CMLL](https://docs.google.com/document/u/0/d/1SUdgNugJtM4l644jfR90J0nxvSdpq0nNMO-k492S2ik/mobilebasic#). I'll describe these algs here, but that's a great reference!

If you learned the layer-by-layer "beginner's method" first, then you already might know:
- Niklas
  - `R U' L' U R' U' L`
  - Used in beginner's method to permute corners.
  - Not necessarily used in 2-look CMLL, but hey, now you know a full CMLL case!
    - It actually does a Sune's orientation + an adjacent corner perm (like a T perm).
- Niklas mirror (just do that but with ur left hand starting first!)
- Sune:
  - `R U R' U R U2 R'`
  - Used in beginner's method to move yellow edges!
- Antisune:
  - either do sune with left hand, OR do sune in reverse:
  - `R U2 R' U' R U' R'`
  - or *from the back*:
    - `R' U' R U' R' U2 R` (this is the one on the page)
- F sexy F':
  - `F (R U R' U') F`
  - used in beginner's to FLIP yellow edges
  - *Note: "sexy move" refers to `R U R' U'`, a common trigger in algs*

Sune, Antisune, and F sexy F' are used in 2-look CMLL to orient corners.
The remainders for orientation are:
- H: `F (triple sexy) F'`
  - As in, you do 3 sexy moves!
- Pi: `F (double sexy) F'`
- T: `(sexy) (sledgehammer)`
  - A "sledgehammer" is `R' F R F'`.
- L: `F R U' R' U' R U R' F'`
  - Note: don't confuse *these* R and U moves with a sexy move!

For permutation, you'll need the T and Y perms:
- T perm:
  - Used for adjacent corner swaps on the right side.
  - `R U R' U' R' F R2 U' R' U' R U R' F'`
    - Aka, `(sexy) (L orientation)`, but the `R R` that would be in the middle of that  gets written as R2.
    - T perm is best perm :)
- Y perm:
  - Used for diagonal corner swaps.
  - `F R U' R' U' R U R' F' R U R' U' R' F R F'`
  - Notice: `(L orientation) (T orientation)` lol