# Rouge like terminal game

In terminal dungeon crawler.



I started this project in an effort to learn Rust and hopefully learn more about game design. It based on the book Hands on Rust https://pragprog.com/titles/hwrust/hands-on-rust/

My end goal is to release it as a free to use browser game using wasm, to add multiple levels, characters, monsters, maps, levels, objects and add an over arching story and theme to the project. I want to make it multiplayer and give it a progression system. This will be a long term project and my go to project to improve my knowledge of Rust.

To use it currently, install the rust langauge on your computer, download the code and run 

## cargo build

then 

## cargo run


you can see it live [here](https://sleepy-island-60648.herokuapp.com/)

## to run the web app version
npm install
npm start

## to build the wasm 

cargo build --target wasm32-unknown-unknown --release

to generate the js links for the wasm 

wasm-bindgen target/wasm32-unknown-unknown/release/rogue-like.wasm --out-dir ./wasm_help --no-modules --no-typescript



Shane Hamilton 2022