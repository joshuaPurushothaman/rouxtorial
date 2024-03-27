# LSE

> Note: Refer to [Notation](./Notation.md) and [Triggers](./Triggers.md) as necessary.
> Edge notation such as "UL" "DF", and Triggers are used here extensively.

1. How to "[Swap](./Triggers.md)" edges
   - We'll be using this idea a lot in multiple parts of LSE.
   - To move an edge from the U layer to the D layer:
     1. Put it "on top" of where it needs to be with a U*
     2. Do the [Swap trigger](./Triggers.md).
   - Alternatively, to swap from the D layer to U, simply use the [Swap trigger](./Triggers.md) in front or back accordingly.
2. EO (Edge orientation)
   - The [Flip trigger](./Triggers.md) is used here.
   - [Kian Mansour's EO Guide](https://docs.google.com/document/d/1dFXRcw29cS6h59j0qoZniA-qo232vQ7Sg9dCVX1zppE/edit) helps here. However, it all boils down to some form of:
     - Align the U layer by doing a U*
     - Do the [Flip trigger](./Triggers.md)
     - Repeat those steps until EO is solved
3. ULUR (Upper Left and Upper Right edges)
   1. Use the [Swap trigger](./Triggers.md) to put UL in the bottom
   2. Same, but for UR and using the other remaining bottom spot
   3. Look at the front face of DF.
      1. What color is it?
      2. Find its opposite color (red - orange; green - blue)
   4. Align the U layer such that the *opposite color is facing you* using U*
      1. Example:
        ```
        R _ R
        _ _ _
        _ O _
        ```
   5. Then do an M2!
   6. After a U*, you should have both the left and right LAYERS fully finished.
4. *Finish him!*
   - Apparently, this step can be called L4E (Last Four Edges) - which makes sense! The only remaining pieces should be in the M slice.
   - This section doesn't actually use U and U' - just U2 (and M*).
   - A simple approach can be to use the [Swap trigger](./Triggers.md):
      1. If necessary, use an M2 to align the centers such that the white center is on bottom (assuming you started with white bottom).
      2. Identify what your DF edge *should* be - for example, if you have white on bottom and green on front, DF should be white-green (oh my god what a shocker!!) - and find it!
      3. Put DF in its correct spot, utilizing the [Swap trigger](./Triggers.md) as necessary.
         1. Put it in the right spot using U2.
            - If one or both of DF and DB are on the bottom already, use the [Swap trigger](./Triggers.md) (using Front or Back versions accordingly) to bring them to somewhere on the top.
         2. Use the [Swap trigger](./Triggers.md) to put it into either the front or back.
      4. Put DB in its correct spot in the same way!
   - However, you can solve this intuitively.
     - For example, M2 U2 M2 U2 is a case that the above method is very inefficient for, given that a 4-move solution exists.
   

**The cube should be solved.**
