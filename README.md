# OpenAI Gym written in pure Rust for blazingly fast performance :rocket:

This library aims be be as close to the original OpenAI Gym library which is written in Python
and translate it into Rust for blazingly fast performance.
This will make the use of Python unnecessary which is awesome.

If you don't mind Python and would like to use the original implementation from Rust,
check out a gym [wrapper](https://github.com/MrRobb/gym-rs).

### Demonstration

![cart_pole](assets/cartpole.png)

![mountain_car](assets/mountain_car.png)

### Usage

To use this crate in your project, put this in your Cargo.toml:

```toml
gym_rs = "1.0.0"
```

### TODOs:

- [ ] Implement more environments.
- [ ] Compare performance to gym-rs python wrapper.
- [ ] Make generic implementation and compare f32 vs f64 performance.
- [ ] Publish on crates.io.
- [ ] Introduce gif render style, so that black themed output is possible.

### Contributing

All contributions are welcomed.

If you would like to add an environment or a feature, please fork this repository and create a pull request
with your changes. Adding new environments should be as easy as translating from Python to Rust. See
[OpenAI/gym](https://github.com/openai/gym)
for environments that are not yet implemented here! There is a lot of easy work to be done here.
Any help is highly appreciated and benefits the Rust and ML/AI community greatly!

### Donations :moneybag: :money_with_wings:

I you would like to support the development of this crate, feel free to send over a donation:

Monero (XMR) address:

```plain
47xMvxNKsCKMt2owkDuN1Bci2KMiqGrAFCQFSLijWLs49ua67222Wu3LZryyopDVPYgYmAnYkSZSz9ZW2buaDwdyKTWGwwb
```

![monero](img/monero_donations_qrcode.png)

### License

gym-rs is licensed under MIT License just like OpenAI's Gym.

See [LICENSE.md](https://github.com/MathisWellmann/gym-rs/blob/master/LICENSE.md) for further details.
