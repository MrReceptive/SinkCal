# SinkCal — Satisfactory AWESOME Sink Coupon Optimizer

[![View App](https://img.shields.io/badge/View%20Web%20App-mrreceptive.github.io%2FSinkCal-blue?logo=github)](https://mrreceptive.github.io/SinkCal/)

**SinkCal** is an open-source, up-to-date web app that helps Satisfactory players optimize how to earn coupons (tickets) from the AWESOME Sink. It automatically calculates how many points you need for any number of coupons and shows you the fastest, most efficient items to sink based on your real unlocks, progress, and inventory.

## Features

- 🏆 **Accurate Coupon Math** — Uses the official formula from Satisfactory 1.1+ for calculating single and bulk coupon costs.
- 🗂 **Tier, Milestone, and Research Filtering** — Only shows items you actually have unlocked (select by Tier, paste your items, or use milestone presets).
- 🖱️ **Quick & Simple Interface** — Instantly see what to sink for your next ticket(s).
- 📝 **Inventory & Custom Unlocks** — Enter your inventory and unlocks for fully personalized recommendations.
- 🚫 **Up-to-date Item Values** — Includes all major items, FICSMAS/event items, and excludes all unsinkable items.

## How to Use

1. **Open the web app:**  
   👉 [https://mrreceptive.github.io/SinkCal/](https://mrreceptive.github.io/SinkCal/)
2. **Select your Tier** (or paste a list of unlocked items/recipes for full accuracy).
3. **Enter how many coupons you want** and your current point balance.
4. *(Optional)* Enter your inventory to only recommend items you can actually sink.
5. Click **Find Best Items** to get an instant, optimized list!

## How Coupon Math Works

The app uses the official Satisfactory formula for coupon cost:
- The first three coupons cost 500 points each.
- For coupons 4–3,000:  
  `cost(n) = 250 * (ceil(n/3)-1)^2 + 1000`
- After coupon #3,000:  
  `cost(n) = 249,501,250`
- **Bulk/cumulative cost** is calculated correctly for *any* starting point and coupon count.

## Development & Contributing

- This project is **pure HTML/JavaScript/CSS** — all logic runs client-side.
- To edit, just update `index.html` and commit your changes.
- Want to help? Suggestions, bug reports, or PRs are welcome!

### To run locally
Just clone the repo and open `index.html` in any browser.  
No server or build process required.

## To Do / Roadmap

- [ ] Add milestone and MAM research checklists for even more precise unlock tracking.
- [ ] Autocomplete and quick-select for custom unlocked items.
- [ ] Preset buttons for common milestone combinations.

## License

[MIT License](LICENSE)

---

*Made by [MrReceptive](https://github.com/MrReceptive) and OpenAI ChatGPT automation. Satisfactory™ is property of Coffee Stain Studios. This is an unofficial fan project.*
