this is a replica of len() function used in rust language and a demo to published on crates.io

to use this library you have to add following line in dependency section of cargo.toml

lengthofstring = "0.1.1"

your cargo.toml file should look like this:

[package]
name = "hello_world"
version = "0.1.0"
authors = ["ZAN-UL-AABEDEEN<zan.ul.aabedeen@gmail.com>"]
edition = "2018"

[dependencies]
lengthofstring = "0.1.1"
In src/main.rs you can use like this:

use legthofstring;
fn main() {
    let string = "A String of your choice".to_string();
    legthofstring::legthofstring(&string);
}
following will also work:

use firstwelcome::hello;
fn main() {
    println!("Hello, world!");
    hello();
    }
