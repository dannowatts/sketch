# SVGO Compressor

A Plugin that compresses SVG assets using SVGO, right when you export them. This Plugin *requires* Sketch 3.8.

## Install

- Download [SVGO Compressor](https://github.com/BohemianCoding/svgo-compressor/archive/master.zip) & unzip it.
- Double click **SVGO Compressor.sketchplugin** to install the Plugin.

## Usage

Selecting menu items or hitting keys is out of fashion, so SVGO Compressor will compress your SVG assets whenever you export them, without you having to do anything.

You’ll get a message on your document window showing some stats about the process to let you know the compression worked as expected.

If you want your SVG assets uncompressed, you can temporarily disable the Plugin by opening Sketch’s **Preferences › Plugins** and unchecking 'SVGO Compressor'. Alternatively, you can right-click any layer and select **Copy SVG Code**, and that will give you the original, uncompressed code.

## Editing Settings

If for some reason you’re not happy with the default settings we’ve chosen, you can select **Plugins › SVGO Compressor › About SVGO Compressor** and then click the **Edit SVGO Settings…** button. You default editor will open the `svgo.json` file, where you’ll be able to tweak the settings.

For an explanation of what each SVGO Plugin does, please refer to the [SVGO page on GitHub](https://github.com/svg/svgo#what-it-can-do).

## Acknowledgements

We would like to thank:

- The [SVGO project](https://github.com/svg/svgo), for creating the golden standard for SVG compression.
- [Andrey Shakhmin](https://github.com/turbobabr), for his inspiration during the [Hamburg Hackathon](http://designtoolshackday.com), where he showed us how to use node modules inside Sketch.

## Support & feedback

We’ve done our best to make the Plugin useful & usable, but we know there’s always room for improvement. If you have any question or want to share your feedback, we’d love to hear it. Either file an issue, or get in touch with us at <developers@sketchapp.com>
