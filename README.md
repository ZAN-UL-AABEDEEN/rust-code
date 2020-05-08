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

use lengthofstring::length;
fn main() {
    let string = "A String of your choice".to_string();
    let x = length(&string);
    println!("The length of given string is: {}",x);
    }
