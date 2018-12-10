# fast-neural-style-transfer in the web

This is compiled WebDNN models from https://github.com/mil-tokyo/webdnn/tree/master/example/neural_style_transfer

## Usage

#### jsDelivr CDN

```js
<script src="https://cdn.jsdelivr.net/gh/webdnnModels/fast-neural-style-transfer@master/dist/webdnn.js"></script>
<script>
    const cdnHost = "https://cdn.jsdelivr.net/gh/webdnnModels/fast-neural-style-transfer@master/"
    const options = {backendOrder:['webgpu','webassembly','webgl']}
    const dnn
    dnn = await WebDNN.load(`${cdnHost}output.candy`, options)
    // dnn = await WebDNN.load(`${cdnHost}output.fur`, options)
    // dnn = await WebDNN.load(`${cdnHost}output.kanagawa`, options)
    // dnn = await WebDNN.load(`${cdnHost}output.kandinsky`, options)
    // dnn = await WebDNN.load(`${cdnHost}output.scream`, options)
    // dnn = await WebDNN.load(`${cdnHost}output.starrynight`, options)
</script>
```
