# Nomad Emoji

Are you a fan of Nomad? Want to truly express those feelings? Or maybe you want to take a more subliminal approach to convincing your friends and colleagues that Nomad is as great as you've been saying? Consider adding these **32 custom Nomad emoji** to your Slack, Discord, or whatever instance!

## Files

Files are split across four directories:

1. **Originals:** These are source files, including files for [Adobe Illustrator](https://www.adobe.com/products/illustrator.html) and [Cinema 4D](https://www.maxon.net/en/cinema-4d/). If you don't have that software, don't worry, you don't need the originals anyway.
2. **SVGs:** These are scalabe vectors of the originals (that were made in Illustrator). You don't need these either, but you can use these to make bigger versions of the PNGs.
3. **PNGs:** These are the files you actually want to upload to Slack. They come pre-named as my recommended emoji name.
4. **GIFs:** These are also the files you want to upload to Slack. They should all already be compressed to the point of uploadability.

## Quickly upload to Slack with the Emojipack

Including in this repo is a `nomad.yaml` file that can be used to batch upload all emoji in this repo to your Slack instance using [emojipacks](https://github.com/lambtron/emojipacks). :warning: Disclaimer. I never actually tested this. Idk, file an issue or make a PR if it doesn't work.

Note that [do to a limitation with emojipacks](), you'll have to serve the files on port `6464` by doing something like this from the root of this repo.

```shellsession
$ python -m http.server 6464
$ npx emojipacks -y nomad.yaml
```

## Backstory

Right, but y tho. I don't remember how it started. Something to do with my compulsion to anthropomorphize things combined with the Nomad logo's alluring hexagonal foundation. Anyway, I put a face on it. Then it became a thing. Then we'd celebrate each major release by taking a poll for which emoji would get nomadified. Many releases later, here we are.

## Attribution

The bulk of the art here is original content, but there are a few places where I borrowed for memetic or canonical reasons.

- **Girl on scooter Premium Vector**: From [freepik](https://www.freepik.com/premium-vector/girl-scooter_1366690.htm)
- **Nomad logo on girl on scooter Premium Vector**: From [Matthias Endler](https://endler.dev/2019/maybe-you-dont-need-kubernetes/) (we liked this post so much the lady on the scooter became an unofficial mascot)
- **Abe "Grandpa" Simpson**: From [The Simpsons](https://en.wikipedia.org/wiki/The_Simpsons)
- **Nomad Logo**: From [HashiCorp](https://www.hashicorp.com/brand)

## Creative Commons

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

