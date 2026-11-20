### Week 8 — Neural networks and "AI"

The Flinders Petrie notebook did not work because Project Gutenberg was down, so the model had only 7 tokens to learn from. The model depends on texts that someone else hosts, and when that site went down there was nothing to train on. Dr. Graham described an archaeology of generative AI as "layers of dead data, pattern detection throughout." Here the top layer, Petrie's books, never arrived.

In Teachable Machine I trained a model on 5 red-figure and 5 black-figure vases from the Met. It called both red-figure test vases black-figure, including the bilingual Andokides amphora at 95%. The categories were mine, but the model decided for itself what separated them, and nothing in its output shows what that was.

ArchaeoCLIP made the same mistake with the Andokides amphora. When I searched for "warrior with a spear," the top result was a woman with two bulls, and the one vase with a warrior ranked ninth. This answers Dr. Graham's question about the query layer: the closest match is not necessarily an answer. Magnani and Clindaniel make a similar point about AI pictures of Neanderthals, which repeat old scholarship because that is what was available to learn from (2026).

These tools also rest on other people's work that does not show up in the result: the volunteers who transcribed Petrie's books, the archaeologists who photographed and captioned the images ArchaeoCLIP was trained on, and the Egyptian workers on Petrie's excavations. Most of the friction this week was practical, such as Safari not loading Teachable Machine and the notebook expecting .jpg files. Huggett calls slow research "friction-full, because more inclusive" (2022), and editing llm_clip.py by hand at least made me see which model was being used.

This connects to my PDAP. The Spotify technical log shows that Spotify runs its own models on my listening, such as the generated "daylist" and advertising inferences, so the data I am studying was partly made for those systems.
