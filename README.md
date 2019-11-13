# NativeScript Simple File Share Plugin

## Installation

```
tns plugin add nativescript-simple-fileshare
```

## Usage 

``` TypeScript
    const shareFile = new ShareFile();
    shareFile.open({
        path: pathToFile,
        options: true,
        animated: true
    });
```

## License

MIT
