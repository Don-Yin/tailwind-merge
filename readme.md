# Quoted-delimiter regression evidence

`quoted-delimiters.png` compares the number of classes retained from seven representative conflicting pairs. Every pair should keep only its last class. The full measured set contains 22 pairs: 4 merge correctly before the fix, and all 22 merge correctly afterward.

`measurements-base.json` and `measurements-fixed.json` contain the exact inputs, outputs, generated CSS, runtime version, and parser source hashes. Each candidate was compiled independently with Tailwind CSS 4.3.3 to confirm that it generates a utility. The baseline is dcastil/tailwind-merge commit `8396cc3d1f18c143a608a08ce8d2ca7487aa7b75`.

The chart reads these measured values directly; it contains no estimated values. It is rendered at 16 cm width and 420 dpi. Orange hatching marks the baseline, and solid blue marks the fixed parser.
