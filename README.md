# rEFInd KorvNN Theme

A personalized 1920x1080 rEFInd theme.

## Preview

![KorvNN background](background.korvnn.png)


## Installation

Copy the repository into the `themes` directory next to `refind_x64.efi` and
name the copied directory `rEFInd-KorvNN`:

```text
EFI/refind/
├── refind.conf
└── themes/
    └── rEFInd-KorvNN/
        ├── background.korvnn.png
        ├── icons/
        ├── selection_big.png
        ├── selection_small.png
        └── theme.conf
```

Then add this line to the end of `refind.conf`:

```text
include themes/rEFInd-KorvNN/theme.conf
```

The configured resolution is 1920x1080. Change the `resolution` line in
`theme.conf` if your firmware display uses another mode.

## Customization

- Background: `background.korvnn.png`
- Theme settings: `theme.conf`
