# shellinabox-md-style
A little CSS replacement for shellinabox to theme it with Google's Material Design language and make it more pretty

## Some images

![Some images](images/Screenshot.png)

## Use

Just copy `00+Black on White.css` to `/etc/shellinabox/options-enabled/` (replacing what's in there).

If that doesn't work try using the `--css` option when running shellinabox as such (thanks [@liudonghua123](https://github.com/liudonghua123) for [the fix](https://github.com/rianadon/shellinabox-md-style/issues/1)!):
```
shellinaboxd -s /:LOGIN --css "/path/to/00+Black on White.css"
```

You'll also have to restart shellinabox with `/etc/init.d/shellinabox restart`.

## Credits

Thanks to the [Materialize framework](https://github.com/Dogfalo/materialize) for creating some of the styles I adapted.
