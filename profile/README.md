# Tilekit: A fast streaming compute engine for the multicore era.

Tilekit streamlines the development process for data-intensive workloads, such as massive geospatial, medical, time-series, and nearly any large structured dataset, on any platform and over the network. It does this by abstracting low-level, performance-centered tools like Arrow, WASM, WebGPU, and WebTransport. In essence, TileKit empowers regular developers to tap into performance levels that previously required dedicated research and teams of people to achieve.

At present, as part of our exploratory research around single source kernels and automatic parallelization techniques, we are openly conducting a series of [hacks](https://github.com/tilekit/hacks) and making upstream [open source](https://github.com/tilekit/opensource) contributions to build the engine from the ground up with quality foundations. Our ambition is to design it as close to the machine as possible, with minimal external dependencies. This approach allows for full control of the ecosystem, including the API, memory, and execution.

A technical preview, serving as an experimental shell for testing compute kernels, is scheduled for Q1 2024.

# Seeking Collaboration
Contributions are very much welcomed even without large experience in open web standards or Rust. We hope that this project can be a sandbox for all of us to learn more about those technologies beyond this project's initial scope. 

Please don’t hesitate to contact us at [hello@tilekit.dev](mailto://hello@tilekit.dev) or join our [Discord](https://discord.gg/jNaYqjgRsB). We're open to collaboration and ready to help.
