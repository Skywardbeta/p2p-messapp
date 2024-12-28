# P2P Chat in Rust

This is a deno repo of an IP-based p2p chat for the design of light-weight messaging app for bp

## Installation

To install and run the application, follow these steps:

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/alexrohrberg/berg-chat.git
   ```

2. Navigate to the project's directory:

   ```shell
   cd your-repo
   ```

3. Build the project using `cargo`:

   ```shell
   cargo build
   ```

## Usage

This command will compile and run the application. Make sure you have an active internet connection to connect with other peers.
```shell
cargo run
```

## Testing on Local Host

By default the app starts on localhost:8081
To test this app with 2 peers, first start up the 1st peer.

```shell
cargo run
```

Then change the port in server.rs to some other port (e.g. 8080), save server.rs, switch terminal tabs and run cargo run once more to startup a second peer.

```shell
cargo run
```

## License

This project is licensed under the [MIT License](LICENSE). 
