# /etc/hosts bundle for TextMate 1

This bundle helps you to display `hosts` file more readable :)

## Install

```bash
cd ~/Library/Application Support/TextMate/Bundles/
git clone git@github.com:vigo/textmate-hosts.tmbundle.git
osascript -e 'tell app "TextMate" to reload bundles'
```

## Usage

```bash
mate /etc/hosts
```

## Note

If you add special element to your color theme (*TextMate > Preferences > Fonts & Colors*)
you can see the ip addresses in color (*Scope Selector*):

    punctuation.definition.ip-address.source.hosts-file


## Change Log

**2016-04-25**

* Fixed prefs + languaage.

**2015-01-06**

* IPV6 is available now! (via [WeZZard](https://github.com/WeZZard))