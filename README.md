# enchantum-feedstock

This feedstock packages [enchantum](https://github.com/ZXShady/enchantum), a header-only C++ enum reflection library, for the `linux-64` platform.

## Build and test

```bash
pixi install --locked
pixi run build
```

The package is written to `output/linux-64/`. Its CMake configuration exports the `enchantum::enchantum` target.

## Release

Pushing a version tag such as `v0.5.0` builds and tests the package, attaches it to a GitHub release, and uploads it to the [cxxlibs channel](https://prefix.dev/channels/cxxlibs) using trusted publishing.

## License

enchantum is distributed under the MIT License.
