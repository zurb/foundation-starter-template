# Quickstart

Start by opening a Terminal and changing your Sites/ folder, like so:

```bash
mkdir -p ~/Sites
cd ~/Sites
```

Clone this repo:

```bash
git clone git@github.com:zurb/foundation-starter-template.git awesomeapp
```

Install dependencies using:

```bash
bundle install
```

Scaffold out your project:

```
bundle exec compass create awesomeapp -r zurb-foundation --using foundation
```

## Working on your project:

Change into the directory of your project (this assumes it's called awesomeapp)

```bash
cd ~/Sites/awesomeapp
```

Then run the compass watch utility like so:

```bash
bundle exec compass watch
```
