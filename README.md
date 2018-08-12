NodaBlock documentation
--------------------
## MacOs prerequisite: 

The documentation runs on Ruby
```
gem update --system
xcode-select --install
sudo gem install nokogiri
sudo gem install bundler
```

## Setup things for the repo:
```
# clone this repo then inside this repo:
git clone https://github.com/nodablock/doc.git
cd doc

# setup all things:
bundle install
``` 

## Run:
```
bundle exec middleman server
```

Then the doc will be available at [http://localhost:4567](http://localhost:4567)

## Deploy:
```
./deploy.sh
```

Special Thanks
--------------------

This documentation is based on the [Slate](https://github.com/lord/slate) open source project, built by [Robert Lord](https://lord.io)
