2024/9/6 Feng Tang @ Nanjing University

Unzip EBSToSubGrps1.1.zip, and you'll see four files:
Data/, example.nb, example.mp4, and ExternalFieldsSubgroups.wl.

Directly open example.nb,  (please guarantee that Mathematica should be already installed),

and then run the two following commands subseqently (shift+enter):

SetDirectory[NotebookDirectory[]]

Get["ExternalFieldsSubgroups.wl"]

, then you will see an interface as shown in example.mp4, and then you can:
Choose how to break the symmetry in 'Step 1': 'E' stands for electric fields, 'B' stands for magnetic fields and 'sigma' stands for strain fieds; 'E+B' means applying electric and magnetic fields simultaneously, and so on.
Then choose the parent magnetic space group of the unperturbed crystalline materials in Steps 2 and 3.
Finally, a tree-like graph then appears. See example.mp4, you can get different tree-like graphs by dynamically choosing different options in Steps 1, 2 and 3. 
