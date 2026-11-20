**November 20**

Flinders Petrie language model
- Opened the Flinders Petrie notebook in Colab, saved a copy to my Drive, and checked that the runtime was T4 GPU.
- The first run of the training cell failed with "Variable model/wpe already exists," because it had been run twice in the same session. I restarted the session and ran all the cells once.
- The training then failed with "Dataset files are too small to sample 1024 tokens at a time." The dataset had only 7 tokens: the notebook downloads Petrie's books from Project Gutenberg, but Gutenberg has been down for several days, so the files were empty. On November 20 isitdownrightnow.com listed gutenberg.org as down: https://www.isitdownrightnow.com/gutenberg.org.html
- The download cell starts with %%capture, which hides its output, so the failure only showed up at the training step.
- Could not generate text from the prompt "Local workers are."

Teachable Machine
- Teachable Machine did not load in Safari, so I used Chrome.
- Made an image project with two classes, red-figure and black-figure, using public-domain photographs of Attic amphorae and neck-amphorae from the Met's collection. Left out fragments and drawings.
- Uploaded 5 images per class and trained the model.
- Tested it on three vases that were not in the training set:
  - a red-figure neck-amphora: black-figure 77%, red-figure 23% (wrong)
  - a black-figure amphora: black-figure 100% (right)
  - the bilingual amphora signed by Andokides, red-figure side: black-figure 95% (wrong)
- Screenshot: teachable-machine.png

ArchaeoCLIP
- Used the same Met photographs: 5 red-figure and 5 black-figure vases in two folders, plus the two test vases and the Andokides amphora. Zipped them and uploaded the zip to the Colab file tray.
- Visually similar search on the red-figure side of the Andokides amphora: the closest image was the black-figure test vase (0.84), then a black-figure vase (0.83), then a red-figure vase (0.83). Five of the eight closest vases from the two folders were black-figure. All the scores were between 0.74 and 0.84.
- Search by idea, "warrior with a spear": the top three were all black-figure vases, but none showed a warrior with a spear (the first was a woman with two bulls, the second satyrs and a woman, the third a horseman). The only vase with a warrior holding a spear and shield ranked 9th. All the scores were very low and close together (0.26 to 0.30).
- Screenshots: archaeoclip-results-1.png, archaeoclip-results-2.png

PDAP
- Received final Spotify data export: "Technical Log Information" (cf. PDAP-update, November 20).
- Downloaded my YouTube watch history from Google Takeout to complement Spotify data.
