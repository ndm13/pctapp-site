# PCT APP Site
This repo will see some major changes as things get consolidated.  As
it stands, `htmlversion` represents what is currently live, `kurotowa`
represents the efforts to simplify the code base, and `pico` represents
the target CMS installation that `kurotowa` will eventually be mapped
onto.

If you don't feel like setting up FTP but really need to make a major
change, fork, merge, and poke me on Discord and I'll integrate it.
Maybe I'll look into a CI solution at some point, but I doubt this will
reach the point where we'll need one.

Best way to get things fixed is still the Discord.

-----

The plan as of now is to migrate all of  `htmlversion` to something
passable in `kurotowa`, and once we've hit consensus I'll drop
`htmlversion` from the repo and `kurotowa` will be used as the template
for `pico`, which will become the new repo root.  Maybe at that point
we'll just use the GitHub for `/content`, `/themes`, `/plugins` and
`/config`, but that's a few dozen commits dedicated solely to cleanup
down the road.
