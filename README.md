# AI4SoftwareSec

Website for the AI for Software Security workshop: https://secure-reasoning-lab.github.io/AI4SoftwareSec/.

## Edit the website

Workshop content is in `index.html`, styles are in `assets/css/style.css`, navigation behavior is in `assets/js/navigation.js`, and photographs are in `assets/images/`. The site uses plain HTML, CSS, and JavaScript and has no build dependencies.

Preview locally with `python3 -m http.server 8000`, then open http://localhost:8000.

## Publish

GitHub Pages publishes the root of `main`. Push changes to `main` to update the website. The `.nojekyll` file enables direct static publishing.

## Future editions

Keep this repository and its URL for future editions. Before replacing an edition, copy its page to a year folder such as `2027/index.html`, change that archived page’s relative asset paths to `../assets/`, and set its canonical and Open Graph URLs to the archived URL. Preserve any assets used by the archived edition. Add links between the current and previous editions.

## Credits

The workshop layout is adapted from the organizer-provided Efficient Reasoning 2026 website, based on [Start Bootstrap Agency](https://startbootstrap.com/theme/agency). The San Francisco skyline photograph is by [Casey Horner on Unsplash](https://unsplash.com/photos/tymOL8yT8XM), used under the [Unsplash License](https://unsplash.com/license). Portraits are from the homepages of [Jiahao Yu](https://hubertyoo.github.io/) and [Yan Chen](https://users.cs.northwestern.edu/~ychen/).
