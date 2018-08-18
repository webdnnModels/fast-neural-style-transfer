# fast-neural-style-transfer in the web

Compiled WebDNN models from https://github.com/mil-tokyo/webdnn/tree/master/example/neural_style_transfer

## Usage

#### RawGit CDN

```js
<script src="https://cdn.rawgit.com/webdnnModels/fast-neural-style-transfer/master/dist/webdnn.js"></script>
<script>
    const options = {backendOrder:['webgpu','webassembly','webgl']}
    const dnn
    dnn = await WebDNN.load("https://cdn.rawgit.com/webdnnModels/fast-neural-style-transfer/master/output.candy/", options)
    // dnn = await WebDNN.load("https://cdn.rawgit.com/webdnnModels/fast-neural-style-transfer/master/output.fur/", options)
    // dnn = await WebDNN.load("https://cdn.rawgit.com/webdnnModels/fast-neural-style-transfer/master/output.kanagawa/", options)
    // dnn = await WebDNN.load("https://cdn.rawgit.com/webdnnModels/fast-neural-style-transfer/master/output.kandinsky/", options)
    // dnn = await WebDNN.load("https://cdn.rawgit.com/webdnnModels/fast-neural-style-transfer/master/output.scream/", options)
    // dnn = await WebDNN.load("https://cdn.rawgit.com/webdnnModels/fast-neural-style-transfer/master/output.starrynight/", options)
</script>
```
