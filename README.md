# Vanilla Demo

- [Video demos and documentation](https://partners.boothmotion.com/)
- [React example repo](https://github.com/BoothMotion/react-import-widget-demo)

## Introduction

This widget enables customers to smoothly transfer their BoothMotion products into your app. Crafted for easy integration, it provides multiple integration approaches based on your app's architecture.

Below you can find demos and example code for each of the import strategies in vanilla JS and React.

If you have any questions, please reach out to hello@boothmotion.com

### File Input Strategy

[source](https://github.com/BoothMotion/vanilla-import-widget-demo/blob/main/src/components/FileInputStrategy.jsx) - [demo](https://partners.boothmotion.com/file-input-strategy.htm)

If you already allow your user to upload start screens or animated overlays, the file input strategy is the simplest way to integrate with BoothMotion. It takes a reference to a file input element, and once the user has selected a file, it will download the file and load it into the file input purely on in the browser as if the user has selected the file from their desktop.

Other than adding the import widget code and a small amount of configuration, there is no other work required on your part. The import widget will handle the rest.

### File Return Strategy

[source](https://github.com/BoothMotion/react-import-widget-demo/blob/main/src/components/FileReturnStrategy.jsx) - [demo](https://partners.boothmotion.com/file-return-strategy.htm)

The file return strategy is a more advanced strategy that allows you to have more control over the import process. It returns a native file object.

### Signed URL Strategy

[source](https://github.com/BoothMotion/react-import-widget-demo/blob/main/src/components/SignedUrlStrategy.jsx) - [demo](https://partners.boothmotion.com/signed-url-strategy.htm)

The signed URL strategy returns a URL lasting 7 days that can be used to download the asset.
