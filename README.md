# rust-3d-demo
  An example of how you can do 3D graphics in the browser with Rust and WebGL.

# prerequisites
  Rustup
    I'm using version 1.19.0.  If you have trouble, you might want to peg your verions to that.
    If you need help getting this set up, I have a youtube tutorial at https://youtu.be/f6tizikEMTk
  NPM
    - I'm using version 6.4.1.  If you have trouble, you might want to peg your version to that.
    - To get NPM and Node, go to https://www.npmjs.com/get-npm
  Node
    - I'm using version v10.13.0.  If you have trouble, you might want to peg your version to that.
    - Node will automatically be installed if you install npm.
  Visual Studio Code
    - To install, go to https://code.visualstudio.com/
    - The is the dev environment I use, but of course you can use your favorite.
    - If you need help getting this environment set up, I have a youtube tutorial at https://youtu.be/f6tizikEMTk

# initialization
    In your command line terminal, type...
        cargo build
            - This will download all your Rust crates and make sure your Rust can build.  May take a minute.
        npm install
            - This will download all you node packages.  May take a minute.

# running
    In your command line terminal, type...
        npm run dev

    - NOTE: The first time you run this is may take a minute to start.  After that, is should take just a few seconds.
    - Live Reloading is enabled.  As you make Rust code changes and press "Save", the browser will automatically reload with the new code.

