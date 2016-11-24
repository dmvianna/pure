# pure

I almost finished [haskellbook](www.haskellbook.com), and I'm looking for a convenient way to write Haskell in the browser. After a good lookaround even bits of the `GHCJS` documentation suggest that I use Purescript instead. So I'll bite the bullet and try to get used to it as I am eager to start using it in the real world.

### How to start

There are some things that always trip me up when I clone purescript projects in a new machine. So I list them here:

1. Install pulp & bower globally

    ```bash
    $ npm i -g pulp bower
    ```

2. Pull whatever libraries you need (from the project's root directory)
   ```bash
   $ npm i
   $ bower i
   ```

3. Make an initial build from the prompt. `psci-ide` won't help you the first time you build your project. It will afterwards.
   ```bash
   $ pulp build
   ```
