# PairAir-Bench project website

A responsive, static project website populated from `PairAir__Camera_Ready.pdf`.

## Files
- `index.html` — project page content
- `style.css` — responsive styling
- `assets/figure1-overview.png` — crop of Figure 1 from the paper
- `assets/figure2-scenes.png` — crop of Figure 2 from the paper
- `assets/figure5-method.png` — crop of Figure 5 from the paper
- `assets/figure3-distributions.png` — crop from the dataset statistics page (available if needed)
- `assets/PairAir_Camera_Ready.pdf` — paper PDF linked from the website

## Publish to the existing GitHub repository
1. Download and extract the ZIP.
2. Open `https://github.com/keshri07/PairAir-Bench`.
3. Choose **Add file → Upload files**.
4. Upload/replace `index.html`, `style.css`, and the complete `assets` folder from this package. Keep `README.md` if you want the updated documentation.
5. Commit the changes to `main`.
6. GitHub Pages should redeploy automatically if Pages is already enabled for `main` and `/(root)`.

Expected site: https://keshri07.github.io/PairAir-Bench/

## Before public launch
- The paper PDF is included and linked publicly by this page. Remove it from `assets/` and remove the paper links if it is not cleared for public release.
- Code and dataset URLs remain marked as coming soon; add real URLs only after release.
- The BibTeX proceedings field is provisional because the final official proceedings citation was not present in the uploaded PDF.
- Check the paper's internal methodological consistency before finalizing numerical details on the website. In particular, the manuscript has differing descriptions of color-probe counts and feature-vector dimensions in the text and Figure 5. This website avoids publishing those disputed dimensions.
