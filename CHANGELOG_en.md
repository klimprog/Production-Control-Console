# Production Control Console

*[Description](README_en.md)*

![Production Control Console](About/GitHub_Preview.jpg)

**Your colony's production management in one window.**

`Version 0.2.6` · `RimWorld 1.6 and 1.7` · requires [RimUI Framework](https://steamcommunity.com/sharedfiles/filedetails/?id=3763759074)

# Changelog

## 0.2

- **RimWorld 1.7.** One mod for 1.6 and 1.7: each version of the game loads its own build. Requires RimUI Framework 0.4.0 or newer.
- **Recipe variants.** Larger-output recipes, such as simple meal ×4, appear as their own row in the wizard, and the order card lets you pick the variant from a list. Amounts are counted in whole runs: an order for 50 with the ×4 recipe becomes 52, and the field shows it right away.
- **Drop on floor.** The crafter drops the result next to the workbench and starts the next item right away, while other colonists haul it to storage.
- **Order batches.** Tick several products in the wizard: shared settings are entered once, each product keeps its own mode and amount, and you get a separate order for each.
- **Use as template.** Create a new order with the settings of an existing one — just pick the product.
- **Deleting an order now asks for confirmation.**
- **Fixed.** Recipe selection depended on the game language, and in English the ×4 variant was never used. Stock did not count products being carried by colonists and could start an extra run while the result was on its way to storage. After switching the language in game, the catalog kept working with stale data and stock read as zero. The console window lost its grip while dragging if the cursor left the frame.
- **Help.** New topics on recipe variants, order batches, and order card buttons. The workbench description is corrected: one workbench can serve several orders.

## 0.1

- **Production.** Orders are built with a step-by-step wizard: product, amount, ingredient sources, allowed materials, workbenches, workers, and the destination stockpile. Three modes — make a fixed amount, keep a target stock, run forever; operations without a product are measured in recipe runs.
- **Several workbenches per order.** They work towards one total and share a single stock count, so they never each make a full batch. One workbench can serve several orders, queued by priority.
- **Growing.** Fields, growing zones, and hydroponics from a single tab: repeat one crop, queue crops through the full field cycle, stop sowing, treat blight, copy a saved plan to other fields.
- **Animals.** Taming, hunting, and slaughter by species. Herd limits by sex and life stage in one table, area or pen and medicine level for newly tamed animals, slaughter priority, and per-animal designations in the tamed and wild tables.
- **Overview.** Production state, workbench load, orders that need attention with the reason spelled out, upcoming completions, and output over the last seven in-game days.
- **Workbenches, workers, and stockpiles** each get their own tab, with navigation to related objects and a "use" switch per object.
- **Stock summary.** What is in storage, how much the orders need, and the balance.
- **Clear reasons for a stopped order.** Missing materials, no workbench, no available worker, not researched, storage gone or disabled — the reason is written where the stop is shown.
- **In-game help.** Forty topics in plain language: what each block does, when it helps, and what the mod deliberately does not do. "Show in console" opens the matching tab and highlights the block being described.
- **Settings.** Separate check intervals for orders, growing, and animals; starting values for a new order and section defaults, so the same numbers are not retyped every time.
- **Compatibility.** The catalog is built from the game's own data, so recipes and workbenches from other mods are picked up automatically. Harmony is not used. The mod can be added to an existing save.
