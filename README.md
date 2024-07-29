## Getting Started

When you first open the plugin, you are presented with a set of pre-defined parameters that can be used as-is to show you what is possible. 

## Options

| Parameter | Description | Value |
|----------|-------------|------|
| `Direction` | The direction in which the component groups will be laid out. | _Horizontal_, Vertical |
| `Levels` | The hierarchy levels in which your components will be organized. | 1 to 100 |
| `Margin` | Distance between each group. | Number in pixels |
| `Gutter` | Distance between each component. | Number in pixels |
| `Display Title` | The parent category name that will be displayed before each group. | _checked_, unchecked |
| `Rename Duplicates` | If multiple components have the exact same name, they will be renamed with incremental numbers. | checked, _unchecked_ |
| `Zoom to Center` | After cleaning up your 💩, view will zoom out to show all components. | _checked_, unchecked |
| `Sort Alphabetically` | Tidy will sort your components and variants alphabetically. | checked, _unchecked_ |
 
## Contribute
- Run `yarn` to install dependencies.
- Run `yarn build:watch` to start webpack in watch mode.
- Open `Figma` > `Plugins` > `Development` > `New Plugin...` and choose manifest.json file from this repo.
- Create a Pull Request for your branch
