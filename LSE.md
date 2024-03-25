# LSE

## Here are the main triggers in LSE:
- "Flip": `M' U M`:
  - Flips the "arrow case" of edges, where there are 3 good on top in front, and 1 on bottom front.
  - `M U M'` Same thing, but mirrored for the back side
- "Swap": `M' U2 M`
  - Swaps the top front edge with the bottom.
  - `M U2 M'`: mirrored for back side

## Here's the notation used to describe edges:
- UF, UB, UL, UR, DF, DB
  - **U**p/**D**own 
  <!-- - that line above looks awful without the preview LOL -->
  - **F**ront/**B**ack
  - **L**eft/**R**ight
- The "bottom two" are DF and DB
- The "left and right on top" are UL and UR (aka ULUR in step 2, later on)


## Move notation:
- https://ruwix.com/the-rubiks-cube/notation/advanced/ is a nice reference!
- R,L,U,D,F,B as usual for side turns
- For slice turns:
  - M move: Follows the L side, turns the middle slice. M' goes "*up*"
  - E move: follows D -> E is a "swipe from left to right"
  - S is rarely used lol

## The actual steps!
1. EO (Edge orientation)
   - The Flip trigger is used here.
   - [Kian Mansour's EO Guide](https://docs.google.com/document/d/1dFXRcw29cS6h59j0qoZniA-qo232vQ7Sg9dCVX1zppE/edit) helps here. However, it all boils down to:
     - Align the U layer by doing a U, U', or U2 move
     - Do the Flip trigger
     - Repeat those steps until EO is solved
2. ULUR (Upper Left and Upper Right edges)
   1. Use the Swap trigger to put UL in the bottom
   2. Same, but for UR and using the other remaining bottom spot
   3. Look at the front face of DF.
      1. What color is it?
      2. Find its opposite color (red - orange; green - blue)
   4. Align the U layer such that the opposite color is facing you on the U layer...
      1. Example:
        ```
        R _ R
        _ _ _
        _ O _
        ```
   5. Then do an M2!
   6. After a U/U'/U2 move, you should have both the left and right LAYERS fully finished.
3. Finish him!
   1. Apparently, this step can be called L4E (Last Four Edges) - which makes sense! The only remaining pieces should be in the M slice. 
   2. This section doesn't actually use U and U' moves - just U2 (and M, M', M2)
   3. A simple approach can be to use the Swap trigger (TODO: i really wanna make these *link* to the top of this page, where i describe said triggers...).
      1. Use an M2 move as necessary to align the centers such that the white center is on bottom (assuming you started with white bottom).
      2. Identify what your DF edge *should* be - for example, if you have white on bottom and green on front, DF should be white-green (oh my god what a shocker!!) - and find it!
      3. Put DF in its correct spot, utilizing the Swap trigger as necessary.
      4. Put DB in its correct spot in the same way!
   

**The cube should be solved.**
