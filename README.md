documentation for learning

1. when running "npx vite", terminal returns unexpected token { } - this was due to incompatible node version. use "nvm install node" to use the latest version. the error should go away when you run the command again

2. vite is a build tool

3. error - esbuild complains wrong package for arm64 platform - https://blog.hao.dev/fixing-esbuild-related-cpu-architecture-error-on-apple-silicon-macs . reinstall node modules and package-lock. i have installed the lts version. could not replicate bug. read up on esbuild https://dev.to/zaydek/what-is-esbuild-2ofc#:~:text=esbuild%20is%20a%20CLI%2C%20NPM,in%20Go%20and%20JavaScript%20%2F%20TypeScript.
