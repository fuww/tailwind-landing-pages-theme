# Tailwind CSS landing pages theme
## Install
  
```bash
asdf install
npm install
# all used postcss plugins should be installed globally
npm install -g postcss-cli autoprefixer tailwindcss
# Install go
yay -S go
```

ASDF Go does not work with Hugo (2022-8)

Extra useful commands:

```bash
asdf plugin add nodejs https://github.com/asdf-vm/asdf-nodejs.git
asdf plugin-remove golang
# restart terminal
```

## Tailwind & Hugo notes

https://github.com/gohugoio/hugo/issues/8343#issuecomment-1013956389

Hugo Pipe’s PostCSS requires the postcss-cli JavaScript package to be installed in the environment (npm install -g postcss postcss-cli) along with any PostCSS plugin(s) used (e.g., npm install -g autoprefixer).

## Run example site

cd exampleSite
hugo server -D
