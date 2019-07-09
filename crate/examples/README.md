## Examples
Examples for creating GDL graphics natively.

Note: If you're here to see WebAssembly in action, this is the wrong path, turn back. 
To see WebAssembly in action, clone this repo and run `npm start` after `cd`ing into photon. 
More details can be found in the main repo README.

### Running These Examples
Clone this repo:
```sh
git clone https://github.com/silvia-odwyer/gdl
```

Several examples are included, for this demo, we'll run the Rust file called `text.rs`:

```sh
cd crate
cargo run --example text --release 
```

Make sure the `--release` flag is added.

You'll find the outputted images in `example_output`.

To change the images being inputted, add your image to `input_images` and change the filename in `example.rs`.

#### Add Text Example
To run the example which adds text to an image:

```sh
cargo run --example add_text 
```

#### Examples
`text` - Draw text of various fonts onto an image.
`text_effects` - Showcases some of the various text effects available.
`gradients` - Draws preset gradients onto a background.