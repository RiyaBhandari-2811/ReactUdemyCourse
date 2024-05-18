
1. Ref Vs useState:
   1. useState:
      1. Causes component re-evaluation when changed
      2. Should be used for values that are directly reflected in the UI
      3. Should not be used for "behind the scenes" values that have no direct UI impact.
   2. Refs:
      1. Do not cause component re-evaluation when changed
      2. Can be used to gain direct DOM element access
