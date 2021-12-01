# Cultures Website

This website is for my Cultures Across Cultures project. I will be updating with posts throughout my project. The site is built using Jekyll and hosted on GitHub Pages. The theme used is <a href="https://github.com/samesies/barber-jekyll" target="_blank">Barber from Samesies</a>. My workflow was:

1. Get a working Ruby environment with <a href="https://github.com/monfresh/laptop" target="_blank">Monfresh's laptop package</a>.
2. Edit as desired, with directions from the <a href="https://github.com/samesies/barber-jekyll#update-settings" target="_blank">Barber repo</a>. Create a Formcarry, tweak footer to remove subscribe bar. Test locally with 	`bundle exec jekyll serve`.
3. To deploy, I used <a href="https://www.moncefbelyamani.com/making-github-pages-work-with-latest-jekyll/" target="_blank">Monfresh's Jekyll GH pages tutorial</a>. This will allow custom plugins used in the tag list to run. Ensure your origin is `main`, if not, tweak the script to follow `master` instead. I decided against Netlify due to the limited build time on the free plan. Once the initial build is complete, don't forget to switch the default branch back to `master/main`.
4. To update the site, push changes to `master` (not the `gh-pages` branch). This will trigger the update github workflow, which can be seen in the <a href="https://github.com/lianamerk/cultures/actions" target="_blank">Actions tab</a>.



