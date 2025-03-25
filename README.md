# wasm-io-2025

Three demos for each computing era. 

## POSIX

During the POSIX era, application development relied heavily on broad, implicit access to system resources like the filesystem, network, and environment variables—often leading to over-privileged execution and security risks. WASI introduces a modern approach by offering the familiar capabilities of POSIX (e.g., file I/O, sockets, clocks) but in a sandboxed, capability-based model. Instead of assuming access, WASI requires explicit permission for each resource, aligning with the principle of least privilege. This is why a comparison to POSIX-based environments was made, highlighting how WASI modernizes the execution model without sacrificing power or portability.

For additional reading, checkout wasmCloud's guide to [composition](https://wasmcloud.com/docs/concepts/linking-components/linking-at-build/#example-composition).

## Containers

The goal was to use state-of-the-art container orchestration that includes all the necessary features a large enterprise needs, including scale-to-zero. This is why a comparison between wasmCloud and Knative was created. Check out the Knative setup at [knativepay](https://github.com/ricochet/knativepay).

## Components

Enterprises rely on key architectural patterns to ensure success. Our demo of [wasmpay](github.com/cosmonic-labs/wasmpay) showcases how platform engineering teams can manage and evolve capabilities independently of developer code by using a component that serves as a platform harness. It also highlights a platform model that integrates workload identity, enabling secure operations across multi-cloud environments.
