# Firefox-UserChrome
UserChrome for firefox [Vertical Tabs](https://addons.mozilla.org/en-US/firefox/addon/vertical-tabs/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)

Also use this [Dark Theme](https://addons.mozilla.org/en-US/firefox/addon/red-moonlight-dark-red/) and the [Dark Reader Extension](https://addons.mozilla.org/en-US/firefox/addon/darkreader/)

In the extention settings for Vertical Tabs set the custom stylesheet to the following:
```
#newtab-icon {
  background-image: url("img/new.svg");
  background-repeat: no-repeat;
  padding-left: 24px;
}

#filterbox-input {
  color: var(--input-text);
  background-color: var(--input-background);
  display: flex;
  flex: 1;
  font: inherit; /* needed for windows */
  margin-left: 14px;
  margin-right: 4px;
  padding: 2px;
  padding-left: 6px;
  border: 1px solid var(--input-border);
  border-radius: var(--button-border-radius);
  box-shadow: 0 1px 4px rgba(0, 0, 0, 0.05);
  transition: border-color 0.1s, box-shadow 0.1s;
  cursor: text;
  border-radius: 4px;
}
#filterbox-icon,
#settings-icon {
  display: none;
}
```
