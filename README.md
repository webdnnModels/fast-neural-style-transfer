# fast-neural-style-transfer in the web

This is compiled WebDNN models from https://github.com/mil-tokyo/webdnn/tree/master/example/neural_style_transfer

## Usage

```js
<script src="https://raw.githubusercontent.com/webdnnModels/fast-neural-style-transfer/master/dist/webdnn.js"></script>
<script>
    const cdnHost = "https://raw.githubusercontent.com/webdnnModels/fast-neural-style-transfer/master/"
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
