# TTFishProfile

A simple academic profile templete for researchers powered by Hugo.

## Requirements

+ hugo v0.111.3+extended

```bash
pacman -S hugo #(e.g.)
```

Visit [offical documentation of hugo](https://gohugo.io/getting-started/quick-start/) for installation

## Documentation

```bash 
# Init a hugo project
hugo new site blabla -f=yaml

# Clone TTFishProfile into the themes dir
git clone https://github.com/fish98/TTFishProfile.git themes/TTFishProfile

# Use the template config.yaml
cp -r themes/TTFishProfile/exampleSite/* .

# Preview the template site locally
hugo server # hugo server --disableFastRender -D
```

## Contributing

As I am not quite familiar with Hugo, please feel free to open an issue if you have any problems in using this template or directly submit a PR if you fix some bugs of this project.

## Special Thanks

This project refers some useful components from [gurusabarish's](https://github.com/gurusabarish) projects [hugo-profile](https://github.com/gurusabarish/hugo-profile) and [hugoProfileV2](https://github.com/gurusabarish/HugoProfileV2).

## License

This project uses [MIT License](./LICENSE)