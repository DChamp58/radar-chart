# Company Radar

A single-file web app for building radar charts that compare companies on five
criteria, each scored 0–5:

- **Innovative**
- **High Standard Volume**
- **Low Beckhoff Support** (5 = little/no existing Beckhoff support — greenfield opportunity)
- **Business Type** (1 = one-off machine builder, 5 = pure OEM)
- **Company Size**

## Use it

Open `index.html` in any browser — no build step, no server, no dependencies.

- **+ Add** creates a company; type each 0–5 score and the chart updates live.
- Overlay as many as 8 companies; click a legend entry (or **Hide**) to toggle
  one on/off, hover a vertex for the exact value.
- Each company shows the **area its shape covers** as a percentage of the full
  pentagon, in the legend and the score table.
- Everything is saved in your browser (localStorage). **Export / Import**
  moves your data between machines as a JSON file.
- A score table below the chart shows all values at a glance.
