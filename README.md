# HelloPhoenix

To start your Phoenix app:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Install Node.js dependencies with `npm install`
  * Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: http://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix

Following Tutorials:
  * http://www.phoenixframework.org/docs/up-and-running
  * http://codetunes.com/2015/phoenix-blog/

Upon first run of `mix phoenix.server` there were no styles and odd warnings about js errors.
Updating/installing babel-preset seemed to help fix this: `npm install --save-dev babel-preset-es2015`
Running `mix phoenix.server` then compiled properly and served styles.
