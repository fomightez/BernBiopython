## UPDATE: THIS IS NO LONGER NEEDED AS 'parsing of PDB headers for missing residues' HAS BEEN MOVED FROM DEVELOPMENT VERISON OF BIOPYTHON TO CURRENT VERSION. SEE [here](https://github.com/fomightez/cl_demo-binder) for a repo where you can launch sessions with this ability ready and indeed demonstrated  in the notebook entitled `Using Biopython PDB Header Parser to get missing residues.ipynb` that you can select once you launch a session. (Leaving this here as it reminds me how I was able to test and develop and later move.)

# developmentBiopython-binder

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/fomightez/BernBiopython/master?filepath=cl_demo-binder%20Using%20Biopython%20PDB%20Header%20Parser%20to%20get%20missing%20residues.ipynb)

*tl;dr:*  
Click any `launch binder` badge on this page to run Jupyter environment where you can inport a developmental version of Biopython .

------

***Developmental version of Biopython***

## UPDATE: THIS IS NO LONGER NEEDED AS 'parsing of PDB headers for missing residues' HAS BEEN MOVED FROM DEVELOPMENT VERISON OF BIOPYTHON TO CURRENT VERSION. SEE [here](https://github.com/fomightez/cl_demo-binder) for a repo where you can launch sessions with this ability ready and indeed demonstrated  in the notebook entitled `Using Biopython PDB Header Parser to get missing residues.ipynb` that you can select once you launch a session. (Leaving this here as it reminds me how I was able to test and develop and later move.)

Adds parsing of PDB headers for missing residues.

Should soon be in main Biopython because updated October 17th, 2018 to clear what looked to be last of hurdles.

-------




Technical Details
-----------------

This repository is set up to make use of the binder service offered by [MyBinder.org](https://mybinder.org/). See their site for more information about Binder.

I couldn't directly fork [Bernhard10's personal fork of biopython](https://github.com/Bernhard10/biopython) because when I tried in the Github web site, it just took me to my old fork of the main bioython repo, which I cannot delete yet because records will be messed up.

So I cloned [Bernhard10's personal fork of biopython](https://github.com/Bernhard10/biopython) to my work mac and then made this new 'BernBiopython' repo. I cloned it to my work Mac. On my local computer, I moved the files from the cloned Bernhard10's personal fork into my cloned  'BernBiopython' repo, did git add, git commit, and git push to send them to remote 'BernBiopython' repo. Bcause it already had a `setup.py` in the main directory, it seemed to build and allow import on Binder served versions out-of-the box. See https://github.com/binder-examples/setup.py .

Click this button below to begin using it:

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/fomightez/BernBiopython/master?filepath=cl_demo-binder%20Using%20Biopython%20PDB%20Header%20Parser%20to%20get%20missing%20residues.ipynb)

