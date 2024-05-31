# TTFishProfile

A simple academic profile templete for researchers powered by Hugo.

Here is the [demo site](https://ttfish-profile.netlify.app/)

## Requirements

The code works properly on **hugo v0.126.1+extended**

```bash
pacman -S hugo #(e.g. for Arch Linux)
```

Visit [offical documentation of hugo](https://gohugo.io/getting-started/quick-start/) for installation

## Documentation

```bash 
# Init a hugo project
hugo new site blabla --format=yaml

# Clone TTFishProfile into the themes dir
git clone https://github.com/fish98/TTFishProfile.git themes/TTFishProfile

# Remember to replace the default hugo.yaml
rm hugo.yaml

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